
<!DOCTYPE html>
<html lang="en">

  <head>

    <!-- Non social metatags -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <meta name="theme-color" content="#157878">

    

    <title>About Me</title>

    
      <!-- Update your html tag to include the itemscope and itemtype attributes. -->
<html itemscope itemtype="http://schema.org/Article">












<!-- Place this data between the <head> tags of your website -->

<meta name="description" content="Max Base" />





<meta itemprop="name" content="About Me" />
<meta itemprop="description" content="Max Base" />

  <meta itemprop="image" content="https://basemax.github.io" />


<!-- Twitter Card data -->
<meta name="twitter:card" content="summary_large_image" />



<meta name="twitter:title" content="About Me" />
<meta name="twitter:description" content="Max Base" />



<!-- Twitter summary card with large image must be at least 280x150px -->

  <meta name="twitter:image:src" content="https://basemax.github.io" />
  <meta name="twitter:image" content="https://basemax.github.io" />

<meta name="twitter:url" content="https://basemax.github.io/about.html" />

<!-- Open Graph data -->
<meta property="og:title" content="About Me" />
<meta property="og:type" content="article" />
<meta property="og:url" content="https://basemax.github.io/about.html" />

  <meta property="og:image" content="https://basemax.github.io" />

<meta property="og:description" content="Max Base" />
<meta property="og:site_name" content="Max" />


<meta property="og:locale" content="" />












    

    <link rel="canonical" href="https://basemax.github.io/about.html">

    

    <link rel="shortcut icon" href="https://basemax.github.io/favicon.ico">
    <meta name="robots" content="noarchive">

    <!-- <link rel="alternate" media="only screen and (max-width: 640px)" href="">
    <link rel="alternate" media="handheld" href=""> -->


    <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,700' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" href="/assets/css/style.css?v=a84d057ccc2c6af821d14b4a564c7be2491233f4">
  </head>
  <body>

    <header class="site-header" role="banner">

  <div class="wrapper">
    
    

    
      <a class="site-title" href="/">Max</a>
    

    
      <nav class="site-nav">
        <input type="checkbox" id="nav-trigger" class="nav-trigger" />
        <label for="nav-trigger">
          <span class="menu-icon">
            <svg viewBox="0 0 18 15" width="18px" height="15px">
              <path fill="#424242" d="M18,1.484c0,0.82-0.665,1.484-1.484,1.484H1.484C0.665,2.969,0,2.304,0,1.484l0,0C0,0.665,0.665,0,1.484,0 h15.031C17.335,0,18,0.665,18,1.484L18,1.484z"/>
              <path fill="#424242" d="M18,7.516C18,8.335,17.335,9,16.516,9H1.484C0.665,9,0,8.335,0,7.516l0,0c0-0.82,0.665-1.484,1.484-1.484 h15.031C17.335,6.031,18,6.696,18,7.516L18,7.516z"/>
              <path fill="#424242" d="M18,13.516C18,14.335,17.335,15,16.516,15H1.484C0.665,15,0,14.335,0,13.516l0,0 c0-0.82,0.665-1.484,1.484-1.484h15.031C17.335,12.031,18,12.696,18,13.516L18,13.516z"/>
            </svg>
          </span>
        </label>

        <div class="trigger">
          
            
            
              
              
            
          
            
            
              
                <a class="page-link" href="/about.html">About Me</a>
              
            
          
            
            
          
            
            
          
        </div>
      </nav>
    
  </div>
</header>


    
    
    

    <section class="page-header">
      <h1 class="project-name">About Me</h1>
      <h2 class="project-tagline">Max Base</h2>
      
      <!-- Post tagline -->
      
      <!-- End: Post tagline -->
    </section>

    <section class="main-content">

      <article>

  <div>
    <h1 id="max">Max</h1>
<p>I’m a compiler engineer, low-level developer and full-stack programmer in the world like others.</p>

<h4 id="because-this-page-contains-some-private-information-you-need-a-password-to-view-the-details">Because this page contains some private information, you need a password to view the details.</h4>

<p><input type="password" value="ABCDEFGHIJKLMNOPQRSTUVWXYZ" name="password" id="password" required="true" />
<button id="view">View full the details</button></p>

<style>
.secret
{
  display: none;
}
</style>

<h2 id="skills">Skills</h2>

<div class="secret">
<ul>
  <li>Compiler</li>
  <li>Assembly</li>
  <li>C</li>
  <li>...</li>
</ul>
</div>

<h2 id="projects">Projects</h2>

<div class="secret">
<ul>
  <li>...</li>
</ul>
</div>

<h2 id="works">Works</h2>

<div class="secret">
<ul>
  <li>...</li>
</ul>
</div>

<h2 id="education">Education</h2>

<div class="secret">
<ul>
  <li>...</li>
</ul>
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
  // console.log(maps);
  let index=0;
  for(character of input)
  {
    // console.log("Current : " + character);
    if(maps[character])
    {
      // console.log("Is My Map : " + maps[character]);
      result+=maps[character];
    }
    else
    {
      // console.log("Not My Map!");
      result+=character;
    }
    // else{}
    // index++;
  }
  return result;
}
function passwordMap(pass)
{
  // console.log("Password : " + pass);
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
function checkElement(secret)
{
  // console.log(secret);
  let childs = secret.children;
  for(child of childs)
  {
    // alert( child.textContent);
    if(child.children.length >0)
    {
      // console.log("have child");
      // checkElement(child.children);
      for(child_children of child.children)
      {
        checkElement(child_children);
      }
    }
    else
    {
      // console.log("Item : "+child.innerText);
      child.textContent=parse(child.textContent);
    }
  }
  // secret.innerHTML=parse(secret.innerHTML);
  secret.style.display="block";
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
        checkElement(secret);
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


  </div>

</article>


      <footer class="site-footer">
        <!-- SVG icons from https://iconmonstr.com -->

        <!-- Github icon -->
        <span class="my-span-icon">
          <a href="https://github.com/BaseMax" aria-label="BaseMax's GitHub" title="BaseMax's GitHub">
            <svg class="my-svg-icon" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
          </a>
        </span>

        <!-- Twitter icon -->
        <span class="my-span-icon">
          <a href="https://twitter.com/" aria-label="BaseMax's Twitter" title="BaseMax's Twitter">
            <svg class="my-svg-icon" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm6.066 9.645c.183 4.04-2.83 8.544-8.164 8.544-1.622 0-3.131-.476-4.402-1.291 1.524.18 3.045-.244 4.252-1.189-1.256-.023-2.317-.854-2.684-1.995.451.086.895.061 1.298-.049-1.381-.278-2.335-1.522-2.304-2.853.388.215.83.344 1.301.359-1.279-.855-1.641-2.544-.889-3.835 1.416 1.738 3.533 2.881 5.92 3.001-.419-1.796.944-3.527 2.799-3.527.825 0 1.572.349 2.096.907.654-.128 1.27-.368 1.824-.697-.215.671-.67 1.233-1.263 1.589.581-.07 1.135-.224 1.649-.453-.384.578-.87 1.084-1.433 1.489z"/></svg>
          </a>
        </span>

        <!-- RSS icon -->
        
        <!-- Contact icon -->
        
        
          <span class="my-span-icon">
            <a href="/about.html" aria-label="Contact" title="Contact BaseMax">
              <svg class="my-svg-icon" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .02c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm6.99 6.98l-6.99 5.666-6.991-5.666h13.981zm.01 10h-14v-8.505l7 5.673 7-5.672v8.504z"/></svg>
            </a>
          </span>
        

      </footer>
    </section>

    
  </body>
</html>
