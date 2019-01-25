---
layout: page
title: About Me
tagline: Max Base
---

# Max
I'm a compiler engineer, low-level developer and full-stack programmer in the world like others.


#### Because this page contains some private information, you need a password to view the details.

<input type="password" name="password" id="password">
<button id="view">View full the details</button>

<script>
let button=document.querySelector("#view");
let password=document.querySelector("#password");
if(button && password)
{
  let secrets=document.querySelectorAll(".secret");
  console.log(secrets);
}
else
{
  alert("Error!");
}
</script>
<style>
.secret
{
  display: none;
}
</style>

## Skills

<div class="secret">
  - Compiler
  - Assembly
  - C
  - ...
</div>
 
## Projects

<div class="secret">
  - ...
</div>

## Works

<div class="secret">
  - ...
</div>

## Education

<div class="secret">
  - ...
</div>
