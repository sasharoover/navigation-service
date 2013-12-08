#1.Title - "requirements of the system MyWay1.0" 
* Team name: MyWay1.0
* Team members:listed below 

        
	* Jeremy Kyejo
	* Bilen Gerawork
	* Masinde Masinde
	* Zelalem Aragie
	* Aleksandr Tikachev
        
        
#2. Introduction 
 
The project is mainly a real time navigation  system application that helps users to find a specific locations indoor and outdoor unlike GPS satellite navigation; which is outdoor. The idea is using the internet from phone and also WIFI. There is also a cool voice function for blind people. There are other functionalities and features as well.These features are email and event notifications, schedule, newsfeed and games. Those features are also interesting from the market perspective.

 
#3. Use cases 
##User Groups
* Student
* Teacher
* Staff
* Guest
* Generic User

##Use case diagram and Description
![myflowchart](http://users.metropolia.fi/~jeremyk/SoftEng/usecasedia.JPG)

##Use case scenarios (based on template)
1. Open the phone
2. Open the app
3. Sign in as Guest or with account
3. Choose navigation
2. Choose your destination
3. Internet could fail, use internal GPS(for out door) and or use history offline mode (indoor)
4. E-mail,alarm and other settings they will come according to the significance and timing of course.
5. Generic user has reached the destination

##Depiction of one use case as a flowchart
![myflowchart](http://users.metropolia.fi/~jeremyk/fl.JPG)

#4.System architecture
##4.1 High-level overview of the system
Kana2.0 is a navigation app with more interesting features. The database is consisted of the whole school map. The app runs using the WIFI to detect the position of the user. It is an indoor GPS system.
###4.2 Main modules and their functions represented
![myflowchart](http://users.metropolia.fi/~bileng/SoftEng/hl.JPG)
The main modules and functions of this indoor navigation app could be seen as follows:-
* Positioning service – this is the main functionality of the app. It provides information how to get the shortest path of a definite location and it checks also the crowd. After all, it will provide the most preferable way. And according to significance the app continues working. The voice command is also inside this service but it is considered as a different feature. 
* The information service – This functionality is the next important service the app provides to the user. It simply notifies the most important notifications like e-mails, news feed, events, and schedule; for example in case of next class and deadline reminder and games.
* Authentication service – This is the single sign in based for the user safety.
* Database - Simply thee schools map and news feed from tuubi.
* General view – Is the about the path and the picture view that appears in the app. Its functionality is more likely straight forward. At the main page there is simple search destination bar which have a submit button next to it. And 


#5. Requirements (in traceable (and measurable) format) - Sasha
##Functional requirements
##Non-functional system requirements
Usability: how do you ensure that your system is easy to use?
Reliability: how do you ensure that your system is reliable? List the possible system failures and how the system reacts to them
Efficiency: there are multiple people using your system. How do ensure that the system is efficient enough? What metrics would you use?
What other non-functional requirements should be documented?
What kind of metrics you should use to guarantee unambiguity?
 
#6. User interface - 
##The views / components of the system and The functionalities of each view

#User Interface

#1. login view
  * Username
  * Password
  * login button

#2. Menu 
 * navigation 
 * Schedule 
 * notification 
 * Events 
 * Voice guide 
 * news
 * Back 
 * Logout

#7. Project management, self reflection
#Working hours
       * Aleksandr Tikachev : 25 hours
       * Jeremy Kyejo :36 hours
       * Bilen Gerawork : 30 hours
       * Masinde Masinde : 25 hours
       * Zelalem Aragie :25 hours
 * It was difficult because in real work situation there is a person whose job is to right down the hours for you and moreover the person also notes down these working hours from start.
 *  We would take more time off from school (other courses) to concentrate on this kind of project.
 * We would definetly buy this product. Who wouldn't 
enjoy and have fun with this navigation service? the answer to that of course noone.
 * The most difficult part would be the requirements (functional and 
non functional) and system architecture.
