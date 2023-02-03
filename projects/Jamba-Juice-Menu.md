---
layout: project
type: project
image: img/JAMBA-JUICE_Orange_Carrot_Karma_1920x976_tcm343-16949.jpg
title: "Jamba Juice Menu"
date: 2023
published: true
labels:
  - Programming
  - JavaScript
summary: "A program containing JavaScript classes in order to create a Jamba Juice menu for ICS 314."
---



In this program, four JavaScript classes were created in order to represent four different menu items based off of a given picture. They were then used to define another class called "Menu". In this particular project, we are asked to create a "MenuItem" class and instances for specific smoothies. The smoothies goes as follows: PapayaSunrise, PeachPerfection, StrawberryDragon, and StrawberryWhirl. Here is the picture provided with the given menu itemsʻ prices, ingredients, and calories depending on size.

<img src="https:///user-images.githubusercontent.com/122927921/216520288-b17e6681-d305-4725-9b7e-6f159823b90e.jpg" width="500" height="600">

For example, an item would be the drink "Strawberry Whirl", its ingredients, the different prices per size, and the specific number of calories for each size. You would then create a class that takes an ingredient string and return whichever smoothies has that specific ingredient. Your end result should be able to input an ingredient and it would find the smoothie names that has that ingredient included.

<hr>

Here is a showcase of the "MenuItem" class and the instances it takes:

" class MenuItem {
	constructor(name, ingredients, price, calories) {
		this.name = name;
  	this.ingredients = ingredients;
  	this.price = price;
 		this.calories = calories;
	}
}

const papayaSunrise = new MenuItem("Papaya Sunrise", ("papaya", "strawberry", "peach"), {small: 5.15, medium: 5.75, large: 6.55}, {small: 190, medium: 280, large: 330});
const peachPerfection = new MenuItem("Peach Perfection", ("peach", "strawberry", "mango"), {small: 5.15, medium: 5.75, large: 6.55}, {small: 210, medium: 320, large: 360});
const strawberryDragon = new MenuItem("Strawberry Dragon", ("pitaya", "strawberry", "orange", "passionfruit", "mango", "banana"), {small: 5.15, medium: 5.75, large: 6.55}, {small: 360, medium: 480, large: 610});
const strawberryWhirl = new MenuItem("Strawberrquy Whirl", ("strawberry", "banana", "apple"), {small: 5.15, medium: 5.75, large: 6.55}, {small: 210, medium: 310, large: 380}); "


<hr>

Source: <a href="https://courses.ics.hawaii.edu/ics314s23/morea/javascript-2/experience-jamba-juice-1.html"><i class="large github icon "></i>ICS-314-Course-Page-JJ1</a>

