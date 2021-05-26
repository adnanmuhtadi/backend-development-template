<h1 align="center">(title of project)</h1>

[View project here](#)

(introduction of the site)

<h2 align="center"><img src="#"></h2>

## User Experience (UX)

### The Audience

The purpose of this site is to ...

### User Objectives



### My Objectives



### User Stories

The intended type of users which this website is targeted for are ...

1. As a user, I want to be able to ... so ...

### Design
-   #### Colour Scheme
    -   

-   #### Typography
    -   

-   #### Imagery
    -   

*   ### Wireframes

    #### Home Page
    
    
    #### Master Wireframes
    - Master Wireframes - [View](#)
    
#### Database Mapping

The database was designed using an online tool called [DB Diagram](https://dbdiagram.io/). The tables where mapped depending on the field requirements.

Database Design - [Mapping](#)

## Features

The features that will be utilised in this project will be as follows:

### Existing Features

#### Site Features

-   

### Features Left to Implement

-   

## Technologies Used

###  Programming Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - HTML5 was used to structure and present content on my website.
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - CSS3 was used to provide my website with style.
-   [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
    - JavaScript was used to make the site interactive.
-   [Python](https://en.wikipedia.org/wiki/Python_(programming_language))
    - Python was used as the backend language to access and parse data.

### Databases, Frameworks, Libraries, Programs and Templates Used

#### Databases
1. [DB Diagram](https://dbdiagram.io/)
    - Online tool to design the database.
1. [Mongodb:](https://www.mongodb.com/)
    - Database which stores the data to be recalled onto the website.

#### Frameworks
1. [Bootstrap:](https://getbootstrap.com)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [JQuery Core 3.6.0:](https://code.jquery.com/)
    - JQuery library was implemented to use features within Materialize
1. [EmailJS]()
    - Using emailJS service to send emails from the contact modal

#### Library
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome 5.13.3:](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [Hover 5.15.3](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css)
    - Hover effects used for the animation on hovering over links and buttons.

#### Programs
1. [Google Chrome:](https://www.google.co.uk/intl/en_uk/chrome/)
    - Default browser used to visually display the build process as well as utilising Chrome Dev Tools to assist where needed.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the code of the project after being pushed from GitPod.
1. [GitPod:](https://www.gitpod.io/)
    - A cloud development environment that allows us to create the website.
1. [Visual Studio Code](https://code.visualstudio.com/)
    - Code editing software was used to replace GitPod as the free license expired due to over 50 hours useage. 
1. [GitHub Desktop:](https://desktop.github.com/)
    - A tool that allows you to interact with GitHub from the desktop
1. [Grammerly:](https://app.grammarly.com/)
    - Online tool which assists with the English grammar.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](#) during the design process.
1. [RandomKeygen:](https://randomkeygen.com/)
    - A tool to randomly generate a password.
1. [Heroku:](https://www.heroku.com)
    - A platform as a service (PaaS) that enables me to deploy my website in the cloud.

#### Templates

1. [Github Template:](https://github.com/Code-Institute-Org/gitpod-full-template)
    - A template which has the preinstalled tools that will get us started.

## Testing

...

### Validation


On code completion, I ensured my code was validated with no snytax errors. I used [W3C Markup Validator](https://validator.w3.org/) for HTML5, [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) for CSS3 to ensure my code is W3C Compliant. I used [JSHint](https://jshint.com/) to helps to detect errors and potential problems in your JavaScript code. I also used [PEP8 Online](http://pep8online.com/) to validate my python scripts

#### Results

Page | Initial Errors | Resolved Errors | Error Notes
------------ | ------------- | ------------- | -------------
index.html| [Initial Errors](#) | [Resolved Errors](#) | ...

or use this template

#### HTML - [W3C Markup Validator](https://validator.w3.org/)

- 

#### CSS - [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - [Results](#)

- 

#### JS - [JSHint](https://jshint.com/) - [Results](#)

- 

#### Python - [PEP8 Online](http://pep8online.com/) - [Results](#)

- 

### Further Testing

#### User Stories Testing from User Experience (UX) Section - [View Results](#)



#### Functionality and Usability Testing - [View Results](#)



#### Browser and Responsive Testing



### Known Issues

- 

## Deployment

### Making a Deployment

The project was deployed to Heroku and connected to GitHub pages using the following method:
1. To direct Heroku which application and dependencies are required to run the app being developed, 
create a requirements file.
    - In the terminal, enter "pip3 freeze --local > requirements.txt"
1. Install the Procfile file as that what Heroku looks for to know which files run the app and how to.
    - In the terminal, enter echo web: python app.py>Procfile
    - Note:  In the Procfile, there could be a blank line automatically created, go into the file, remove the blank line and save it again.
1. In [Heroku Dashboard](https://dashboard.heroku.com/), click on 'New', then click on 'Create new app'.
1. Providing it with a unique name and changing the region to 'Europe' (or whatever region you are in). Then click on 'Create app'.
1. In 'Deployment method' click on 'GitHub', Ensuring your GitHub username is visible, either 
search for your repository or type in exactly how your repository is spelt in GitHub. 
When it finds your Repository, it will be visible and you would click on 'Connect'
1. Scroll to the top of the page and click on 'Settings'.
1. Scroll down till you are in 'Config Vars' section and since we hide the environment variables. It would need to be 
added into Heroku manually. You would need to add the following: IP, PORT, SECRET_KEY, MONGO_URI and MONGO_DBNAME, ensuring you putting the same values as you did in the env.py file
1. Going back to the terminal within GitPod. Commit and push the files that were created.
1. Once successfully pushed into GitHub, go back to Heroku and click on 'Enable Automatic 
Deployment' and then 'Deploy Branch'.
1. Once completed, a 'View' button would appear meaning the app has been deployed and successfully connected to Github.
1. As Heroku is now connected to Github, for the remaining for project, upload your files into GitHub and it would automatically sync with Heroku.

### Making a Clone

I had to get the SSH key from the repository which allowed me to clone the repository to my local hard drive. 
The method which I used to clone the project was via the terminal as well as Github Desktop. I was able to connect my Github repository and clone my files through this method. 

#### Step 1 - Method 1 (Steps taken in VSCode)
1. Open your IDE and open up the Terminal
1. Inside your terminal type `git clone git@github.com:adnanmuhtadi/milestone-project-3.git`
    - This would clone what is in github to your computer and so now modification to the files can happen on your local machine
1. Inside your terminal type `git status`
    - To see what changes have been made
1. Type `git -a`
    - To add all the files that you have worked on to the stage
1. Type `git commit -m "add notes here"`
    - To add a message to files you are about to push to the servers
1. Type `git push`
    - To upload to the remote repository

#### Step 1 - Method 2
1. Open the repository that needs to be cloned.
1. On the top-right side of the page, above the files, you will see a button 'Code' with an arrow point down.
1. Once clicked, a drop-down would appear which would give me the option 'Open with GitHub Desktop' 
(as I had already pre-installed [GitHub Desktop](#) previously).
1. Once clicked, it would automatically open the application and request where for it to be saved.

#### Step 2 - Create Env.py
1. Create a new file in the dictory called 'env.py'
    - In the terminal type in `git touch env.py`
1. Inside the env.py file you will need to add the following:
```
# Python env code to set all defaults

import os

os.environ.setdefault("IP", "0.0.0.0")
os.environ.setdefault("PORT", "5000")
os.environ.setdefault("SECRET_KEY", "yourkeyhere")
os.environ.setdefault("MONGO_URI", "yourmongouriaddress")
os.environ.setdefault("MONGO_DBNAME", "yourdatabasename")
```
3. Need to install the project requirements from the requirements.txt file.
    - In the terminal type in `pip3 install -r requirements.txt`
1. log into [MongoDB]() to create your database and the tables
    - Mapping of database available [Here]()
1. Within the app.py file, scroll to the bottom of the page and change the code from 
```
# This tells the application where and how to run.
if __name__ == "__main__":
    app.run(host=os.environ.get("IP"),
            port=int(os.environ.get("PORT")),
            debug=False)
``` 
To
```
# This tells the application where and how to run.
if __name__ == "__main__":
    app.run(host=os.environ.get("IP"),
            port=int(os.environ.get("PORT")),
            debug=True)
```
6. In the terminal, type in `python3 app.py` to run the application.

## Credits

### Content



### Code



### Media



### Acknowledgements

