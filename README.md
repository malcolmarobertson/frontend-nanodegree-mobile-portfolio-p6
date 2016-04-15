Project 6 Web Performance
===============================

1. The site (src or dist) must be saved to a web server directory
2. a Python webserver must be enabled using: 'python -m http.server'
3. the website must be run in a browser using 'http://http://localhost:8000/'
4. fixes include:
 - reduced image sizes
 - inlined CSS
 - minmized CSS and JS
 - added async tag to Google Analytics header
 - reduced amount of total pizzas to 'phase' across the page, by row and column in document.addEventListener('DOMContentLoaded', function()
 - used translateX in updatePositions() 
 - took scrollTop out of for look in updatePositions() 
 - refactored changePizzaSizes()
 