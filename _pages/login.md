---
permalink: /login.html
layout: login
title: Login
---
<form name="person" class="form-signin">
<img class="mb-4" src="../img/infinityid-logo-1@1x.png" alt=""  height="72">
<h1 class="h3 mb-3 font-weight-normal h32">Please sign in</h1>
<label for="name" class="sr-only h32">Username</label>
<input type="name" id="name" class="form-control" placeholder="Username" required autofocus>
<!-- <input id="name" name="name" value="John">-->
<label for="password" class="sr-only">Password</label>
<input type="password" id="password" class="form-control" placeholder="Password" required>
<input type="checkbox" checked style="color: white;" id="toggle-two" class="h32"></input><label style="color: white;">Remember me</label>
<script>
$(function() {
$('#toggle-two').bootstrapToggle({
on: 'Enabled',
off: 'Disabled'
});
})
</script><br /><br />
<button class="rounded-pill btn btn-lg btn-primary btn-block" type="button" id="btnFetch" onclick="loadDoc()">Sign in</button>
<div id="result1" class="h32 result"></div>
<p class="mt-5 mb-3 text-muted"><div class="h32">&copy; 2017-2020</div></p>
</form>