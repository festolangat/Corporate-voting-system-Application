# Corporate-voting-system-Application
This is an application meant to facilitate choose of leadership in a small organization such as companies and organisation. It is a full functional application develop using PHP, JQuery for Mobile, HTML, CSS and Javascript. 

The application has several modal for users
1. Registration modal
2. Login Modal
3. Voting Modal
4. Results panel

Admin  manages users through
1. Add , remove and modify new candidate
2. Register voters
3. Add position 
etc

How the system work
1. Admin register voter by capturing some basic details such as Identification number and names
2. The system will generate a unique code that will be used by the voter when creating login details e.g VL03232223Rf
3. Voter will be using such unique code as their username e.g VL03232223Rf, 
4.Note: Without unique code voter will not be able to create password
5. Once the users is successful registered, He is uppose to login using unique code and password created
6. The system will check the voting time before proceeding to the voting panel. The default time sent is 18:00hrs Login.php, set the time convenient to you.
7. If the time is bellow 18:00hr the system will allow users to cast the vote else the system will reject as it will sense as voting is closed,
8. At the voting panel, user is required to select the candidate in a drop down menu,
9. Before submitting choices, voter is prompt to conform the choose, if it is wrong, presss cancel and start again.
10. By pressing submit, voter will be logout automatically and the session for voting expires.
11. Voters will not be able to vote once they have cast the vote, They can only login to view the results.
12. 

System Requirements
1. Xammpp/Wampp server
2. Browser: Firefox with latest pluggins
3. 
Consideration to make
1.  Remove localhoist password
2. create database name: onlinevoting
3. Transfer the files into htdocs folder for xampp or www folde for wampp


