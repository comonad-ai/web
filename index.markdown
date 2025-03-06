---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<nav class="navbar">
        <ul>
            <li><a href="/#home">Home</a></li>
            <li><a href="/#about">About</a></li>
            <li><a href="/#incubation">Incubation</a></li>
            <li><a href="/#contact">Contact</a></li>
        </ul>
</nav>
<section>
    <section id="home">
        <div class="logo">
            <img src="{{ 'assets/images/ComonadLogoConcept.png' | relative_url }}" alt="Comonad.ai Logo">
        </div>
        <div class="desc">
            <p>We're incubating the next generation of Platform, SaaS, Data Infrastructure & Vertical AI startups.</p>
            <p>Built in India, for the world.</p>
            <p>Our services include early stage funding, fractional CTO, PMF, GTM & Operations for India-US corridor.</p>
        </div>
    </section>
    <section id="about">
        <div class="desc">
            <p>We build and advise the next generation of tech startups in India. Our mission is to help Indian startups build world class products for a global audience.</p>
            <p>Our portfolio focus is on early to growth stage B2B SaaS, Platform infrastructure & Vertical AI.</p>
        </div>
    </section>
    <section id="incubation">
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
    </section>
    <section id="contact">
    <div class="flex">
                <div class="col-12 col-md-6 hbspot-form">
                    {% include contactform.html %}
                </div>
                <div class="col-12 col-md-6 address-info">
                    <div>
                        <!-- <h5 class="mt-4">Singapore</h5> -->
                        <!-- <p>{{ site.data.contact.singapore_office }}</p> -->
                        <div class="address">
                <h5>India.</h5>
                <address>
                    HRBR.space <br>
                    STE 1, 232, 9th Main Road,<br>
                    Kalyana Nagar 1st Block <br>
                    Bangalore - 560043
                </address>
                </div>
                        <!-- <p><a href="tel: {{ site.data.contact.phone }}"> {{ site.data.contact.phone_in }} </a></p> -->
                        <div class="d-flex email-block">
                            <span>Email : </span>
                            <a href="mailto: {{ site.data.contact.email }}">{{ site.data.contact.email }}</a>
                        </div>
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d307.48517461459124!2d77.64682082610716!3d13.021658573626059!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bae172ea4cacbfb%3A0xfd7c2fdc99e03a14!2s838%2C%205th%20Cross%20Rd%2C%20HRBR%20Layout%201st%20Block%2C%20HRBR%20Layout%2C%20Kalyan%20Nagar%2C%20Bengaluru%2C%20Karnataka%20560043!5e1!3m2!1sen!2sin!4v1741238731766!5m2!1sen!2sin" width="400" height="240" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
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