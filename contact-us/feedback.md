---
layout: page
title: Feedback
lang: en
ref: feedback
exclude: true
---

> Let us know your thoughts.
##### *This is an anonymous feedback form. Please do not submit any sensitive information.
<script>
function onSubmit(token) {
document.getElementById("invisible-recaptcha-form").submit();
}
</script>

<script src="https://www.google.com/recaptcha/api.js" async defer></script>

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
    cursor: pointer;roid app in react
    
}
</style>


<div class="form-container">
  <form id="invisible-recaptcha-form" action="https://usebasin.com/f/3fe1f57d50e7" method="POST">
    <label for="participation" style="color:#ffae2c">Did you participate in any Anyvision cooking session?</label><br>
    <input type="radio" id="yes" name="yes" value="yes">
    <label for="yes">Yes</label><br>
    <input type="radio" id="no" name="no" value="no">
    <label for="no">No</label><br>
    
    <label for="fname" style="color:#ffae2c">Feedback Recipe Name</label>
    <input type="text" id="recipename" name="recipename" placeholder="Name of the recipe for which you are providing feedback">
    
    <label for="cooked" style="color:#ffae2c">Did you cook the recipe?</label><br>
    <input type="radio" id="yes" name="yes" value="yes">
    <label for="yes">Yes</label><br>
    <input type="radio" id="no" name="no" value="no">
    <label for="no">No</label><br>
    
    <label for="food-good" style="color:#ffae2c">Was the food good?</label><br>
    <input type="radio" id="yes" name="yes" value="yes">
    <label for="yes">Yes</label><br>
    <input type="radio" id="no" name="no" value="no">
    <label for="no">No</label><br>
    
    <label for="food-habit" style="color:#ffae2c">You are</label><br>
    <input type="radio" id="veg" name="food-habit" value="veg">
    <label for="male">Vegeterian</label><br>
    <input type="radio" id="non-veg" name="food-habit" value="non-veg">
    <label for="non-veg">Non-vegeterian</label><br>
    <input type="radio" id="vegan" name="food-habit" value="vegan">
    <label for="vegan">Vegan</label><br>
    
    <input type="hidden" name="_gotcha">

    <label for="subject" style="color:#ffae2c">Suggestions and Comments</label>
    <textarea id="comments" name="comments" placeholder="We appreciate positive as well as negative comments. If you want us to add a particular recipe, let us know." style="height:200px"></textarea>
    
    <input type="submit" value="Submit">
    <div class="g-recaptcha" data-sitekey="6Lew3SMUAAAAAJ82QoS7gqOTkRI_dhYrFy1f7Sqy"></div>
  </form>
</div>
