<style>

html {
  background-color: #f2dce7;
  height: 100%;
  background-image: url("data:image/svg+xml,<svg id='patternId' width='100%' height='100%' xmlns='http://www.w3.org/2000/svg'><defs><pattern id='a' patternUnits='userSpaceOnUse' width='20' height='20' patternTransform='scale(4) rotate(45)'><rect x='0' y='0' width='100%' height='100%' fill='%23f2dce7ff'/><path d='M0 0h10v10H0z'  stroke-width='1' stroke='none' fill='%23ffffffff'/><path d='M10 10h10v10H10z'  stroke-width='1' stroke='none' fill='%23ffffffff'/></pattern></defs><rect width='800%' height='800%' transform='translate(0,0)' fill='url(%23a)'/></svg>");
}
#site_header {
  display: block;
  color: #a53860;
  font-size: 14px;
  text-align: center;
  padding-bottom: 5px;
  border-bottom: 2px solid #a53860;
}

#site_footer{
  display: block;
  color: #a53860;
  font-size: 14px;
  text-align: center;
  padding-bottom: 15px;
  border-top: 2px solid #a53860;
  position: flow;
}

#main{
  flex-grow: 1;
}

body{ 
  font-family:verdana;
  color:#450920;
  height:100%;
  font-size:21px;
  background-attachment: fixed;
}
  
.grid-container {
  display: grid;
  grid-template-columns: 1fr 7fr; 
  padding: 50px;
  gap: 20px;
}

.infocol{
  background-color: #ffe5f1;
  border-radius: 10px;
  border: 3px outset #ffdbeb;
  padding:10px;
}

.maincol{
  background-color: #ffe5f1;
  border-radius: 10px;
  border: 3px outset #ffdbeb;
  padding:10px;
}

@view-transition {
  navigation: auto;
}

::view-transition-old(root),
::view-transition-new(root) {
  animation-duration: 0.3s;
  background-color: #f2dce7; 
  mix-blend-mode: normal;
}

}
</style>
<head>
<link rel="icon" href="/assets/favicons/himafava.png">
<title>olivemoment</title>
<meta name="viewport" content="width=device-width,initial-scale=1" />
<meta name="view-transition" content="same-origin" />
<meta name="theme-color" content="#f2dce7">
</head>
  
<header id="site_header">

# olivemoment   
###  "we do a little bandori-ing here"  
  
  </header>

<main>

<div class="grid-container">
  <div class="infocol">
  
  ![himari](/assets/favicons/himafava.png)
  
  links:  
  [take me home!!](/)  
  [about me](/about)  
  [photo album](/album)
  [source](https://github.com/olivemoment/the_site/tree/main)  
  [quotebot](https://quotebot.olivemoment.com/) 
  
  
  
  </div>
  <div class="maincol">
  {{ content }}
  </div>
</div>

</main>

<footer id="site_footer">

<a href="#" onclick="window.scrollTo({top: 0, behavior: 'smooth'}); return false;">
  jump to top
</a>  

### they call me the himari uehara enthusiast

</footer>

</body>