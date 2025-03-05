---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---


<section id="home">
<div class="logo"> <img src="{{ 'assets/images/ComonadLogoConcept.png' | relative_url }}" alt="Comonad.ai Logo"> </div>
<div class="desc"><p>We're incubating the next generation of Platform, SaaS, Data Infrastructure & Vertical AI startups.</p>
<p>Built in India, for the world.</p>
<p>Our services include early stage funding, fractional CTO, PMF, GTM & Operations for India-US corridor.</p>
<div class="cta-container"> <button id="get-in-touch" class="cta-button">Get in Touch</button> </div>
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
