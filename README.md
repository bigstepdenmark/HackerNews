# Requirements Analysis Document (Hacker News)

1. **Introduction**
	- A. Purpose of the system
	- B. Scope of the system
	- C. Objectives and success criteria of the project
	- D. Definitions, acronyms, and abbreviations
	- E. References
	- F. Overview

2. **Current system**

3. **Proposed system**
	- A. Overview
	- B. Functional requirements
	- C. Nonfunctional requirements
		- a. Usability
		- b. Reliability
		- c. Performance
		- d. Supportability
		- e. Implementation
		- f. Interface
		- g. Packaging
		- h. Legal

	- D. Systemmodels
		- a. Scenarios
		- b. Use case model

4. **Glossary**

---

### 1. Introduction
In this section we will try to establish the essentials, for the system and an lead-in to what some of the most fundamental functionality that has to be present in the system. 

##### A. Purpose of the system
To enable discussions and opinions for users by letting them create stories, which others may comment on, and if they choose to, up-vote/down-vote. 
Another important part of the system is users can use an API that we have build, to post a specific storie from their website, an again people will be able to comment on these specific stories.  

##### B. Scope of the system
The scope of the system is making sure that we have all the requirements done and implemented, and also to make sure that it is a clone of the current system. We will also need a database, for where there can be stored data. 

There will also be an API where a user can use the API to post whatever storie the user wants to post. A server is needed where the database and the API will be located, so the public can access it. 

We have an idea about, that there will an _buffer mechanism_ between our system and the simulator, the reason for that is if the system we have build goes down for some reason and there some sort of transaction going with some important data then that can be stored, and as soon as the system has the right state the transaction will be successful.

There will be no changes in the front-end/design, meaning that the design of the front-end will be exactly be the same as the current front-end. 

##### C. Objectives and success criteria of the project
__Objectives__&__Success Criteria__  -  is to develop a clear understanding at a high-level how functionality is performed in the current system (HackerNews). This also includes an understanding of the various use case scenarios and what functionality is required to complete each use case. “Leverage the information that is already available from HackerNews”. One very important objective is that team members are working together and, there is an continouous communication so that there is provided trust between developers, concerns to be addressed, and ideas to be discussed. 

A documented inventory of current requirements and functionality including non-functional requirements. It also important that there is an functioning team, where the level of productivity is high, therefore there are rolles giving to each member of the team and these roles has to be taken very seriously. The team work is a key factor to get the project up and running. 

Because of the tight scheduling and , we have made a team contract to ensure that everybody meets on time and every deadline is meet, if these team requirements are not respected there will consequences. In worst case scenario the individuel will be thrown out of the group.  

##### D. Definitions, acronyms, and abbreviations
*Mangler*

##### E. References
[Scope of the system](http://www.testablerequirements.com/testablerequirements/def_sys_scope_bound.htm)
[Hacker News](https://news.ycombinator.com)
[Usability](https://www.usability.gov/how-to-and-tools/methods/usability-testing.html)

##### F. Overview
*Mangler*

---

### 2. Current system
The current system enables registered users to perform a variety of actions.
* Post stories
* Comment on existing stories
* Up/down vote stories
																*Description of the current system*
Hacker News is a news forum, where you can publish and read stories from other websites. The stories and comments on Hacker News can only be published by registered users.
Registered users can also up and down vote stories on Hacker News, however it's required to have at least 500 Karma points before user can down-vote stories. Karma points is calculated using up-votes, which came from other users. All down-votes from users can be marked as SPAM.

As an additional service Hacker News also comes with an API, which gives users free read access.

---

### 3. Proposed system
The proposed system is an exact clone of the current, meaning that it is the exact same functionality and design.  

##### A. Overview
The proposed system provides the same functionality as the current system, with minor improvements such as design and usability.

##### B. Functional requirements
1. Register – People have an option to register themselves as users.
2. Post stories – Registered users have the option to post stories.
3. Comments – Allows registered users, to write comments on stories, and other’s comments.
4. Vote – Registered users may up-vote published stories and comments. Once 500 karma points have been accumulated, the user is allowed to down-vote content.
5. Karma points – Karma points are calculated as the number of up-votes a given user's content has received minus the number of down-votes.
6. Spam – Regardless of karma, all users have the option to flag submitted content as spam.
7. Front-end overview of number of comments.  
8. Front-end Overview of stories. 
9. Front-end who is the author of the story.
10. Front-end overview of the blog website.
11. Rest-API Service.
12. Job’s functionality in the nav-bar.
13. Ask’s functionality in the nav-bar.
14. Show’s functionality in the nav-bar.
15. Front-end, Amount of time a story has been online.
16. Front-end, Be able to show/hide a story.
17. Front-end, Ranking system of stories.
18. Buffering mechanism.


##### C. Nonfunctional requirements

###### a. Usability
The usability is more has to be more or less the same as the current system. Meaning that the button convention should be the same, and the responds time(in milliseconds) for the buttons should be the same, etc. _Usability testing_ would be an effeicient way to ensure that our system works as the current system. 

###### b. Reliability
We are ensuring that there is no data loss, if the system for some reason is down. We will plant an _buffer mechanism_, between the system and the simulator ensuring that there will not be any data loss.  

###### c. Performance
The system should be able to work under stress, meaning that there should not occur any problems if the amount of users is increasing rapidly. This can be tested using JMeter. When using the API, the users should be able post their blog to the system with a good load time.


###### d. Supportability
Users will use the REST-API

###### e. Implementation
*Mangler*

###### f. Interface
*Mangler*

###### g. Packaging
*Mangler*

###### h. Legal
*Mangler*


##### D. Systemmodels

###### a. Scenarios
*Mangler*

###### b. Use case model
![Use Case](systemmodels/usecase.png)