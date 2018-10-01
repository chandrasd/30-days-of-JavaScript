# 30 days of JavaScript
I am challenging myself on JavaScript for 30 days. Inspired by Wes Bos's JavaScript30.
I'm following through the JavaScript30 challenges and I'm exploring various JavaScript techniques to become a better programmer. 
## Day-1 
Web page with Audio buttons that reciprocate a sound from keyboard inputs (ASDF).

## Day-2 
Created a web page with a live clock with hour, minute and second hands.

## Day-3 

Learning how to update CSS variable using JS. Everywhere on the page that variable is referenced will update itself. Whereas in Sass you define the variables at compile time and you can't change it after that.

### Intersting detail:

```JS
JavaScript querySelectorAll('.controls input')
```
This creates a nodeList and has lesser number of prototypes compared a normal Array. Most common practice is to convert it to an Array. 
forEach() method in nodeList is only avaiable in newer versions of a browser.

## Day-4
Learned how to properly use .map(), .filter(), .sort(), .reduce() by doing 8 Array exercises. 
```JS
const totalYears = inventors.reduce((total, inventor) => {
        return total + (inventor.passed - inventor.year);
    }, 0);
 ```
 The value of total is undefined therefore we needed to assign it as 0 by default.
