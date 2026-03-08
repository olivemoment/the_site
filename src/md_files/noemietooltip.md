<style>

.tooltip {
  position: relative;
  display: inline-block;
  border-bottom: 1px ridge #990000;
  cursor: pointer;
  color: #bb0000;
}

.tooltip-img {
  visibility: hidden;
  opacity: 0;
  position: absolute;
  z-index: 10;
  top: 125%; 
  left: 50%;
  transform: translateX(-50%);
  transition: opacity 0.3s;
  pointer-events: none;
  border-radius: 8px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.3);
}

.tooltip:hover .tooltip-img {
  visibility: visible;
  opacity: 1;
}
</style>
<body style="font-family:georgia">

  # hi again!
  I'm Noémie (or Noemie or Naomi if you're too lazy for the CMS or FR keyboards).  
  
  **FACTS:**
  - My birthday is on January 6  
  
  - My birthdate was in 2010
  
  - do the math
  
    <li>I live in 
      <div class="tooltip">
        La Prairie
        <img src="https://file.garden/aVIi7vQn93xoMwXi/laprairie.JPG" class="tooltip-img" style="height: 256px;" alt="La Prairie">
      </div>, in 
      <div class="tooltip">
        Montérégie
        <img src="https://file.garden/aVIi7vQn93xoMwXi/quebec.jpg" class="tooltip-img" style="width: 256px;" alt="Montérégie">
      </div>, a region on the south shore of Montréal.</li>