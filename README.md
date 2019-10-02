# ColorGame
Can you guess the color?


This is a game I created to refresh my Javascript skills after mostly working with PHP. The goal of the game is 
to guess the color by looking at the RGB color at the top of the page. There are two levels, easy and hard. The 
easy level has 3 different colors to choose from and the hard level has 6. 

**Example**

![print screen](https://github.com/YelenaMerzlyakova/ColorGame/blob/master/colorgame.png)

**Result**

![print screen](https://github.com/YelenaMerzlyakova/ColorGame/blob/master/colorgame2.png)

As you can see it is an easy exercise to test Javascript skills while having fun. This game is a crowd pleaser and slightly addictive :wink: .


## A bit of code explained

Here is a small snippet of my code. Check out the rest of the file to see the complete code. 

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



