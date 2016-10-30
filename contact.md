---
layout: page
order: 2
classes: contact

title: Contact
permalink: /contact/
image: about.jpg
---

<form action="http://forms.cassidyjam.es" method="POST" class="grid">
	<input type="hidden" name="ignore" value="not-human" />
	<input type="hidden" name="success" value="/" />
	<input type="hidden" name="error" value="contact/" />
	<input type="hidden" name="site" value="www.katiemkblaede.com" />

	<!-- <div class="whole">
		<select name="subject">
			<option value="Quote">Request a Quote</option>
			<option value="Website Issue">Report a Website Issue</option>
			<option value="Other Inquiry">Other</option>
		</select>
	</div> -->

	<div class="whole">
		<input type="text" name="name" placeholder="Name" required autofocus />
		<input type="text" name="not-human" style="display: none;" />
	</div>

	<div class="whole large-half">
		<input type="email" name="email" placeholder="Email" required />
	</div>

	<div class="whole large-half">
		<input type="tel" name="tel" placeholder="Phone" />
	</div>

	<div class="whole">
		<textarea name="note" placeholder="Comment"></textarea>
	</div>

	<div class="whole">
		<input type="submit" value="Send">
	</div>
</form>
