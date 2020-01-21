# Software-Development
Requirement Specification For Crime Reporing Application


Android Crime Reporter and Missing Person Finder

LAKSHYA TRIPATHI		2GI17CS056
SUCHETA KULKARNI	2GI17CS054
ASHISH JOSHI	2GI17CS022







INTRODUCTION
This App allows user to file complaints or missing reports and keep a track of it. There are 3 categories that a user can file; Complaint, Crime Report and Missing Report and can see all the status of what action has been taken by the admin. To file any of the above 3 the user should register himself to the system and provide his right credentials to file them. The App also allows other user who doesn’t want to register but can check the crimes at his or any other area, just provide the pin code and in return the system displays the crimes if any filed. The offline i.e. the unregistered user can also take advantage of checking the missing persons but he is refrained from getting complaints done by the users. 

The Front End of the App is done using Android Studio and Firebase serves as a backend to store books lists and inventory data. The App has both the user as well the Admin Part, the role of admin is to just check all the 3 modules or categories and update their status likewise.
This App helps the user in tracking any report filed to the law and take an advantage of reporting any complaint from anywhere bringing the whole system online.

Software Requirements:
•	Windows XP, Windows 7(ultimate, enterprise) 
•	Android SDK

Hardware Components:
•	Hard Disk – 5 GB
•	Memory – 1GB RAM








 
FUNCTIONAL REQUIREMENTS:

1.	LOGIN AND LOGOUT
The citizens who wish to use the application will have to login into the app. If the user isn’t registered, then he can only view the Missing persons reported around his area but will not be able to file any report unless they are logged in.

2.	LODGE A FIR FOR LOST SIM
The citizen can file for a FIR for the lost sim cards and phone online through the application and the digital copy of the report will be shared between the user and the police.

3.	REGISTRATION OF COMPLAINT
Citizens can register their complaints with police and then based on the evidence, facts and 
following investigation, police shall take the complaint forward. The Registration module 
acts as an interface between the police and citizens and it eases the approach, interaction and information exchange between police and complainants.

4.	MISSISING PERSON REPORT
Citizens will be able to file report of missing person directly with the app along with several information like image of the missing person and personal information. The data will be shared with the relevant police station and the status will be updated.

5.	SEARCH
The Search module gives police personnel the ability to execute a basic or 
advanced search on cases. Using the search functionality, police personnel can search for a 
particular person, type of crime, modus operandi, property etc. It also gives the user the 
ability to customize the results view by criminal/accused or by cases. It makes reporting easy 
for police by enabling them to execute different types of queries such as monthly reporting, 
RTI related etc.

6.	FIND NEAREST POLICE STATION
The citizens will be able to locate the nearest police station from their location. Using a MAP and get the directions using third party API’s.

7.	SOS SIGNAL
The application will also have an emergency SOS option that the Citizens can send to the police authorities in case of a severe emergency.

8.	ADMIN LOGIN
Admin and the user have the same app, no different system.  The admin has to check the cases and update the status of that case;













NON FUNCTIONAL REQUIREMENTS

•	The non-functional requirements specify the qualitative attributes such as user-friendliness and performance of the system that are critical for the increased user-acceptance of the application.

1.	SYSTEM AVAILABLITY

a.	The System must be available to users: 
  i.	on <all weekdays/363 days per year>
  j.	from <00:00> to <23:45>;

b.	The planned downtime for the System must not exceed 15 hours per rolling three-month period. The System is considered to be down if any user is unable to perform any normal System function and if this failure is attributed to any component of the System other than the workstation.

c.	In the event of any software or hardware failure, it must be possible to restore the System (with inline synchronization) within no more than 03 hours.

2.	PERFORMANCE AND SCALABILITY

  a.	The System must provide adequate response times for commonly performed functions under both standard and peak conditions like SOS Functionality.

  b.	The System must be able to perform a simple search within 5-8 seconds and a advanced search (multiple search criteria) within 10-15 seconds regardless of the storage capacity or number of cases in the system. In this context, performing a search means returning a result list.  It does not include retrieving the records themselves.

3.	USABLITY

  a.	The user interfaces should be designed to make them user-intuitive.

  b.	Making navigation self-descriptive: Navigation should be designed to help users understand where they are, where they have been     and where they can go next
  c.	Minimizing navigation effort: The number of navigation steps needed to reach a certain piece of content should be minimized as     long as different mental models, navigation strategies and tasks of the user are taken into account.  

  d.	Minimizing user errors:  Potential user errors as well as the effort needed to recover from errors should be minimized.


  e.	Making user interfaces robust: User interfaces should be designed to be as robust as possible in the face of changing technology.   This encompasses being able to present content containing newer technologies by older user agents as well as designing content to be   usable with future technologies.

  f.	Text quality: The quality of textual content with respect to spelling and grammar should be sufficient so as not to impede         readability.


  g.	Linking back to the home page or landmark pages: Each page should contain a link leading to the home page of the application or     to a landmark page that is easy to recognize for the user.

4.	SECURITY

  a.	Database cannot be altered by any user apart from the administrator.

  b.	Privacy of the user should be maintained.




