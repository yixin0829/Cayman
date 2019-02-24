---
layout: default
title: Contact
---
Please enter your name, email, and message in the respective boxes:

<form action="//formspree.io/i.webster@mail.utoronto.ca" method="POST">
 <fieldset>
 <label for="name">Your name</label><br>
 <input type="text" name="name" placeholder="Name" id="name" required>
 </fieldset>
 <fieldset>
 <label for="_replyto">Your email</label><br>
 <input type="email" name="_replyto" placeholder="example@domain.com" id="_replyto" required>
 </fieldset>
 <fieldset>
 <label for="message">Your message</label><br>
 <textarea name="message" rows="1" placeholder="Message" id="message" required></textarea>
 </fieldset>
 <input class="hidden" type="text" name="_gotcha" style="display:none">
 <input class="hidden" type="hidden" name="_subject" value="Message via http://domain.com">
<input class="button submit" type="submit" value="Send">
</form>
