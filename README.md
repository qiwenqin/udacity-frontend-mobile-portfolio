--------------------------
HOW TO RUN THE APPLICATION
--------------------------
1.Open the browser,and click [here](https://qiwenqin.github.io/udacity-frontend-mobile-portfolio/) to run the application.
2.Or you can clone the repository (fork first if necessary).
```
  git clone git@github.com:abustamam/mobile-portfolio.git
  cd mobile-portfolio
```

Alternatively, you can use ngrok, but site will not be completely optimized because ngrok does not compress files.

--------------------
OPTIMIZATIONS I MADE
--------------------
1. index.html -> PageSpeed score >90 :
- inline above-the-folde css and defer unneccessary styles, script
- delete the css and javascipt files which had been inlined, compress all the images
- erase some unneccessary styles in style.css

2. main.js -> 60FPS when scroll & Resize pizza size less than 5ms :
- define variables outside the for loops
- replace querySelector with getElementById, getElementsByClassName
