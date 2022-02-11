---
layout: essay
type: essay
title: Raise your standards
# All dates must be YYYY-MM-DD format!
date: 2022-02-09
labels:
  - Software Engineering
  - Learning
  - Coding Standards
  - ESLint
  - Javascript
---

Maintaining standards, whether in life or in programming, is the key to success. When writing a program, in any language, it is important to keep in mind the basic
coding standards. Now a solution to a problem can be obtained through both the clean and the messy code, with its successful compilation. And for now I'm just working on small projects, but what if we were to maintain a large codebase like Google (discussed [here](https://jaiswal-aditi.github.io/essays/The-multiverse-of-SE.html)), or run multiple applications which requires updates once every few years, which one do you think would be easier to work with? I hope you say the clean one! A clean code, complying to the coding standards, make development, readability, maintenance and debugging of the code much easier. And cleanliness of a code is not just defined by an optimal solution to a problem or its outer beauty, but the inner statements as well. What  variable names you choose, which loop do you prefer, which notation gives better readability, including comments in your code, are just few examples of what a good code looks like.

I am used to Python now and those familiar with the syntax may know that if one were to use a code block of conditional statement or loops or function, you either have to leave 4 blank spaces to indent the code or Python will automatically do that for you. Initially, I'd get annoyed by this because it will always throw an  indentation error. I used to take this in a high-fashion manner thinking that this is code ethics, (what I meant was coding standard format). Clearly, I was confused between the terms code ethics and coding standards and I didn't pay any attention then. But since then I have come to understanding that this annoying thing is actually very helpful because the next time if I or someone else is trying to read and debug my code, it is so much easier to work wit that (and it sure feels good not seeing any clutter in your piece of code). So, when I started coding in Javascript for this class I was so habitual with the indentation that I will automatically hit the tab button as soon as I was inside a code block! 

### IntelliJ IDEA (indeed a brainy idea by JetBrains)

As we are progressing through the semsester, we are also trying to merge different applications. So we are not limited to just solving some WODs (discussed [here](https://jaiswal-aditi.github.io/essays/Is-Javascript-my-karma.html)), but also learn to use right tools (editors, IDE) and platform (GitHub) to store our work, which eventually I will be using some day in future, after I get a good job (^wink ^wink). We have started with IntelliJ IDEA, an integrated development environment, primarily used for software development using JAVA or Javascript. I have never used this before so I am excited to learn more about its features but for now it seems like a really nicely organized environment. There was a fun activity hosted by our professor so as to declare the *key binding shortcut champion* and though I didn't do well in that, I can see how these shortcuts can make development process much easier. Using key binding shortcuts for any editor or IDE or platform is good to learn because you can do things fastly. (Fun fact: I used to feel so smart after I learned the Linux command lines but it also made working with the system much more faster and simpler.) 

<img class="ui medium right floated rounded image" src="../images/coding-standards.png">

### Making IntelliJ more intelligent with ESLint

Working with IntelliJ allows you to use ESLint as well, which is a pluggable code analysis tool to easily maintain your code and stick to the coding standards while getting fewer errors. It is easy to let your IDE know that it has to use ESLint to report for any errors by setting right preferences. And although it sounds like a great tool, it is kind of annoying. It will report every small details, whether it be a bad variable name, using let instead of const, missing indentation or blank spaces. These things may not negatively affect the functionality of your code or its readability, but behind the scenes ESLint is just trying to maintain its own standards (along with coding standards) and make your and your computer's life easier. So it doesn't have to worry about any variable which you are not going to use later or it doesn't have to hold a variable with a silly name. But the good thing you don't have to manually check everything as it will help you along the process and guide you where the error is by raising red flags and what that error is? You just have to correct those mistakes or maybe use shortcuts to reformat the code automatically and ESLint will approve that by giving a green checkmark!

Overall I'd say I'm starting to see the good side of IntelliJ for developing a Javascript project and how ESLint can make your code look much presentable and readable. It forces you to follow proper etiquettes to become a better developer or programmer and make the collaborative projects look good. In the initial stage, we all use some random variable names like 'foo' to store the results temporarily and see what the code is doing. And that is okay, but once you become more confident about your work and start working in collaboration with others, it is always a better idea to use releveant variable names so that when you or others take a look at your code (or are trying to debug it), you'd know what that variable was supposed to do. ESLint allows you to maintain a consistent style across your code through a good platform IntelliJ. So all you have to do is sit back, relax, and work on your code because ESLint is here to help you with your coding journey.




