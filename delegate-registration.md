---
layout: default
title: Delegate Registration
permalink: /delegate-registration/
robots: noindex
---
<link rel="stylesheet" href="https://cymun2019.github.io/css/form.css">
<h2>Delegate Registration Form</h2>
Personal Information
<form method="POST" action="https://formspree.io/cymun2019.official@gmail.com">
<input style="display: block;" type="text" name="firstname" placeholder="First name">
<input style="display: block;" type="text" name="lastname" placeholder="Last name">
<input style="display: block;" type="date" class="form-control" name="dateofbirth" placeholder="Date of Birth">
  <input style="display: block;" type="email" name="email" placeholder="Your email">
  <input style="display: block;" type="text" name="adress" placeholder="Pernament adress">
  <input style="display: block;" type="text" name="phone" placeholder="Telephone number">
  <input style="display: block;" type="text" name="class" placeholder="Class name">
  <input style="display: block;" type="text" name="speciality" placeholder="Major/concentration/speciality">
  English language proficiency:
  <input style="display: block;" type="radio" name="englishlevel" value="Beginner" checked> Beginner<br>
  <input style="display: block;" type="radio" name="englishlevel" value="Intermediate"> Intermediate<br>
  <input style="display: block;" type="radio" name="englishlevel" value="upper"> Upper-Intermediate
  <input style="display: block;" type="radio" name="englishlevel" value="Advanced"> Advanced
  <input style="display: block;" type="radio" name="englishlevel" value="Fluent"> Fluent
  <input style="display: block;" type="radio" name="englishlevel" value="Native"> Native speaker
  <button style="display: block;" type="submit">SUBMIT!</button>
</form>
<div class="wrapper">
    <form>
        <h1>Material Inputs</h1>
        <h5>Inspired by Google's Material Design guidelines for text fields</h5>
        <div class="btn-box"><a class="btn btn-link" href="https://material.google.com/components/text-fields.html" target="_blank">Design Docs</a></div>
        <hr class="sep" />
        <div class="group"><input type="text" required="required" /><span class="highlight"></span><span class="bar"></span><label>Name</label></div>
        <div class="group"><input type="text" required="required" /><span class="highlight"></span><span class="bar"></span><label>Email</label></div>
        <div class="group"><input type="password" required="required" /><span class="highlight"></span><span class="bar"></span><label>Password</label></div>
        <div class="group"><input type="number" required="required" /><span class="highlight"></span><span class="bar"></span><label>Number</label></div>
        <div class="group"><textarea type="textarea" rows="5" required="required"></textarea><span class="highlight"></span><span class="bar"></span><label>Message</label></div>
        <div class="btn-box"><button class="btn btn-submit" type="submit">submit</button><button class="btn btn-cancel" type="button">cancel</button>
            <h5>*these buttons do nothing <span class="emoji">&#x1F609;</span></h5>
        </div>
    </form>
</div>
