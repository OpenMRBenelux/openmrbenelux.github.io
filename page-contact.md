---
title: Contact
subtitle: We would love to hear from you!
layout: page
show_sidebar: false
#tabs: example_tabs
#hero_image: assets/ext_images/Home_logo.png
---

<!-- ### <span style="color:#004777"> Contact Form </span> -->

<style>
img {
  width: 30%;
  height: auto;
  display: inline-block;
}
form {
    display: block;
    width: 100%;
    float: left;
    padding-right: 4%;
}
.container-form {
    padding:1px;
}
input[type=text], input[type=email], textarea {
    width: 100%;
    padding: 12px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    box-sizing: border-box;
}
input[type=submit], input[type=reset] {
    width: 120px;
    padding: 12px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    box-sizing: border-box;
}
input[type=checkbox] {
    margin-top: 16px;
}
input[type=submit] {
    background-color: #004777;
    color: white;
    border: none;
}
input[type=submit]:hover {
    opacity: 0.8;
}    
</style>

<p><div style="text-align: justify">Questions or feedback? Do not hesitate and use the <i>Contact Form</i> below to contact us. We will answer you as soon as possible to the best of our abilities!</div></p>
<p><div style="text-align: justify"><b>IMPORTANT</b>: Please disable AdBlock or Privacy Badger when submitting the <i>Contact Form</i>! If you don't, we won't receive your request.</div></p>

<h2 style="color:#004777"> Contact Form </h2>

<form class="container-form" id="contact-form" action="https://script.google.com/macros/s/AKfycbxFvlT1LVB4mrKHuMl0-HkOb62QP4n_rFHm8-6vH7Zhe_CcQ8XX/exec">

<!-- <h2 style="font-family:Courier New; color:#004777; opacity:0.7">Contact Form</h2> -->

  <div class="form-group">
    <label>First Name:</label>
    <input type="text" name="First Name" placeholder="First Name" class="form-control" required>
  </div>

  <div class="form-group">
    <label>Last Name:</label>
    <input type="text" name="Last Name" placeholder="Last Name" class="form-control" required>
  </div>

  <div class="form-group">
    <label>Email:</label>
    <input type="email" name="Email" placeholder="E-mail" class="form-control" required>
  </div>
  <div class="form-group">
    <label>Questions or feedback?</label>
    <!-- <input type="text" name="Message" placeholder="Message" required> -->
    <textarea rows="5" name="Message" placeholder="Questions or feedback?" class="form-control" required></textarea>
  </div>


  <br>

  <div>
    <!-- Enter message: <input type="text" id = "message"> -->
    <!-- <button type="submit" id="submit-form" value="Submit" onclick="showMessage()" >Submit</button> -->
    <input type="submit" id="submit-form" value="Submit" class="form-control">
    <input type="reset" id="reset-form" value="Reset" class="form-control">
 </div>

</form>

<img src="../assets/ext_images/2020/post_separator.png" alt="text"> 
<br>
<a href="#"><i class="fas fa-arrow-alt-circle-up" style="position: relative; top: -3px; text-indent: 0px; vertical-align: middle; color:#004777;"></i></a>

<!-- <p> Message is: <span id = "display_message"></span> </p> -->

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
<script src='../contact.js'></script>
<script src='../subscribe.js'></script>
<script type="text/JavaScript">
function showMessage(){
    //window.alert("Done"); 
    //$("#contact-form")[0].reset();
    // var message = document.getElementById("message").value; 
    // display_message.innerHTML= message; 
}
</script>
