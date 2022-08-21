# ID-Asg-2

Github link: https://github.com/ZacharyChong/ID-Asg-2
L4D2 tracker
Overview
This application is a game tracker that tracks players' statistics for a game called Left for Dead 2. One can use this application to check stats such as their total zombies killed, total number of hours played, and amount of achievements completed.They can also participate in a lucky draw in the application to win limited edition skins by simply filling in their name and contact details. When there are problems in the application, one can navigate to the 'Contact help and support' page and contact the help and support person to resolve any issues in the application. Our application essentially supports the LFD2 game and is targeted at the playerbase of this game. 

Design Process
This web application is targeted at the playerbase who plays the game. Generally, there is no tracker for the game and the playerbase wants to check their statistics of the game, so our web application fulfills that by providing stats that players want to see, and also provides a lucky draw system to encourage users to come back to the app to win prizes.

    User stories:
    - As a L4D2 gamer, I want to navigate to the stat page, so that I can check out my player stats when I play the game
    - As a user who loves lucky draws, I want to participate in a lucky draw, so that I can get free limited edition skins in the game
    - As a L4D2 enthusiast, I want to go to the stats page to find out how long I have played the game for

Features
    Existing features:
        - The navigation bar - allows users to navigate to different parts of the website, by having them click on the names of the different sections of the app 
        - Lucky draw contact form - allows users to participate in a lucky draw to help them win limited edition prizes, by having them fill in their name and contact information in the contact form.
        - Lucky draw table information of participants -  allows users to change their name and contact info if they have inputted it wrongly to ensure correct name and contact info, by having them click on the update button, change the contact information, and click the save button.

    Features Left to Implement:
        - The 'Contact help and support' page could have a message to the developers of the app from the web application by having a contact form as well instead of just a number and email of the person to use and contact
        - The web application could use a sign-in and Login function to register and Login users to the web application 
    
Technologies Used
- Html - The project uses html to show the website's outerior
- Css - The project uses css to style the html so that it looks nicer
- Javascript - The project uses javascript to use the RestApi for the contact form and table information of participants for users to participate in the lucky draw
- AJAX - The project uses AJAX to communicate with the restdb server and send and receive users' personal information

Testing
1. Contact form:
    Go to the "Contact Us" page
        - Try to submit the empty form and verify that an error message appears
        - Try to submit the form with an invalid email address and verify that an error appears
        - Try to submit the form with all inputs valid and verify that a success message appears.

2. Navigation bar
    Go to the navigation bar
        - Try to navigate to the home page and it should bring users there
        - Try to navigate to the stats page and it should bring users there
        - Try to navigate to the lucky draw page and it should bring users there
        - Try to navigate to the Help and Support page and it should bring users there

3. Table information of Participants
    Go to the Table information of Participants
        - Try to update the information of participants and verify that it has been updated
        - Try to delete information and verify that it has been deleted
    
    Bugs
    -  The delete button navigates to the home page instead of deleting the information

Credits
    Media:
        - Circle image - https://www.freevector.com/vector-circle
        - Bar graph icon - https://icons-for-free.com/STATISTICS-131994911363180250/
        - Menu button - https://www.pinterest.com/pin/create/button/?url=https%3A%2F%2Fpngtree.com%2Ffreepng%2Flist-vector-icon_4236974.html?share=3&media=https://png.pngtree.com/png-vector/20190420/ourmid/pngtree-list-vector-icon-png-image_963980.jpg&description=list+icons%2Cchecklist%2Cdo%2Cfile%2Clist%2Cmenu%2Ctext%2Cchecklist+icon%2Cdo+icon%2Cfile+icon%2Clist+icon%2Cmenu+icon%2Ctext+icon%2Cicon%2Cvector%2Cillustration%2Cdesign%2Csign%2Csymbol%2Cgraphic%2Cline%2Clinear%2Coutline%2Cflat%2Cglyph%2Ccircle%2Cshadow%2Clow+poly%2Cpolygonal%2Csquare%2Cline+vector%2Ccircle+vector%2Cgraphic+vector%2Csquare+vector%2Cmenu+vector%2Csign+vector%2Ctext+vector%2Clist+vector%2Cchecklist+vector%2Csymbol+vector%2Cicon+vector+png%2Cshadow+vector
        - Home background image - https://wallpapertops.com/walls/left-4-dead-2-wallpapers
