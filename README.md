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

##### A. Purpose of the system
To enable discussions for users by letting them create stories, which others may comment on, and if they choose to, up-vote/down-vote.

##### B. Scope of the system
Scope of the system, the scope of the system is making sure that we have all the requirements done, and also to make sure that it is a clone of the current system. We will also need a database, for where we can store our data.

There will also be an API where a blogger can use our API to post whatever blog the blogger wants to post. A server is need where the database will be, and also our API so that an blogger can use it in the public.

We have an idea about, that there will an database between our system and the simulator, the reason for that is if the system we have build goes down for some reason and there some sort of transaction going with some important data then that can be stored, and as soon as the system has the right state the transaction will be successful.

##### C. Objectives and success criteria of the project
__Objectives__ -  is to develop a clear understanding at a high-level how functionality is performed in the current system (HackerNews). This also includes an understanding of the various use case scenarios and what functionality is required to complete each use case. “Leverage the information that is already available from HackerNews”. One very important objective is that team is working well together.

__Success Criteria__ - A documented inventory of current requirements and functionality including non-functional requirements. It also important that there is an functioning team, where the level of productivity is high, therefore there are rolles giving to each member of the team and these roles has to be taken very seriously. The team work is a key factor to get the project up and running.


##### D. Definitions, acronyms, and abbreviations
*Mangler*

##### E. References
*Mangler*

##### F. Overview
*Mangler*

---

### 2. Current system
The current system enables registered users to perform a variety of actions.
* Post stories
* Comment on existing stories
* Up/down vote stories

---

### 3. Proposed system

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
12. Jobs.
13. Ask’s.
14. Show’s.
15. Front-end Amount of time a story has been online.
16. Front-end Be able to show/hide a story.
17. Front-end Ranking system of stories.
18. Buffering mechanism.


##### C. Nonfunctional requirements

###### a. Usability

The button convention is important, the size should be the same size as the current system has.

1. It should be possible to accomplish any given task with just the keyboard, without the mouse, as the current system. 

2. The use of the API should be as the current system. 

3. All delays in the system longer than .5 seconds will produce a dialog box that says "Please wait."


###### b. Reliability
We are ensuring that there is no data loss, if the system for some reason is down. We will plant an extra database, between the system and the simulator ensuring that there will not be any data loss.


###### c. Performance
The system should be working under stress, meaning that there should not occur any problems if lot users using the system. This can be tested using JMeter. When using the API, the users should be able post their blog to the system with a good load time.


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
*Mangler*