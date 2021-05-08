+++
description = "Você tem alguma pergunta? Você tem algum feedback? Você quer bater um papo? Me envie um e-mail : )"
slug = "contact"
thumbnail = "/uploads/screenshot.png"
title = "Contato"

+++
{{< html >}}  
<div id="contact">

<form name="contact" action="/thank-you" method="POST" netlify>

<h3>Escreva-me uma mensagem : )</h3>

<fieldset>

<div class="field">

<label for="name">Nome<span class="requireed">*</span></label>

<input type="text" name="name" required>

</div>

<div class="field">

<label for="email">E-mail<span class="requireed">*</span></label>

<input type="email" name="email" required>

</div>

<div class="field-group">

<div class="field">

<label for="message">Mensagem<span class="requireed">*</span></label>

<textarea class="huge-field" type="text" name="message" required rows="6"></textarea>

</div>

</div>

</fieldset>

<button type="submit">Enviar</button>

</form>

</div>  
{{< /html >}}