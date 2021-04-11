# **MILESTONE PROJECT 3 - Task Manager** #

This is the third of four Milestone Projects required for the Full Stack Web Development course provided by Code Institute.

**For testing purposes, use the following login details:**

- login: RootUSER
- password: ROOTUSER234

## **UX** ##

### <ins>PROJECT GOALS</ins> ###

My main aim was to create an application that can be used within a workplace as a way to keep track of all tasks that need to be completed by a specific team or group of people. It allows the users to add and delete tasks, categorise them, mark them as complete, and add a due date and urgency setting.


### <ins>USER STORIES</ins> ###

- As a **user**, I want to be able to add new tasks to the database, edit them, categorise them, add a date due and urgency properties to the individual tasks, as well as have the ability to delete them once they are done.  
- As a **user**, I want to be able to log on and off the site after I have registered, in order to be able to add, delete and categorise tasks.
- As a **user**, I want to be able to see all tasks that are present in the database.
- As a **user**, I want to be able to search the database for certain tasks.
- As a **user**, I want the site navigation to be easy to use and intuitive. 
- As a **user**, I want the tasks to be displayed in a clear and organised way.
- As a **site owner**, I want the information on the site to be presented in a clear and easy to use way encouraging more **users** /workplaces to register on the site.

## **TECHNOLOGY USED** ##

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - used to create the site structure.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - used to create the styling throughout the site.
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - used for various funcionalities including the bottons and sign up.
- [jQuery](https://jquery.com/) - used to activate the Materialize functionality.
- [Python](https://www.python.org/) - used to write the logic that operates the site.
- [Flask](https://flask.palletsprojects.com/en/1.1.x/) - used to manage the HTML more efficiently through the use of templates.
- [Font-Awesome](https://fontawesome.com/icons?d=gallery) - icons were taken from this site.
- [Materialize](https://materializecss.com/) - used for responsive grid design.
- [Heroku](https://www.heroku.com/home) - used for hosting website.
- [MongoDB](https://www.mongodb.com/3) - used for database functionality.
- [Git](https://git-scm.com/) - version control and recording of all changes to site during development process.
- [Chrome Developer](https://developers.google.com/web/tools/chrome-devtools) - used to test responsiveness of site throughout the developmnent process.

## **TESTING** ##

- Chrome Developer Tools were used to test responsiveness of varous screen sizes.
- All links were tested to ensure they worked.
- NavBar was tested to ensure it worked.
- All CRUD functions were tested to ensure they worked.
- Used [W3C Validator](https://validator.w3.org/) and [W3C Validator CSS](https://jigsaw.w3.org/css-validator/) to ensure that HTML and CSS code was valid.
- Site and database was tested using Google Chrome web browser.
- further testing needs to be carried out including user testing to insure full functionality of the site.

## **DEPLOYMENT** ##

The site is hosted on [Heroku](https://milestone-3-larder.herokuapp.com/).

Deployment of the site was achieved by following the steps below (outlined in the CI Mini Project - Task Manager):

- Created a new repository within GitHub.
- Opened repository in my IDE of choice - Visual Studio Code - by cloning the repo from GitHub.
- Created a requirements.txt file by typing "pip3 freeze --local > requirements.txt" in the terminal which tells Heroku what dependencies are required.
- Created a Procfile for Heroku by typing "echo web: python app.py > Procfile" in the terminal.
- Checked the Procfile to make sure there is no extra line after the first line as this can confuse Heroku.
- Push the requirements.txt and Procfile to GitHub.
- Logged in to Heroku and selected "Create New App".
- Selected the input field "App Name" and gave app a unique name using dashes instead of spaces.
- Selected the region closest to my location and which was free to use!
- Clicked "Create App".
- Selected "Deploy" from the Heroku App menu.
- Selected "GitHub" from the "Deployment Method" section of the page.
- Ensured my GitHub profile name was showing in the "Connect to GitHub" section and inserted my GitHub repo name in the input field and clicked "Search".
- Once Heroku had found my repo, I clicked "Connect" to complete the link.
- Selected "Settings" from the Heroku App menu.
- Selected "Reveal Config Vars" and inputed the relevant key/value information from the my env.py (IP, PORT, MONGO_URI, MONGO_DBNAME, SECRET_KEY) file making sure that there were not quotation marks used.
- Selected "Deploy" from the Heroku App menu.
- Scrolled down the page and selected "Enable Automatic Deployment".
- Selected Master Branch under "Branch Selected".
- Clicked "Deploy Branch" - crossed my fingers and waited!
- Once site was deployed, clicked "View" to launch the app and be able to view it within the browser.

## **CREDITS** ##

- This project was created by following the tutorial for the mini project - Task Manager - within the web development course form Code Institute.

## **ACKNOWLEDGEMENTS** ##

Thank you to the following people:

- I would like to thank the Code Institute for giving me the skills, knowledge and resources to be able to carry out this project.