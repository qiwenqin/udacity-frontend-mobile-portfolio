--------------------------
HOW TO RUN THE APPLICATION
--------------------------
1.Open the browser.and enter the

--------------------
OPTIMIZATIONS I MADE
--------------------
1. index.html -> PageSpeed score >90 :
- inline above-the-folde css and defer unneccessary styles, script
- mibnify html, css, js, optimize images using building tool Gulp
- erase some unneccessary styles in style.css

2. main.js -> 60FPS when scroll & Resize pizza size less than 5ms :
- define variables outside the for loops
- replace querySelector with getElementById, getElementsByClassName
