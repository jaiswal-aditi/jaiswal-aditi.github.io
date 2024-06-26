---
layout: essay
type: essay
title: De-'sigh'-n Patterns
# All dates must be YYYY-MM-DD format!
date: 2022-04-28
labels:
  - Software Engineering
  - Design Patterns
---

<img class="ui medium right floated rounded image" src="../images/patterns.png">

Do you enjoy food? I do. A lot. I love trying new dishes, restaurants and this experimentation led me to select few of the dishes or restaurants as my favorite ones. I also love watching cooking videos, especially the ones where they give you small tips which can make your food taste good and cooking easier. And that's because they are **experienced** people, who have **tried those specific tips and tricks** and it proved to be useful for them for that dish. They might have also tried **different methods** or even **different dishes** with the same approach and found an optimal way to get the tastiest food. Now I also like to cook those recipes, at home, in a procedural way as they explained. What I'll do, any guesses? Yeah, I'm going to follow that recipe, with the specified measurements of ingredients, step-by-step. If you use the above bold words and somehow put it together you get the motivation behind design patterns.

### The old grandfather's advice

Design patterns are like old-age, experienced grandfather's advice, a time-tested solution to common problems. They have faced the same issues in their time and by different trial and error methods or using someone else's advice they found a way to solve it. And now they are just trying to pass that information onto us so we don't have to go through the rigorous process again but instead focus on our productivity for the bigger problem. Simple, right? But the reason I sighed is because I was expecting this to be a complex, hi-fi, 'techie' topic only to realize this is a very basic idea of making solutions to common problems available for everyone. And this is a reason to sigh because I have been using this in this class, in my small development journey, without even knowing that this is what I have been doing. Starting from architectural field, this 'problem-driven-approach' made its way into software engineering because it makes code reusable and a developer's life easy as they don't have to build everything from scratch. 


### The technicality in design patterns

There are different types of design patterns in software engineering, providing a vocabulary for software development discussion and can be broadly classified as creational, structural and behavioral. 

Creational pattern is more about classic class-object design. These are further subcategorized in other design patterns based on the difference between inheritance in class instantiation and delegation in object creation, but we will not be discussing that here. Structural design uses class and object composition to obtain new functionality. And finally behavioral design patterns identify the communication between objects of the classes.

<img class="ui medium left floated rounded image" src="../images/Observer.png">

### But why am I writing about this?

As mentioned before, I have been using some of the design practices, especially in my final project to speed up the development process, make debugging easier and code reusable. We've been working with Prototype pattern, a type of creational pattern, where we specify the type of objects to be created using an instance and copy it for other objects. This is like mitosis as opposed to the cookie-cutter method which object oriented programming uses.
The another observable design pattern used in our project is "observer" pattern, a subset of behavioral design pattern, which works on a publisher-subscriber paradigm. This takes note of the dependencies between objects and when the state of one object changes, its dependents are updated and notified automatically. For our project, we have a database of papers and reviews on those papers on the server side but we don't want everyone to access or modify it. This publisher-subscriber paradigm provides an architectural mechanism of how the publishers or data sources wnat to make data available to other components. Another example of observer pattern is when we make changes in any part of our code, it automatically updates the web application and other entities.


To sum up these design practices are equally important as good coding practice because a developer's job is not just to write clean codes but an effective code and if reusing some solution is making the process faster, efficient and easy to maintain with minimum ripple effect then why not use it effectively?
