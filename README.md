# CiudadNuevaComensales
<img src="https://cdn.discordapp.com/attachments/738119984177479815/742530246020038728/CiudadNuevaComensalesEmpty.JPG" style="max-height:50px;">
Web app for a students cafeteria.
The students are able to find their name in a table and select and assign -all by themselves- different statuses for their meals and schedules during the week.

The cooks and the personel in charge of the kitchen can check a summary of the day's orders, who cancelled their food, who ordered may be a diet-type of food, among other different classes of "meal statuses"; as well as take a look at individual students orders throughout the week.

Anyone can add guests or invited person to eat and assign a status for their food.

Some admin users are the ones in charge of adding and removing users into the system.

Web app written in PHP using CodeIgniter Framework and MySQL for the backend. Front end built using Bootstrap and interactions with ajax using jQuery.

<img src="https://cdn.discordapp.com/attachments/738119984177479815/742547949405470811/CiudadNuevaComensalesWithRecords.JPG" style="max-height:50px;">

## Noone used the app on their PCs
First challenge that appeared was the fact that most of the people (I think literally I was the only one using the app from PC) was using the app from their phones.
They just wanted to open it real quick, let the principal know they'd be this day and this other day for diner and bye, app closed.
So we used Bootstrap magic to make the table responsive, making it smooth and easy to scroll horizontaly and verticaly.<br>
Letting people click on their name and opening a bigger, easier to tap modal was also a very celebrated feature.

## Then we had restrictions
Planning. The kitchen personal need to know with some time in advance how many people they need to prepare food for. Hense, restrictions were applied:
*Until what time are the students allowed to notify the app if they were (or not) having diner that day.
*Can they have their lunch to go? That's extra preparation so please notify one day in advance.
*Someone is coming later for lunch? No problem, but let us know in advance.
