---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<nav class="navbar">
    <div class="container">
        <div class="menu-toggle" id="mobile-menu">
            <span class="bar"></span>
            <span class="bar"></span>
            <span class="bar"></span>
        </div>
        <ul class="nav-list">
            <li><a href="/#home">Home</a></li>
            <li><a href="/#about">About</a></li>
            <li><a href="/#portfolio">Portfolio</a></li>
            <li><a href="/#incubation">Incubation</a></li>
            <li><a href="/#contact">Contact</a></li>
        </ul>
    </div>
</nav>
<section>
    <section id="home">
        <div class="container">
            <div class="logo">
                <img src="{{ 'assets/images/ComonadLogoConcept.png' | relative_url }}" alt="Comonad.ai Logo">
            </div>
            <div class="desc">
                <p>We're incubating the next generation of Platform, SaaS, Data Infrastructure & Vertical AI startups.</p>
                <p>Built in India, for the world.</p>
                <p>Our services include early stage funding, fractional CTO, PMF, GTM & Operations for India-US corridor.</p>
            </div>
        </div>
    </section>
    <section id="about">
        <div class="container">
            <h3>About</h3>
            <div class="desc">
                <p>We build and advise the next generation of tech startups in India. Our mission is to help Indian startups build world class products for a global audience.</p>
                <p>Our portfolio focus is on early to growth stage B2B SaaS, Platform infrastructure & Vertical AI.</p>
            </div>
        </div>
    </section>
    <section id="portfolio">
        <div class="container">
            <h3>Portfolio</h3>
            <div class="product-logs">
                <div class="prod-logo">
                    <img src="{{'assets/images/apinomy-logo.png' | relative_url}}" alt="Apinomy Logo">
                </div>
                <div class="prod-logo">
                    <img src="{{'assets/images/eventception-logo.png' | relative_url}}" alt="Eventception Logo">
                </div>
                <div class="prod-logo">
                    <img src="{{'assets/images/rtdx-logo.png' | relative_url}}" alt="RTDX Logo">
                </div>
            </div>
        </div>
    </section>
    <section id="incubation">
        <div class="container">
        <h3>Incubation</h3>
            <div class="desc">
                <p>We provide a broad range of advisory services to incubatees.</p>
                <ul>
                    <li>Product Market Fit</li>
                    <li>CTO in Residence & Engineering Advisory</li>
                    <li>Global GTM: 0-1 and Growth</li>
                    <li>India-US Corridor</li>
                    <li>Investor & VC Nexus</li>
                </ul>
            </div>
        </div>
    </section>
    <section id="contact">
    <div class="container">
    <h3>Contact</h3>
    <div class="contact-container">
                <div class="hbspot-form">
                    {% include contactform.html %}
                </div>
                <div class="address-info">
                    <div>
                        <!-- <h5 class="mt-4">Singapore</h5> -->
                        <!-- <p>{{ site.data.contact.singapore_office }}</p> -->
                        <div class="address">
                <h5>India.</h5>
                <address>
                    43 Worklabs <br>
                    232, 2nd Floor (STE1), 9th Main Road<br>
                    Kalyan Nagar 1st Block <br>
                    Bangalore - 560043
                </address>
                </div>
                        <!-- <p><a href="tel: {{ site.data.contact.phone }}"> {{ site.data.contact.phone_in }} </a></p> -->
                        <div class="d-flex email-block">
                            <span>Email : </span>
                            <a href="mailto: {{ site.data.contact.email }}">{{ site.data.contact.email }}</a>
                        </div>
                        <iframe src="https://www.google.com/maps/embed?pb=!1m13!1m8!1m3!1d242.95558230905038!2d77.6472345735718!3d13.01723905224784!3m2!1i1024!2i768!4f13.1!3m2!1m1!2zMTPCsDAxJzAyLjgiTiA3N8KwMzgnNTAuOSJF!5e0!3m2!1sen!2sin!4v1741870155131!5m2!1sen!2sin"  style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <div id="contact-modal" class="modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <div class="flex">
                <div class="col-12 col-md-6 hbspot-form">
                    {% include contactform.html %}
                </div>
                <div class="col-12 col-md-6 address-info">
                    <div>
                        <!-- <h5 class="mt-4">Singapore</h5> -->
                        <p>{{ site.data.contact.singapore_office }}</p>
                        <!-- <p><a href="tel: {{ site.data.contact.phone }}"> {{ site.data.contact.phone_in }} </a></p> -->
                        <div class="d-flex email-block">
                            <span>Email : </span>
                            <a href="mailto: {{ site.data.contact.email }}">{{ site.data.contact.email }}</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>  
</section>
<script>
     document.addEventListener('DOMContentLoaded', function () {
    const mobileMenu = document.getElementById('mobile-menu');
    const navList = document.querySelector('.nav-list');
    const navLinks = document.querySelectorAll('.nav-list li a');
    // Toggle mobile menu
    mobileMenu.addEventListener('click', function () {
        navList.classList.toggle('active');
    });
    // Close mobile menu when a link is clicked
    navLinks.forEach(link => {
        link.addEventListener('click', function () {
            navList.classList.remove('active');
        });
    });
})
</script>