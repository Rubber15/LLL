# Portfolio Semester 3 Software
**Reading guide:**
My Portfolio for Semester 3 is devided into the learning outcomes. Every chapter will go through all the outcomes. First I'll simply state all the outcomes, next how I will achieve those outcomes and last what i did to achieve them. 
## Table of contents
   - [What are the Learning Outcomes](#what-are-the-learning-outcomes)
      	- [LO 1: You design and build **user-friendly**, **full-stack** web applications.](#lo-1:-you-design-and-build-user-friendly-full-stack-web-applications)
      	- LO 2: You use software **tooling and methodology** that continuously monitors and improve the software quality during software developement.
      	- LO 3: You **choose** and implement the most suitable software developement method for your software project. 
      	- LO 4: You **design and implement** a (semi)automated software release process that matches the need of the project context. 
      	- LO 5: You **recognize** and **take into account** cultural differences between project stakeholders and ethical aspects in software development.
      	- LO 6: You analyze (non-functional) requirements, elaborate (architectural) designs and validate them using **multiple types of test techniques**.
      	- LO 7: You analyze and describe **simple** business processes that are **related** to your project.
      	- LO 8: You act in a **professional manner** during software development and learning.
 - [How will I achieve the Learning Outcomes](#how-will-i-achieve-the-learning-outcomes)
	 - LO 1: Designing and building the LLL. 
	 - LO 2: Which software tooling and methodology is best for the LLL?
	 - LO 3: What is the most suitable software development method for the LLL or the group project?
	 - LO 4: What tool is the best for the LLL to make sure it is (semi)automated released?
	 - LO 5: How are the cultural differences addressed and taken into account in the group prject?
	 - LO 6: Which non functional requirements can be assigned to the LLL?
	 - LO 7: What is the buisiness process for the group project?
	 - Lo 8: Why is professional communication so different from communication between friends(research)?
  -[Proof] 
	  - The LLL
	-Introduction
			"The problem that the LLL solves is that when playing lore heavy games with friends, gameplay has to be interrupted to ask questions. This causes stagnation in gameplay and has everybody lose their immersion. 
			My solution to this problem in THE LEGEND LORE LIBRARY. This will serve as a desktop web app in which you can look up answers to your questions regarding lore. A game leader puts the information somebody needs into the app.
			Only a game leader can do this so that all information is relevant and is written in a way their players can understand. 
		-Designs
		-Requirements
			To get a clear view of what requirements are needed, I started with user stories. 
			As a game master, I want to create and share lore with my players before the game starts, so they can understand and get immersed in the world right away.
			As a player, I want to be able to access the lore of the game world easily during gameplay, so I don't have to interrupt the flow of the game to ask questions.
			As a game master, I want to be able to update the lore and worldbuilding information easily, so I can keep my players informed of any changes or additions to the game world.
			As a new player, I want to be able to learn about the game world quickly and easily, so I can start playing and contributing to the story right away.
			As a player, I want to be able to search and filter the lore information, so I can find the information I need quickly and efficiently during a game.
			As a game master, I want to be able to assign specific lore information to different players, so they can have personalized knowledge about the game world and its history.
			As a player, I want to be able to add my own private notes and comments to the lore information, so I can remember important details and contribute to the game world's development.
			These were somewhat written by ChatGPT and then modified by me. Following these user stories as a guideline, i can extrapolate the following requirements. 
			Scalability:
				The app should be to handle a growing userbase and stored information without sacrificing preformance. 
				The webapp has to support horizontal scaling to accomodate increased user load.
			Preformance: 
				The app must have a fast response time to ensure smooth user experience.
			Availability:
				The app should only be down when an update is implemented. 
				The system could have backup and disaster recovery mechanisms.
			Reliability:
				The webapp should have error handling and logging mechanisms for debugging
			Usability:
				The user interface of the app should be intuitive and simple allowing users to easily navigate and get familliar with the app. 
				The app can have search and filter options to quickly find specific data. 
				The search options can be flexible (keywords, categories, tags, etc.)
				The app can be user friendly for mobile users.
	  - Azure (CI/CD)	
	  - The Group Project (Groopy Swoopy)
		-API
		-Azure
		-Cultural differences
		-Business Process
	  - Research in Communication
		-Why is professional communication so different than "friendly" communication?
	  - Research in Cultural Differences
		-How is autonomy and the feeling of community balanced in Finland as compared to The Netherlands?
		

# What are the learning outcomes?
The learning outcomes are 8 statements that you need to complete to succefully pass this semester. In S3 software, it are the following 8:

## LO 1: You design and build user-friendly, full-stack web applications.
LO1 asks to make a full stack web app keeping the user experience in mind. Full stack means that you build the frontend and the backend yourself. The frontend needs to be in a javascript based framework and the backend needs to have relevant communication protocols and needs to address asynchronous communication issues. 

## LO 2: You use software **tooling and methodology** that continuously monitors and improve the software quality during software developement.
This LO calls for the CI part of CI/CD, meaning continuous integration. There are multiple providers to do this; azure, GitHub actions, docker, Jenkins to name a few. This make sure that every time you finish a new part of your code, that it will be checked against tests and specifications you set up. It prevents that unfinished or broken code ends up at the actual online server.  

## LO 3: You **choose** and implement the most suitable software developement method for your software project. 
This learning outcome calls for Scrum. This is easiest to show in the group project and seems interconnected with LO8. 

## LO 4: You **design and implement** a (semi)automated software release process that matches the need of the project context. 
LO3 sets the requirement of using and implementing the CD part of CI/CD, meaning continuous delivery. There are multiple options to do this but they all, some way or another, place your app on a webserver. When there is a part of code finished, it will automatically make it available to see online. 

## LO 5: You **recognize** and **take into account** cultural differences between project stakeholders and ethical aspects in software development.
Here the LO asks us to think about other cultures and take those into account when communicating. The question of ethics is also raised, not all code should be made. 

## LO 6: You analyze (non-functional) requirements, elaborate (architectural) designs and validate them using **multiple types of test techniques**.
Not only Unit tests and acceptation tests need to be done. User testing is also important and should be done in the project. That is what LO6 asks for

## LO 7: You analyze and describe **simple** business processes that are **related** to your project.
Alle the processes that need to be done to get your program into the real world should be thought about and described. 

## LO 8: You act in a **professional manner** during software development and learning.
This LO wants to convey the professionalism of working an actual job. Asking feedback often, being in class, communicating professionally. 


# How will i achieve the Learning Outcomes?
I am making the Legend Lore Library. It has some key similarities with World Anvil. it will serve as a place where you can store and show information about a game. As a group project we have made Groopy Swoopy. This project was made by a collaboration with Finland. Our dutch group went to Finland (Oulu) for a week at the start of the semester and they came here for a week at the end.

## LO 1: Designing and building the LLL. 
To make the webapp user friendly, my first step is using azure AD for signing in. This makes it so that the user doesn’t need a new username and password to log in, but instead can log in with an existing Microsoft account. 	
The Full stack part I need some help with. 

I want to use a Javascript framework and decided to use React. I have done some research on which framework fits my needs the best. I came to the conclusion that there are a lot of options. Angular is the best rated but mostly used for one page apps, something I am not planning on doing. There is Vue3, which seems great on the surface but is very difficult to learn when you have no experience with frontend development. I chose to use React. There is a lot of guides available and heard about it a lot. 

## LO 2: Which software tooling and methodology is best for the LLL?
For this Learning Outcome I will make changes to my .yml file. The changes I want to make are rules that the application does not build and deploy when not all the Unit and system tests are completed. This will (hopefully) prevent that a version of the app that works locally but not globally ends up being deployed. 

## LO 3: What is the most suitable software development method for the LLL or the group project?
For my own project i think scrum would seem like wasted potential. Scrum is widely used in group projects because it is good at making sure a group works best. Using Scrum in an individual project will cost more effort than it will offer help. However, for the group project we are using Scrum because of those advantages. 

## LO 4: What tool is the best for the LLL to make sure it is (semi)automated released?
To achieve this outcome I am going to use the App Service from Azure. This fabricates a .yml file to initiate Github Actions. Every time I push to the main branch or merge with it, it will run tests and check if there are any errors. If all the conditions are met, it will go through all the steps needed to build and publish my project to an azure web service. I chose Azure here because it seems like a service that can be very useful for all sorts of thing. It however has a very steep learning curve. In this semester I have time and space to try some of its features out and start getting slightly proficient with Azure, hence my choice. 

## LO 5: How are the cultural differences addressed and taken into account in the group prject?


- LO 6: Which non functional requirements can be assigned to the LLL?
- LO 7: What is the buisiness process for the group project?
- Lo 8: Why is professional communication so different from communication between friends(research)?

