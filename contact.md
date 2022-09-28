---
layout: default
banner-image: /img/Contact_Us Original.jpg
---

  <h2>Contact us</h2>
<div id="contact-container">
  <div id="contact-details">

    <h3>Physical address</h3>
    HQ New Zealand Cadet Forces  <br>
    Building CA 6  <br>
    Camp Rd  <br>
    Trentham Military Camp  <br>
    Upper Hutt  <br>

    <h3>Postal address</h3>
    HQ New Zealand Cadet Forces  <br>
    Trentham Military Camp  <br>
    Private Bag 905  <br>
    Trentham 5018<br>

    <h3>Phone</h3>
    NZCF HQ: (04) 816-8678

  </div>

  <div id="contact-form">
    <h3>Message HQ</h3>
    <p>Note: all form fields are required</p>
    <form name="contact" method="POST" netlify-honeypot="bot-field" data-netlify-recaptcha="true" data-netlify="true">
      <ul>
        <li style="display:none">
          <label>
            Don’t fill this out if you’re human: <input name="bot-field" />
          </label>
        </li>
        <li>
          <label for="name">Name:</label>
          <input type="text" id="name" name="user_name" required>
        </li>
        <li>
          <label for="mail">E-mail:</label>
          <input type="email" id="mail" name="user_email" required>
        </li>
        <li>
          <label for="msg">Message:</label>
          <textarea id="msg" name="user_message" required></textarea>
        </li>
        <li><label for="recaptcha">reCAPTCHA:</label><div data-netlify-recaptcha="true"></div></li>
        <li class="button">
          <button type="submit">Send your message</button>
        </li>
      </ul>
    </form>
  </div>

</div> <!--Contact container -->

<div class="btn-container">
    <a href="/units" class="join-btn">Join now!</a>
</div>
