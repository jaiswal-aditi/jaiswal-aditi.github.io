---
layout: essay
type: essay
title: Peer Review Finder
# All dates must be YYYY-MM-DD format!
date: 2022-05-07
labels:
  - Software Engineering
  - Research
  - Publication
---

This is putting everything we learned this semester in a group project, the final step before we go out in the real world of software engineering. 
[Peer Review Finder](https://peer-review-finder.xyz/#/) is a web application to bring researchers together by allowing them to upload their research
papers to get peer reviews before publishing them in journals and conferences and also review other researcher's papers. 

### User Interface walkthrough

On retrieving the application, the user should be able to see a brief introduction of the application system, the current total numbers of papers available on the platform along with the count of number of authors and total topics.

The next step is to login to an existing account or register a new account. After logging in, the user lands on the user home page. Here, the user can see how many new reviews they got on their paper and if there are new papers being uploaded on the platform which matches their interest. The top-left *View Paper* button in the Navbar takes the users to a page where they can see a list of all the papers uploaded on the application. The papers are listed with the title, authors' name, keywords of research topics and a view of the abstract of the paper.

On clicking the *View Paper* button (on each paper), you can see the full abstract of that paper, a link to download it and a section to provide your reviews on it. We have tried adding a rating feature that allows the uploader to rate how well the review was provided on that paper.

Another button, in the Navbar, on the user landing page is *Upload Paper*. Clicking on this button takes you to a form that allows you to upload your paper which needs to be peer reviewed.

There are two additional buttons on the user landing page: *My Papers* and *My Reviews*. The former shows a list of all the papers uploaded (and owned) by the current logged-in user, while the latter shows a list of reviews provided by the user for their peers. 


On the top right corner of the user landing page, the users can find a *View Profile* button which allows them to create a user profile wherein they can upload a profile picture and research topics they are interested in. This is a useful step as it will help curate the papers and authors/researchers with similar interests.
