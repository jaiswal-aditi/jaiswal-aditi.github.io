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

This is putting everything we learned this semester, in a group project, the final step before we go out in the real world of software engineering. 
[Peer Review Finder](https://peer-review-finder.xyz/#/) is a web application which brings researchers together by allowing them to upload their research
papers to get peer reviews before publishing them in journals and conferences and also review other researcher's papers. 

### User Interface 

On retrieving the application, the user should be able to see a brief introduction of the application system, the current total numbers of papers available on the platform along with the count of number of authors and total topics. In the current state of the project, the users can update their profile indicating their research interests, upload their research papers, view the reveiews they got on those papers. The appli cation also displays if there are new papers being uploaded on the platform which matches their interest. The top-left *View Paper* button in the Navbar takes the users to a page where they can see a list of all the papers uploaded on the application, by other researchers. The papers are listed with the title, authors' name, keywords of research topics and a view of the abstract of the paper.

On clicking the *View Paper* button (on each paper), you can see the full abstract of that paper, a link to download it and a section to leave their reviews on it. These reviews can be seen by the user who posted that review and also the author who uploaded the paper. We have also tried adding a rating feature that allows the uploader to rate how well the review was provided on that paper. This rating feature is the foundation of the token system, a characteristic which prompts users to remain active on the site, and improves the research process by allowing the users to read and review other papers first before uploading their paper. This is an important step because journal editors and conference chairs find it increasingly difficult to find reviewers for publication manuscripts

There are two additional buttons on the user landing page: *My Papers* and *My Reviews*. The former shows a list of all the papers uploaded (and owned) by the current logged-in user, while the latter shows a list of reviews provided by the user for their peers. 


On the top right corner of the user landing page, the users can find a *View Profile* button which allows them to create a user profile wherein they can upload a profile picture and research topics they are interested in. This is a useful step as it will help curate the papers and authors/researchers with similar interests.
