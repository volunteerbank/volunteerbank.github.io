---
permalink: /register.html
layout: register
title: Register
---
<form name="person"   class="form-signin1">
<img class="mb-4" src="../img/infinityid-logo-1@1x.png" alt=""  height="72">
<h1 class="h3 mb-3 font-weight-normal h32">A Blockchain Social Platform to Monetize Your Own Data. Earn Crypto & Rewards!</h1>
<table style="width:100%">
<tr><td>
<label for="firstname" class="sr-only h32">First name</label>
<input type="firstname" id="firstname" class="form-control" placeholder="First name" required autofocus>
</td>
<td>
<label for="secondname" class="sr-only h32">Second name</label>
<input type="secondname" id="secondname" class="form-control" placeholder="Second name" required autofocus>
</td>
<td>
<label for="username" class="sr-only h32">Username</label>
<input type="username" id="username" class="form-control" placeholder="Username" required autofocus>
</td>
</tr>
<!-- <input id="name" name="name" value="John">-->
<tr>
<td>
<label for="email" class="sr-only">Email</label>
<input type="email" id="email" class="form-control" placeholder="Email" required>
</td>
<td>
<label for="password" class="sr-only">Password</label>
<input type="password" id="password" class="form-control" placeholder="Password" required>
</td>
<td>
<label for="password" class="sr-only">Password Confirm</label>
<input type="password" id="password" class="form-control" placeholder="Password Confirm" required>
</td>
</tr>
</table>
<input type="checkbox" checked style="color: white;" id="toggle-two" class="h32"></input><label style="color: white;">Recieve SMS Updates.</label>
<script>
$(function() {
$('#toggle-two').bootstrapToggle({
on: 'Enabled',
off: 'Disabled'
});
})
</script><br /><br />
<button class="rounded-pill btn btn-lg btn-primary btn-block" type="button" id="btnFetch" onclick="loadDoc1()">Sign Up</button>