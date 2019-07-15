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
<main class="fancy">
  <section class="demo">
    <div class="box">
      <h3>Checkbox <br /><small>(Multi-select)</small></h3>
      <p>
        <label for="Cookies">
          <input id="Cookies" name="yaybox" type="checkbox" value="Cookies" checked />
          <span>Chocolate Chip Cookies</span>
        </label>
      </p>
      <p>
        <label for="Milk">
          <input id="Milk" name="yaybox" type="checkbox" value="Milk" />
          <span>Ice Cold Milk</span>
        </label>
      </p>

   <p>
        <label for="Other">
          <input id="Other" name="yaybox" type="checkbox" value="Other" />
          <span>Raspberry-Lemon Pastry with Cream Cheese Frosting and Graham Cracker Crust</span>
        </label>
      </p>

   <hr />

   <h3>Radio Button <br /><small>(Single-select)</small></h3>
      <p>
        <label for="Chocolate">
          <input id="Chocolate" name="yaydio" type="radio" value="Chocolate" />
          <span>Chocolate Candies</span>
        </label>
      </p>
      <p>
        <label for="Strawberry">
          <input id="Strawberry" name="yaydio" type="radio" value="Strawberry" />
          <span>Strawberry Jelly</span>
        </label>
      </p>
      <p>
        <label for="Vanilla">
          <input id="Vanilla" name="yaydio" type="radio" value="Vanilla" checked />
          <span>Vanilla Ice Cream</span>
        </label>
      </p>
    </div>
  </section>
  
  <section class="controls">
    <div>
      <p>
        <label for="sim">
          <input id="sim" name="sim" type="checkbox" value="sim" checked onchange="toggleTheFancy()" />
          <span>Toggle The Fanciness</span>
        </label>
      </p>
      <p>
        <label for="square">
          <input id="square" name="square" type="checkbox" value="square" onchange="toggleTheShape()" />
          <span>Square Checkboxes</span>
        </label>
      </p>
      <p>
        <small>Change width to force line-<br />wrapping. Notice the text alignment!</small><br />
        <label for="slider">
          <input id="slider" type="range" min="5" max="100" value="100" oninput="setProperty('--demo-width', this.value)" />
        </label>
      </p>
    </div>
  </section>
</main>