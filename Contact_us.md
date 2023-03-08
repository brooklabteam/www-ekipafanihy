---
layout: page
title: Contact Us
permalink: /contact_us
---

<div class="container">
  <div style="text-align:center">
    <h2>Contact Us</h2>
    <p>Get in touch with Ekipa Fanihy about Master's Student positions, volunteering, our research and conservation efforts and more!:</p>
  </div>
  <div class="row">
    <div class="column">
      <img src="/assets/team/EkipaFanihyLogoWhite.png" style="width:75%">
    </div>
    <div class="column">
      <form action="/action_page.php">
        <label for="fname">First Name</label>
        <input type="text" id="fname" name="firstname" placeholder="Your first name..">
        <label for="lname">Last Name</label>
        <input type="text" id="lname" name="lastname" placeholder="Your last name..">
        <label for="email">Email</label>
        <input type="text" id="email" name="email" placeholder="Your email..">
        <label for="subject">Subject</label>
        <input type="text" id="subject" name="subject" placeholder="Subject or title of message here..">
        <label for="message">Message</label>
        <textarea id="message" name="message" placeholder="Write something.." style="height:170px"></textarea>
        <input type="submit" value="Submit">
      </form>
    </div>
  </div>
</div>

<?php
if($_POST["Message"]) {
mail("fitzk980@gmail.com", ""Subject or title of message here.."",
$_POST["Write something.."]. "From: fitzk980@gmail.com");
}
?>