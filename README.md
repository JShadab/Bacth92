# Bacth92
https://teams.microsoft.com/dl/launcher/launcher.html?url=%2F_%23%2Fl%2Fmeetup-join%2F19%3Ameeting_YzVhMDFhNGItMjViMi00MzQ4LTlmODAtYThmYWE5MWExYjU4%40thread.v2%2F0%3Fcontext%3D%257b%2522Tid%2522%253a%252239d5b779-8b24-4e1d-b86d-94df66abc1e6%2522%252c%2522Oid%2522%253a%252203f5c4bd-912f-425d-87c5-df1cb52a189a%2522%257d%26anon%3Dtrue&type=meetup-join&deeplinkId=3291b756-1c1f-4c68-807c-e683b07e2845&directDl=true&msLaunch=true&enableMobilePage=true&suppressPrompt=true

Software Development models:
------------------------------
Water fall model
V-model
Agile
spiral
prototype 
Capability Maturity Model
iterative model
RAD model
----------------------------------------------
Water Fall Model:
====================
-> Classical life cycle and liner sequential model.
-> One of the oldest and is widely used.
-> Suggests a systematic sequential approach from the requirement analysis.

Phases of waterfall model:
---------------------------
1. Requirement Analysis:
	
--> The goals and containts of the system to be developed are estabilished in consultation with system users.
--> They are then defined in details and serve a System Specification

2. System and software design:

--> Partitions the requirements to either hardware or software.
--> Software design involves identification of necessary fundamentals of thw software requirement.

3. Implementation:

--> During this stage the whole of software components are integrated as a set of programs or programming unit.

4. Unit Testing:

--> Involves verifying that each unit meets its necessary requirement or specification.

5. Integration and System testing:

--> The individual program units  are integrated and tested as a one complete system 
     to ensure that all the necessary requirements have been met.

6. Operation and Maintance:

-> Longest life cycle phase
-> The system which has been delivered is put to the practicle use.
-> Involves correcting the encountered errors which ere not discovered at earlier stages
-> Also by enhancing the system as new requirements are discovered.

-> Requirement analysis(SRS) 
	-> Design(ER Diagram, DFD, Activity Diagram) 
		-> Implementation (FS, User story) 
			-> Testing (Test Cases) 
				-> Maintance
========================================================================
Advantage:
-----------
-> Easy to understand and implement
-> widely used and known
-> Reinforce good habit: define before design.
-> Identifies deliverables and milestone
-> Documents driven
-> Works well on  and weak teams.

Disadvantage:
--------------
-> Does not reflect iterative nature.
-> delays discovery of errors.
-> one phase has to be completed before moving to the next phase.
-> Difficult and expansive to make changes to document.

===================================================================================
when to use?
----------------
-> Requirements are very well known
-> product definition is stable.
-> New version of existing product.
-> Porting our product to new platforms.
------------------------------------------------------------------------------------
Prototype Model:
------------------
-> It is an effective  paradigm for software engineering.
-> Generally in this model, developers listen to the customer, design a prototype model and finally test it.
-> This is repeated until all requirements of system are identified.

Advantages:
---------------
-> Users are actively involved in the development.
-> Errors can be detected much earlier
-> Quicker user feedback is available.
-> Missing functionalities can be identified easily.

Drawbacks:
------------
-> Leads to implementing and then repairing way of building system.
-> Incomplete problem analysis.

When to use:
------------
-> requirements are unstable and have to be clarified
-> short-lived demonstration.
-> new original developed.

----------------------------------------------------
Iterative model:
------------------

Agile Model:
------------

----------------------------------------------------------------------------
Type of testing:
-----------------------

Unit testing -> Integration testing -> System Testing -> Acceptance testing.


Black Box Testing
White Box tetsing
Regression testing
Smoke testing
Alpha Testing
Beta Testing
System testing
Stress Testing
Performance Testing

-------------------------------------------------------------
User Story -> It is the documnent  prepared by the developer for tester.
--------------

Suppose as a developer I completed 3 task:
	1. Login fuctionality using email and password. (BMS-234) -> (BMS-234-userStory.docx)
	2. Post some data(product, medicine, service) from UI to DB.
	3. Getting data from DB and will display at UI side.

Now you want to release above task in QA environment.

For 3 tasks/functionalities we have to create 3 user stories.
--------------------------------------------------------------
Format:
===============

1. Story No.(provided by Jira) along with its description

2. Scenarios:
		a. scenario 1
		b. scenario 2
		----
		----
		---
3. Any negative scenario
	NA

4. Affected Module

5. Performance impact
	NA

====================================================================================
GIT commands:
--------------
1. Check git version	
	> git --version
	
2. To initiate a blank repository(local)
	> git init

3. To check the status of your repository
	> git status
	
4. How to add files from working directory to git repository
	> git add <fileName>
			OR
	> git add . (all new files in the working directory to Stagging area)

5. Commit the added files (stage rea to repository)
	> git commit -m "relavant message"

->  git config user.email "coolshad12@gmail.com"
->  git config user.name "Jshadab"

6. How to check all previous commits
	> git log OR > git log --oneline

===============================================================================
How to create a branch in git:
----------------------------------
$ git branch develop


How to list all branch names:
---------------------------------
$ git branch
  develop
* main

How to switch a branch:
---------------------------------
$ git checkout develop
Switched to branch 'develop'



