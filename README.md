# Website Performance Optimization portfolio project

## Instructions
### Installation:

1. Place all files and folders in desired location
2. Host the files locally using prefered method (for example using MINGW64's "python -m SimpleHTTPServer 8080" command or similar)
3. Go to http://localhost:8080 (or whichever port you've chosen) in your prefered browser

### Usage:
1. Explore the various pages by clicking the hyperlinks
2. Go to Cam's Pizzeria and click the various buttons to jump to points on the page or scroll manually
3. Adjust the size of pizza using the slider above the pizza menu

### Optimizations:
1. Images resized and optimized to achieve quicker loads
2. Reduced number of background pizzas drawn
3. Deferred analytics loading and made perfmatters load asyncrhonously
4. Inlined CSS
5. Switched parseInt to Math.floor
6. Adjusted pizza slider's logic to avoid repeated queries
7. Adjusted changePizzaSize's logic to avoid seemingly pointless code
8. Adjusted pizzasDiv's logic to avoid repeated queries
9. Improved position calculation of "dancing" background pizzas by only performing the calculation once, then adjusting the pizzas in groups
10. Added love