---
layout: project
type: project
image: images/peer-review.jpg
title: Peer Review Project
permalink: projects/peer-review
# All dates must be YYYY-MM-DD format!
date: 2022-05-12
labels:
  - Javascript
  - React
  - MongoDb
  
summary: A web application which allows users to upload their research papers to get peer reviews on it and also review other researcher’s papers.
---

Peer Review Finder is a web application which brings researchers together, by allowing them to upload their research papers to get peer reviews before
publishing them in journals and conferences and also review other researcher’s papers. The basic functionalities of the application allows users to register/login, create a profile, add research interests, upload/edit research papers, view other papers, leave reviews on them. Once a user uploads a paper, it gets stored in the database which is then available to all the registered users to view and leave reviews on. We have added a search bar to filter the papers based on the keywords. There is also a rating feature wherein the uploader can rate the reviews they got on their papers allowing for a constructive feedback and better, collaborative environment. But this feature is also the foundation of the token system, a characteristic which prompts users to remain active on the site, and improves the research process by allowing the users to read and review other papers first, before uploading their paper. We have built the application in a way where each user is given some default token on registering on the platform but to be able to upload more papers, one needs more tokens. These can be credited by providing constructive peer reviews on other user's papers. The original uploader of the paper rates the reviews provided on their paper and based on that tokens are credited to the user who wrote those reviews. We also have some administrator functionality where the admin user can delete papers from the website’s database.

For this project I contributed to both backend and frontend aspect. I started by creating a paper schema to define a structure we'll be using for each paper uploaded on the paper. Next, to continue with the backend side, I linked this schema to an *Add Paper* page using Uniforms, a React library that allows users to upload a paper based on the form type structure. To improve this I also added an *Edit Paper* section to allo users to edit any information they might have entered by mistake. For the review section, I used the Review schema to add an *Add Review* section for the users to leave reviews on the paper. To incorporate the token system I used the Token schema in this section for users to rate the reviews they got on their paper and credit the tokens to the reviewer accordingly. Then I also worked a little bit on the front end side of the project to improve the overall look the pages and add statistics to show many pages, authors, topics are there on our application. To test the codebasewe added tests for each page and component and used testcafe to check those functionalities. 

To sum it up, I really enjoyed working on this group project and my understanding of software engineering as a process and my skills in it have become better. Since this was my first ever software development project there's still room for improvement and there is a lot to learn but the agile project management, team work has taught me a lot. I am thankful to all the group members who were very supportive and guided me through all the steps whenever I got stuck. After this project I can see how development happens in real life in big tech companies, I have become better in using GitHub skills and my overall programming skills using Javascript and its various libraries have improved a lot as well. Also, this project also gave me a real life experience with backend development using MongoDB and Meteor while working with different schemas and collections. Overall it was a fun experience which was challenging at times, but using the internet to ask smart questions (another valuable lesson I learnt from this class) and communicating with team members helped me a lot.

<img class="ui big centered rounded image" src="../images/prf.png">

To see the official web application and learn more about this project you can go [here](https://peer-review-finder.xyz/#/). The project's GitHub repository can be found [here](https://github.com/peer-review-finder/Source-Code) and [here](https://peer-review-finder.github.io/) is a link to our github.io page to visit the step-by-process of the development, community feedback and the milestones from our project board.


