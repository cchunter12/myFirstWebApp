# myFirstWebApp

This is a web application project I created in my second year of college as a Computer Science student.  The front end of this application uses HTML, CSS, Javascript, and Handlebars framework for a smooth web-browsing experience.  The back end of this application uses Linux, MySQL, NodeJS and Express JS.  

![thumbnailPRE](https://github.com/cchunter12/myFirstWebApp/assets/89422782/0a68b69d-8be5-47a2-8bf0-35743e686ad6)

# Disclaimer

"Please note that due to academic integrity concerns for the potential of plagiarism, I cannot publish the source code.  Please feel free to reach out to me if you would like to review the code associated with this project to ensure originality.  Thanks!"

# Front End

The front end composes of a main page, a login page, a sign-up page, an image upload page, and a sign-out page if the user is signed in.  I spent the least amount of time on this portion because I feel like the front end of a website can always be worked on later, but the functionality and core assignment of this project should be the main priority.  I did, however, convert the HTML files into Handlebars to allow easier, dynamic HTML codes.

*** Example of the front page ***
![page](https://github.com/cchunter12/myFirstWebApp/assets/89422782/bf127276-c3c1-47be-9706-4181836bd8a7)

*** HTML into Handlebars files ***
![sidebar](https://github.com/cchunter12/myFirstWebApp/assets/89422782/4586b6e0-f4f1-41dd-a9f0-c65ccc42b1cd)

# Back End

The back end allows me to run the website as a localhost application on my computer (or any other computer).  The back end works with the front end by receiving information received from user registeration, image uploads, and comments and store them into the database in MySQL.  I used middleware to connect these applications.

*** Example of middleware codes ***
![index JS](https://github.com/cchunter12/myFirstWebApp/assets/89422782/927803c7-db8e-4517-b929-f9f7313db9ef)

*** Example of receiving data from the front end ***
![comment in JS](https://github.com/cchunter12/myFirstWebApp/assets/89422782/900e8a6f-48a9-42aa-83fc-e80a842152b5)

*** Example of the MySQL schema that shows the connection between a user, the comments, and posts associated with that user ***
![schema](https://github.com/cchunter12/myFirstWebApp/assets/89422782/33456440-f7b9-4033-9f31-66235c562aa9)
