# ColorGame
Can you guess the color?


This is a game I created to refresh my Javascript skills after mostly working with PHP. The goal of the game is 
to guess the color by looking at the RGB color at the top of the page. There are two levels, easy and hard. The 
easy level has 3 different colors to choose from and the hard level has 6. 

**Example**

![print screen](https://github.com/YelenaMerzlyakova/ColorGame/blob/master/colorgame.png)

**Result**

![print screen](https://github.com/YelenaMerzlyakova/ColorGame/blob/master/colorgame2.png)


## Code explained

Here is how you get a random color. 

```Javascript
function randomColor(){
	//pick a "red" from 0 - 255
	var r = Math.floor(Math.random() * 256);
	//pick a "green" from  0 -255
	var g = Math.floor(Math.random() * 256);
	//pick a "blue" from  0 -255
	var b = Math.floor(Math.random() * 256);
	return "rgb(" + r + ", " + g + ", " + b + ")";
}```

