---
layout: page
title: Contact Us
lang: en
ref: contact-us
---

> Hey there! Let us know your thoughts

<script>
function onSubmit(token) {
document.getElementById("invisible-recaptcha-form").submit();
}
</script>

<style>
.grecaptcha-badge {
    display: none;
}

button.g-recaptcha {
    background-color: #ff0000;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}
</style>

<div class="form-container">
  <form id="invisible-recaptcha-form" action="https://usebasin.com/f/3fe1f57d50e7" method="POST">
    <label for="fname">Your Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your full name">
    
    <label for="country">Email</label>
    <input type="email" id="email" name="email" placeholder="Your email">
    
    <input type="hidden" name="_gotcha">

    <label for="country">Country</label>
    <input type="text" id="fname" name="firstname" placeholder="Your country">

    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Let us know your thoughts. We appreciate positive thoughts as well as negative thoughts. If you want us to add a particular recipe, let us know. If you want to see your recipe here, let us know." style="height:200px"></textarea>

    
    <button class="g-recaptcha" data- sitekey="6Lew3SMUAAAAAJ82QoS7gqOTkRI_dhYrFy1f7Sqy" data-callback='onSubmit' data-badge="inline">Submit</button>
  </form>
</div>