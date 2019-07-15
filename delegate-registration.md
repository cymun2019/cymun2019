---
layout: default
title: Delegate Registration
permalink: /delegate-registration/
robots: noindex
---
<h2>Delegate Registration Form</h2>
Personal Information
<form method="POST" action="https://formspree.io/cymun2019.official@gmail.com">
	   <div class="group">      
    <input type="text" required name="firstname">
      <span class="highlight"></span>
      <span class="bar"></span>
     <label>First name</label>
   </div>
   <div class="group">      
    <input type="text" required name="lastname">
    <span class="highlight"></span>
    <span class="bar"></span>
   <label>Last name</label>
   </div>
	<label for="firstname">First Name</label>
<input style="display: block;" type="text" id="firstname" name="firstname">

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
<form class="form">
  
  <h2>Checkboxes</h2>
  <div class="inputGroup">
    <input id="option1" name="option1" type="checkbox"/>
    <label for="option1">Option One</label>
  </div>
  
  <div class="inputGroup">
    <input id="option2" name="option2" type="checkbox"/>
    <label for="option2">Option Two</label>
  </div>
  
  <h2>Radio Buttons</h2>
  <div class="inputGroup">
    <input id="radio1" name="radio" type="radio"/>
    <label for="radio1">Yes</label>
  </div>
  <div class="inputGroup">
    <input id="radio2" name="radio" type="radio"/>
    <label for="radio2">No</label>
  </div>
</form>