---
layout: essay
type: essay
title: You and I, let's learn Semantic UI 
# All dates must be YYYY-MM-DD format!
date: 2022-02-24
labels:
  - Software Engineering
  - UI Frameworks
  - html, css
---

<img class="ui small right floated rounded image" src="../images/semantic.png">

### Vanilla CSS vs (other flavoured) CSS frameworks

You ever look at a few beautifully designed websites, compatible with all browsers and wonder how much effort was put into those? I did and I used to imagine a developer, sitting frustrated yet so patient, describing each and every property he wants to show on that website. And maybe that's how everyone starts their frontend web development journey, all excited to change the world with their best development skills, only to realize there are easier ways to do the same thing. And that's the logic of the logical CSS frameworks, to make your life easy. Semantic UI is one such framework which provides all the components, integrated with HTML and CSS, a developer might need which can be accessed through classes. But wait, that does not mean you should directly jump into that. 

~~~
.button {
  background: purple;
  color: white;
  width: 80px;
  height: 40px;
  font-size: 20px;
  font-family: sans-serif;
  cursor: pointer;
}
~~~

~~~
<button class="ui purple button">Run</button>
~~~

Both of these codes generate a pretty much same output: a purple button. And sure enough the latter using semantic UI looks much more readable and simpler, even to a non-programmer, than the former using normal vanilla CSS. So as much as it feels tempting to jump right into learning a CSS framework and skip building the stylesheet from the scratch, you shouldn't. The reason being you would lack the basic understanding of what is going on behind the scenes, what each property is supposed to do, how to use margings and paddings, incorporate your own classes or if not any of these you might end up using some boilerplate code with unnecessary things. And for a programmer working in a big company this doesn't seem like a good idea. This is how we did things in our class too, taking one step at a time. For first week of this module we relied on basic html and css syntax, controlling and customizing all the styles by ourselves. And then from second week we switched gears into Semantic UI.  


### Managing front-end semantics with Semantic UI

Without any doubt these frameworks are one of the best things in the web development world, giving the programmers a lot of flexibility and better efficiency to read and write code. On a larger scale, it makes things even easier across an organization or working in collaboration, by giving a sense of consistency and better compatibility with multiple browsers and devices. Since this is the first CSS framework I am learning I was really quite amazed by its functionality. And for now my experience might be biased towards Semantic UI because this is the most recent and only framework I have learned so far, so it may change if I end up learning other frameworks. But back to the functionality of semantic UI, it is not as easy as it seems to be. As I mentioned before, you need to understand how things work under the hood, what different properties (with predefined values) are and how their values can change your webpage. For example to divide your working space into columns, you should know that the right class to use is `grid` along with a class called `column`. Or since you don't have to specify rows in the grid if you are defining a column of certain width, the other columns might move to the next row (as the default column count for a row in Semantic UI is 16). Don't worry, these syntax might look like a bit of a headache at first (and maybe they are) but you are not supposed to remember all these things because you can find all the information [here](https://semantic-ui.com/), on the official documentation of the framework. One good thing about these frameworks are that they live upto their names and focus on semantics too, i.e. you don't have to worry about dealing with some scary programming terms or weird syntax because they use basic English labels as their keywords to define each component. Phew!

### My experience with new CSS flavor

I didn't perform well in my WOD today or in simpler terms I wasn't able to finish a classwork assignment, in time. The reason being `<body>` tag! Yeah, the good old `<body>`. I was supposed to set the background image to this tag but somehow I didn't realize this and was working on a middle menu instead (I know so dumb right). And to be honest I cried a lot after my class because I kind of felt stupid but then I thought this is what learning phase is supposed to look like. And if you look from a developer's point of view maybe this is how things are built. You fail, you make silly mistakes but then you learn and make note of those mistakes and try to simplify those for others as well. Maybe this is what the developers of Semantic UI thought too and that's why from the basic html, css, they came up with the idea of frameworks[^1] (or maybe I'm stil upset and trying to comfort myself with these stupid ideas, who knows?) But anyways what I mean to say is that even though these frameworks are useful to learn, to enjoy all the flavors associated with it you will have to give it some time and get used to working with different classes, properties, tags, tools and how to apply those. After all these frameworks are the cooked meal you can enjoy while building your website but don't forget that the HTML and CSS are the basic ingredients, without which you won't be able to enjoy the meal as much!

[^1]: I think the developers always pay attention to all the details of the frameworks they are building or people might end up writing about it, like I did for this post!

