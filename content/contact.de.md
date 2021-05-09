+++
description = "Haben Sie eine Frage? Haben Sie ein Feedback? Wollen Sie sich unterhalten? Schicken Sie mir eine E-Mail : )"
slug = "contact"
thumbnail = "/uploads/screenshot.png"
title = "Kontakt"

+++
{{< html >}}  
<div id="contact">

<form name="contact" action="/de/thank-you" method="POST" netlify>

<h3>Schick mir eine Nachricht : )</h3>

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

<label for="message">Nachricht<span class="requireed">*</span></label>

<textarea class="huge-field" type="text" name="message" required rows="6"></textarea>

</div>

</div>

</fieldset>

<button type="submit">Einreichen</button>

</form>

</div>  
{{< /html >}}