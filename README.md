###SWABATs
+ understand what an object is
+ define new objects
+ understand the philosophy behind object oriented programming
+ understand how to set properties on an object
+ understand how to create object methods
+ understand how to create an object using object literal notation
+ understand what the window object is and how it relates to other objects

###Motivation 
+ Who here has ever played a video game? What games have you played? (Prompt students for examples - look for the Sims, Sim City, civilization, Age of Empires, Starcraft, Command and Conquer, etc.)
+ In the end, most video games are models of the real world. In the Sims we have virtual people, living in houses in a world where they interact with each other. (give other examples: facebook, twitter, etc). How do video game makers and web developers make such complicated worlds, where you can have hundreds or even thousands of players/users on the screen at any moment doing different things? It’s crazy to even think of!
+ The answer is through a type of programming called object-oriented programming. It’s a way a building new objects (players, worlds, cars, anything really) by making ‘factories’ that standardize how the objects are made. Programmers don’t have to code every car in GTA individually, or every sim, or every player in NBA 2K14. What they do is create a ‘template’ for objects that can then be tailored without having to re-create all of the code for each new object.

### Lesson Plan
+ First let’s talk about JS objects. We create JS objects using {}. So for instance let’s create a dog object (open up JS Fiddle to demo).
+ We can create an empty dog object like this:
	+ dog = {};
+ But what good is a blank dog? We want to describe our dog. We need to give our dog attributes. For instance - what color do you guys want our dog to be? We set attributes like this:
	+ dog = {
		+ color: “brown”
	+ } 
+ What name do you want to give him? What are some other attributes that he might have?
	+ dog = {
		+ color: “brown”,
		+ name: “Fido”,
		+ breed: “Beagle”,
		+ age: 12
	+ }
+ There are a few important syntactical things that you should pay special attention to:
	+ Notice that our attribute - color is not in quotes but the value that goes along with it is
		+ The attribute and value can be referred to as a key value pair and the key - or label - does not need to be in quotes - but if the value is a string it does.
		+ Notice age is not in quotes because it is an integer
	+ We use a colon to assign a value to an attribute (never an equal sign)
	+ We separate the key value pairs with commas - notice that the last value is not followed by a comma though
+ Now we have a dog with attributes like color, name, breed. If we just want to see one of those attributes at a time we can access them with something called dot notation. 
	+ If we want to see just the dog’s color we can do dog.color and “brown” will be returned to us <b>(demo this in JS fiddle). </b>
	+ And if we wanted to see the dog’s name? breed? age? dog.name, dog.breed, dog.age
+ We can also create a dog this way. Let’s create a new dog2 = {}
+ Now we just have an empty dog object. <b>Anyone want to guess how we can set the dog’s color?</b> Like this dog.color = “black”. Let’s also set the name, breed and age.
+ Now when we alert dog2 we see that it is an object. <b>What if we want to check the name?</b> dog2.name <b>Age? Breed?</b>
+ Now you guys are going to get some practice with this AND with the data input skills you learned yesterday (jQuery’s .val() method) with a little donut creator lab.


<a href='https://learn.co/lessons/hs-advanced-web-design-teachers-guide-js-object' data-visibility='hidden'>View this lesson on Learn.co</a>
