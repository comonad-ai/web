---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---


<section id="home">
<div class="logo"> <img src="{{ 'assets/images/ComonadLogoConcept.png' | relative_url }}" alt="Comonad.ai Logo"> </div>
<h4 class="typewriter" ></h4>
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
        <h5>USA</h5>
        <p> {{ site.data.contact.us_office }}</p>
        <p><a href="tel: {{ site.data.contact.phone }}"> {{ site.data.contact.phone_us }} </a></p>
        <div class="line-seperator"></div>
        <h5 class="mt-4">India</h5>
        <p>{{ site.data.contact.india_office }}</p>
        <p><a href="tel: {{ site.data.contact.phone }}"> {{ site.data.contact.phone_in }} </a></p>
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
