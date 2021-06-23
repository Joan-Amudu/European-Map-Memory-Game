# DUNIA

The deployed site can be found [here](https://joan-amudu.github.io/Dunia-Memory-Game/)

# Table of Content
[General Information](#general-information)

[How to Play](#how-to-play)

[User Experience](#user-experience)

[Features](#features)

[Technologies](#technologies)

[Testing](#testing)

[Deployment](#deployment)

[Credits](#credits)

[Acknowledgements](#acknowledgements)

# General Information
## About
Dunia in Kiswahili means - The World. This memory game will be based on the world map and is inspired by my love for travel.

The game is based on matching flags of european countries. 
## How to Play
* To play, simply click on a card to reveal the flag and find a match. Once the user matches 2 identical flags, 1 point is scored. 
* To win the game, simple match all 12 flags.
* To play again, click on the Restart Game button and the card deck will be shuffled.

#### [Back to top](<#table-of-content>)

# User Experience 
This section highlights the user experience, design, fonts and color scheme used to provide a seemless user experience.

## User Stories
* As a player I want to quickly know what the game is about.
* As a player, I want instructions on how to play the game, so that I know what to expect.
* As a player I want to go through different levels of the game.
* As a player I want to see my progress through a scoreboard.
* As a player, I want to be able to mute/unmute any sounds


## Design 
The webiste's design and layout is based on fonts, colors, wireframes, images and icons.

### Fonts
* [Google Fonts](https://fonts.google.com/) was imported to CSS with the Mate SC font family being the main font for the body and playfair font for the paragraphs.

### Color Scheme

This color palette was inspired and generated from the backface image of the cards.
* **#B25823 (Desert):** Used for the < hr > HTML element. 
* **#10273D (Elephant):** Used for socila media icons and paragraph text.
* **#ECD223 (Golden Dream):** Used for the Brand name, About button and overlay texts.
* **#5495B2 (Hippie Blue):** Used as the background color.

![Color Scheme](assets/images/colorPalette.png)

### Wireframes
* Wireframes were created using the [Balsamiq](https://balsamiq.com/wireframes/) software.

* A pdf of the wireframes can be found [here](/Assets/Wireframes/Dunia-Memory-Game.pdf). This file can also be downloaded from Github. (**Please Note:** _[Adobe Acrobat Reader](https://get.adobe.com/reader/) is required to view files in pdf format_).

#### [Back to top](<#table-of-content>)

# Features
The website incorparates a navigation bar with a brand name and a button as a menu item on the left. 

It aslo consists of a landing page with over-lay text which are fully responsive.

### **Existing Features**

Included in the **Landing** page is:

* **An ovelay text - Click to start:** This prompts the player to click and start the game. Clicking the overlay text alos reveals the Nav bar with the Brand Name and About Modal button and the card deck with scoreboard 

* **Navigation Bar:** Fully responsive navbar will expand outside of smaller devices and overall provides a user friendly and intuitive browsing experience.

* **About Button** : This is a Modal with right-aligned social media icons (Facebook, GitHub, LinkedIn). These icons are links to the respective social media pages and will open in a new tab to maintain user retention.
The **Modal** also has content about the game and how to play it.


### **Nice to have Features**
These are features that would have been hice to have as they would have an added value for the player. These features will aslo be implemented in the future.

* **A timer**: This timer wouls start counting when the user clicks the first card when starting the game. In addition, a **Count-down timer**, where the time is predefined for the user and the user either wins the game within that set time or will lose and a **game-over** overlay text will be displayed.
* **Timer controls**: To give the player more control, the timer would have an on/off functionality, allowing them to choose to play a timed game or a more relaxed game without the timer counting down, thus allowing them to get more familiar with the game and give them higher chances of winning.
* **Difficulty levels**: This would include easy, medium and hard levels of difficulty.
* **Additional Music**: This would include a game-over music, and would apply when the **Count-down timer** is chosen. The **game-over** music will be activated when the **Count-down timer** has ended indicating that the player has lost the game.
To add to the user experience, a joyful **Victory** music when the player has won the game, along with the accompanying overlay text. 

#### [Back to top](<#table-of-content>)  
 
# Technologies
This project is created with:
* HTML5 - used for building the website.
* CSS3 - for styling elements.
* JacaScript - used to make the web page more interactive.
* Google Fonts - Mate Sc and Playfair.
* Bootstrap - to customise the site as a responsive mobile-first site.
* Font Awesome - for Icons.
* Balsamic - to creation of the Wireframes.
* GitHub - Used for hosting the code and version control.
* GitHub Pages - This is where the site is deployed.

#### [Back to top](<#table-of-content>)

# Testing 

## Functional Testing

The testing below is identical on all pages.
Test Label | Action | Expected Result | Pass/Fail 
---------------|---------------|---------------|---------------
Label1 |Test Case 1| N/A | Fail
Label1 |Test Case 1| N/A | Fail
Label1 |Test Case 1| N/A | Fail
Label1 |Test Case 1| N/A | Fail
||


#### [Back to top](<#table-of-content>)



## Brower Compatitbility
This will be tested on the following browsers:
  - Google Chrome
  - Microsoft Edge
  - Firefox
  - Safari
  
## Responsiveness
The site was tested on different screen sizes with special attention to very small screens e.g. iPhone 5 and very large screens e.g. 5K iMac Pro (5120 x 2880 px).


## Testing User stories
* As a player I want to quickly know what the game is about.
* As a player, I want instructions on how to play the game, so that I know what to expect.
* As a player I want to go through different levels of the game.
* As a player I want to see my progress through a scoreboard.
* As a player, I want to be able to mute/unmute any sounds

## Validators
HTML Code must pass through the **[W3C HTML Validator](https://validator.w3.org/ "W3C HTML Validator")**.

CSS Code must pass through the **[W3C CSS Validator](https://jigsaw.w3.org/css-validator/ "W3C CSS Validator")**.

- [HTML Validator](https://validator.w3.org/) .
- [CSS Validator](https://jigsaw.w3.org/css-validator/) .

## Lighhouse Report  
### Mobile
![lighthouse report mobile](assets/images/DuniaMobile.png)


### Desktop
![lighthouse report desktop](assets/images/DuniaDesktop.png)
#### [Back to top](<#table-of-content>)

# Deployment
This website was created in gitpod, which is linked to Github. All changes were commited and pushed to Github.

## GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Joan-Amudu/Dunia-Memory-Game).
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. Click save.
6. The page will automatically publish to GitHub pages. 
7. Scroll back down through the page to locate the now published site [link](https://joan-amudu.github.io/Dunia-Memory-Game/) in the "GitHub Pages" section.

### Forking
To fork this respository:

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/).
2. Under the repository name, click Code.
3. To clone the repository, select HTTPS and copy the link.
4. Open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type **git clone**, and then paste the URL you copied in Step 3.

```
 git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
    * To clone this particular repository:
    git clone https://github.com/Joan-Amudu/Dunia-Memory-Game.git

7. Press Enter. Your local clone will be created.
8. Change into the directory being created.
9. Clicking index.html, opens the site in a browser.

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) for more information about cloning repositories.

#### [Back to top](<#table-of-content>)

# Credits
Below are the resources that were used to create this website.
## Code
Javascript code and structure inspired by [Ania Kubrow](https://youtu.be/tjyDOHzKN0w) and [Port Exe](https://youtu.be/3uuQ3g92oPQ)

JavaScript Audio Controls code snippet from [Adam Khoury.](https://youtu.be/hsSXzdn_0Gg)







## Images
Back face Image on cards by James Lee: [Pexels](https://www.pexels.com/photo/close-up-photo-of-feathers-2625664/).


## Inspirations

* [Bootstrap](https://getbootstrap.com/docs/4.3/getting-started/introduction/), a popular front-end open source toolkit has been used for the columns, rows, buttons and form.
* [Font Awesome](https://fontawesome.com/) was used for the social media icons. Here, the free icons were selected and styled to match the overall color-scheme of the website. 

* [Pexels](https://www.pexels.com/) - Used for free stock.
    - [cottonbro](https://www.pexels.com/@cottonbro)
    


[codepen](https://codepen.io/Fako29/pen/ZEOjyBV) solutuion to doucle clicking card: 
original code - line 98: 
if (cardsSelected[0] === cardsSelected[1] && firstCard !== secondCard) { 


## Other resources
* [w3schools.com](https://www.w3schools.com/default.asp): used for a deeper understanding of HTML and CSS.
* [StackOverflow](https://stackoverflow.com/): Used for troubleshooting. 

* Code Institute course modules.
#### [Back to top](<#table-of-content>)
# Acknowledgements
I would like to acknowledgement my mentor Brian Macharia who guided me throughout the project.

#### [Back to top](<#table-of-content>)