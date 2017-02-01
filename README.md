## Website Performance Optimization portfolio project

####Part 1: Optimize PageSpeed Insights score for index.html

1. Loads asynchronously Google Analytics adding async attribute to the script tag
2. Optimize the images, decreasing their size and compressing them. Generate a smaller version of pizzeria.jpg for index.html
3. Load fonts using Web Font Loader
4. Minify style sheets. 
5. Don't load print css rules for online display adding media="print" attribute
6. Include style.css in HTML to avoid blocking 

####Part 2: Optimize Frames per Second in pizza.html

1. Improve time to resize pizzas changing changePizzaSizes and deleting determineDx
2. Improve frame-rate when scrolling using getElementsByClassName instead of querySelectorAll and calculating position outside the loop in updatePosition
3. Improve frame-rate when scrolling decreasing the amount of pizza when page loads
