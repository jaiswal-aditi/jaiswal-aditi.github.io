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

You ever look at few beautifully designed websites, compatible with all browsers and wonder how much effort was put into this. I did and I used to imagine a developer, frustrated yet sitting so patiently, describing each and every property he wants to show on that website. And maybe that's how everyone starts their frontend web development journey, all excited to change the world with their best development skills, only to realize there are easier ways to do the same thing. And that's the logic of the logical CSS frameworks, to make your life easy. Semantic UI uses provides all the components, integrated with html and CSS, a developer might need and this can be accessed through different classes. But wait. That does not mean you should directly jump into that.

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

Both of these codes generate a pretty much same output: a purple button. And sure enough the latter, which uses semantic UI looks much more readable and simpler to than the former, which is normal vanilla CSS. As much as it feels tempting to jump right into learning a CSS framework and skip building the stylesheet from the scratch, you shouldn't, because then you would lack the basic understanding of what is going on behind the scenes, what each property is supposed to do, using margings and paddings, incorporate your own classes or you might end up using some boilerplate code with unnecessary things. And so this is how we did things in our class too. For first week of this module we relied on basic html and css syntax, controlling and customizing all the styles by ourselves. And then from second week we switched gears into Semantic UI.  


### Managing front-end semantics with Semantic UI

Without any doubt these frameworks are one of the best things in the web development world, giving the programmers a lot of flexibility and better efficiency to read and write code. On a larger scale, it makes things even easier across an organization or working in collaboration, by giving a sense of consistency and better compatibility with multiple browsers and devices. Since this is the first CSS framework I am learning I was really quite amazed by its functionality. But it's not as easy as it seems to be. As I mentioned before, you need to understand how things work under the hood, what different properties (with predefined values) are and how their values can change your webpage. For example to divide your working space into columns, you should know that the right class to use is `grid` along with a class called `column`. Or since you don't have to specify rows in the grid if you are defining a column of certain width, the other columns might move to the next row (as the default column count for a row in Semantic UI is 16). And don't worry, you are not supposed to remeber all these things because you can find all the information [here](https://semantic-ui.com/), the official documentation of the framework. The good thing about the frameworks are they live upto their names and focus on semantics too, i.e. you don't have to worry about being scared by some programming terms or weird syntax but the keywords are basic English labels to define each component.

