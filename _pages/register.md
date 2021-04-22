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
<label for="name" class="sr-only h32">Full name</label>
<input type="name" id="name" class="form-control" placeholder="Full Name" required autofocus>
</td>
<td>
<label for="email" class="sr-only h32">Email Address</label>
<input type="email" id="email" class="form-control" placeholder="Email Address" required autofocus>
</td>
<td>
<label for="name" class="sr-only h32">Username</label>
<input type="name" id="name" class="form-control" placeholder="Username" required autofocus>
</td>
</tr>
<!-- <input id="name" name="name" value="John">-->
<tr>
<td>
<label for="number1" class="sr-only">Phone Number</label>
<input type="number1" id="number1" class="form-control" placeholder="Phone Number" required>
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