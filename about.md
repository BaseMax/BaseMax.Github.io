---
layout: page
title: About Me
tagline: Max Base
---

# Max
I'm a compiler engineer, low-level developer and full-stack programmer in the world like others.


#### Because this page contains some private information, you need a password to view the details.

<input type="password" name="password" id="password" required="true">
<button id="view">View full the details</button>

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

<script>
let button=document.querySelector("#view");
let password=document.querySelector("#password");
function parse(input)
{
  let maps=password();
  console.log(maps);
}
function password()
{
  const getName = (i) =>
  {
       const previousLetters = (i >= 26 ? getColumnName(Math.floor(i / 26) -1 ) : '');
       const lastLetter = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'[i % 26]; 
       return previousLetters + lastLetter;
  }
  let maps={};
  const charStart=33;
  const CharDone=125;
  let passwordIndex=0;
  for(let index=charStart;index<=CharDone;index++)
  {
    // passwordIndex=index-charStart;
    if(! password[passwordIndex])
    {
      passwordIndex=0;
    }
    maps[String.fromCharCode(index)]=password[passwordIndex];
    passwordIndex++;
  }
  return maps;
}
if(button && password && password.value!="")
{
  let secrets=document.querySelectorAll(".secret");
  // console.log(secrets);
  for(secret of secrets)
  {
    // console.log(secret);
    secret.innerHTML=parse(secret.innerHTML);
  }
}
else
{
  alert("Error!");
}
</script>
