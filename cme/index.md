---
layout: page
---

 <html>
  <body>
<!-- START HERE -->
   <link rel="stylesheet" href="https://unpkg.com/purecss@1.0.0/build/pure-min.css">
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
   <!-- Style The Contact Form How Ever You Prefer -->
   <link rel="stylesheet" href="style.css">

  <form class="gform pure-form pure-form-stacked" method="POST" data-email="example@email.net"
  action="https://script.google.com/macros/s/AKfycbzvV3Sc92zus-uVtJk0a33FNfSoK6u6NjcxlLOlqf-e77IDJWc/exec">
    <!-- change the form action to your script url -->

    <div class="form-elements">
      <fieldset class="pure-group">
        <label for="name">First Name: </label>
        <input id="name" name="firstname" placeholder="First Name" />
           <label for="name">Last Name: </label>
        <input id="name" name="lastname" placeholder="Last Name" />
        
      </fieldset>

      <fieldset class="pure-group">
        <label for="message">Message: </label>
        <textarea id="message" name="message" rows="10"
        placeholder="What's on your mind..."></textarea>
      </fieldset>

      <fieldset class="pure-group">
        <label for="email">Your Email Address:</label>
        <input id="email" name="email" type="email" value=""
        required placeholder="your.name@email.com"/>
      </fieldset>

    <!--
<fieldset class="pure-group">
        <label for="color">Favourite Color: </label>
        <input id="color" name="color" placeholder="green" />
      </fieldset>
-->
        

       <fieldset class="pure-group honeypot-field">
        <label for="honeypot">To help avoid spam, utilize a Honeypot technique with a hidden text field; must be empty to submit the form! Otherwise, we assume the user is a spam bot.</label>
        <input id="honeypot" type="text" name="honeypot" value="" />
      </fieldset>
   
    
      <button class="button-success pure-button button-xlarge">
        <i class="fa fa-paper-plane"></i>&nbsp;Send</button>
            </div>


    <div class="thankyou_message" style="display:none;">
     <center>  <h4>Your message has been sent. Thank you. </h4> </center>
    </div>

  </form>
  <script data-cfasync="false" src="form-submission-handler.js"></script>

  </body>
  </html>
