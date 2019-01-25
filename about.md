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
  <li>Compiler</li>
  <li>Assembly</li>
  <li>C</li>
  <li>...</li>
</div>
 
## Projects

<div class="secret">
  <li>...</li>
</div>

## Works

<div class="secret">
  <li>...</li>
</div>

## Education

<div class="secret">
  <li>...</li>
</div>

<script>
let button=document.querySelector("#view");
let password=document.querySelector("#password");
function parse(input)
{
  /*
  input=input.replace("<xtag1567891([^>]+)>","<b$1>");
  input=input.replace("<xtag0512054([^>]+)>","<u$1>");
  input=input.replace("<xtag9744051([^>]+)>","<i$1>");
  input=input.replace("<xtag4971234([^>]+)>","<a$1>");
  input=input.replace("<xtag7621642([^>]+)>","<li$1>");
  input=input.replace("<xtag3497823([^>]+)>","<ul$1>");
  input=input.replace("<xtag0508063([^>]+)>","<div$1>");
  input=input.replace("<xtag4619807([^>]+)>","<span$1>");
  */
  let result="";
  let maps=passwordMap(password.value);
  console.log(maps);
  let index=0;
  for(character of input)
  {
    console.log("Current : " + character);
    if(maps[character])
    {
      console.log("Is My Map : " + maps[character]);
      result+=maps[character];
    }
    else
    {
      console.log("Not My Map!");
      result+=character;
    }
    // else{}
    // index++;
  }
  return result;
}
function passwordMap(pass)
{
  console.log("Password : " + pass);
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
    if(! pass[passwordIndex])
    {
      passwordIndex=0;
    }
    maps[String.fromCharCode(index)]=pass[passwordIndex];
    passwordIndex++;
  }
  return maps;
}
if(button && password)
{
  button.onclick=function()
  {
    if(password.value!="")
    {
      let secrets=document.querySelectorAll(".secret");
      // console.log(secrets);
      for(secret of secrets)
      {
        // console.log(secret);
        let childs = document.body.children;
        for(child of childs)
        {
          // alert( child[i].textContent);
          child[i].textContent=parse(child[i].textContent);
        }
        // secret.innerHTML=parse(secret.innerHTML);
        secret.style.display="block";
      }
    }
    else
    {
      alert("Password Field is empty!");
    }
  }
}
else
{
  alert("Error!");
}
</script>
