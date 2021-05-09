+++
description = "Have any question? Have any feedback? Want to chat? Send me an email : )"
slug = "contact"
thumbnail = "/uploads/screenshot.png"
title = "Contact"

+++
{{< html >}}  
<div id="contact">

<form name="contact" action={{ "/thank-you" | absURL }} method="POST" netlify>

<h4>Send me a message : )</h4>

<fieldset>

<div class="field">

<label for="name">Name<span class="requireed">*</span></label>

<input type="text" name="name" required>

</div>

<div class="field">

<label for="email">E-mail<span class="requireed">*</span></label>

<input type="email" name="email" required>

</div>

<div class="field-group">

<div class="field">

<label for="message">Message<span class="requireed">*</span></label>

<textarea class="huge-field" type="text" name="message" required rows="6"></textarea>

</div>

</div>

</fieldset>

<button type="submit">Send</button>

</form>

</div>  
{{< /html >}}