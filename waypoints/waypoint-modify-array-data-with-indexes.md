#Waypoint: Modify Array Data With Indexes
<a href="http://freecodecamp.com/challenges/Waypoint:%20Modify%20Array%20Data%20With%20Indexes?solution=var%20ourArray%20%3D%20%5B1%2C2%2C3%5D%3B%0AourArray%5B1%5D%20%3D%203%3B%0A%2F%2F%20ourArray%5B1%5D%20now%20equals%20%5B1%2C3%2C3%5D.%0Avar%20myArray%20%3D%20%5B1%2C2%2C3%5D%3B%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0AmyArray%5B0%5D%20%3D%203%3B%0A%0A%2F%2F%20Only%20change%20code%20above%20this%20line.%0A%2F%2F%20We%20use%20this%20function%20to%20show%20you%20the%20value%20of%20your%20variable%20in%20your%20output%20box.%0A%2F%2F%20You%27ll%20learn%20about%20functions%20soon.%0Aif(typeof(myArray)%20!%3D%3D%20%22undefined%22)%7B(function()%7Breturn%20myArray%3B%7D)()%3B%7D%0A" target="_blank">Click here</a> to see the solution on the freeCodeCamp website.


####Instructions:
<p class="wrappable negative-10">We can also modify the data stored in arrays by using indexes.</p><p class="wrappable negative-10">For example:</p><p class="wrappable negative-10"><code>var ourArray = [3,2,1];</code></p><p class="wrappable negative-10"><code>ourArray[0] = 1; // equals [1,2,1]</code></p><p class="wrappable negative-10">Now modify the data stored at index 0 of <code>myArray</code> to the value of 3.</p><div class="negative-bottom-margin-30"><div id="MDN-links"><p class="negative-10">Here are some helpful links:</p></div></div>


####Answer:
```javascript
var ourArray = [1,2,3];
ourArray[1] = 3;
// ourArray[1] now equals [1,3,3].
var myArray = [1,2,3];
// Only change code below this line.
myArray[0] = 3;

// Only change code above this line.
// We use this function to show you the value of your variable in your output box.
// You'll learn about functions soon.
if(typeof(myArray) !== "undefined"){(function(){return myArray;})();}

```