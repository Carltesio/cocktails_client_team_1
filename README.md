# The Midcourse Project | Team 1
### Authors
[Carlos Delgado](https://github.com/Carltesio)

[Hunter Vitous](https://github.com/hmvitous)

[Kayla Woodbury](https://github.com/kaylawoodbury) 

[Daniel Bryant](https://github.com/DanielGITB)

[Janko Radakovic](https://github.com/MadFarmer101)

[Paulo Swärdblad](https://github.com/pauloswardblad) 
 
## Built with
**Front End:** React v. | CSS  
**Back End:** Ruby 2.5.1 | Rails 6.0.2 
**Testing framework:** Cypress  
**Deployed at:** [Netlify](https://tippler-team1.netlify.app/) and [Heroku](h).

[![Build Status](https://semaphoreci.com/api/v1/hmvitous/cocktails_client_team_1/branches/master/badge.svg)](https://semaphoreci.com/hmvitous/cocktails_client_team_1)
[![Netlify Status](https://api.netlify.com/api/v1/badges/d0d33ae2-8587-4130-9fe6-217c89a58cd5/deploy-status)](https://app.netlify.com/sites/cocktail-challenge-ca-t1/deploys)



## The code 
This Webapp allows you to search the ingredients needed for a cocktail and the different kind along with price in Systembolaget.
This project is part of a code learning experience where the core is to make use of at least one API where to fetch data from. For this project we made use of the cocktailDB api and Systembolaget. The former one gave us info on what ingredints and cocktails name, the second gives us the different options present in Systembolaget.

## Getting started
### Dependencies  
* Yarn
* React
* Cypress
* Axios

### Setup   
To test this application, fork the repo to your own GitHub account and clone it to your local workspace. </br>
*Note:*Be sure to set up backend api first (noted above), in order to fully interact with the application. 
Install all of the dependencies:    
```
$ yarn install
```  
Start cypress and run the feature tests:  
```
$ yarn run cy:open
```
Start the backend api (if already configured) in a separate terminal (only run this command for the Rails application):
```
$ rails s
```
Start the React application and run it on your local host:
```
$ yarn start
```

## Updates/Improvements   
- Improve UI to make it easier for visitors to use the webpage.

## License  
[MIT-license](https://en.wikipedia.org/wiki/MIT_License)

### Acknowledgement  
- Material provided by [Craft Academy](https://craftacademy.se)
- [Thomas Ochman]() for 

### Workflow Guidelines
 - PR Review: at the end of each day we will meet to review any PRs as a group that are ready for Thomas to review

 - Carousel of swtching: As we stitch partners and front/back, one person will stay while the other three shift and then they will shift next round that way there is always one person comfortable with what next step is needed with the front or back but we still will all eventually switch and work with every part with everyone in the group.

 - 20 min to research blocker, 10-15 with whole group, then pull in Thomas, do not be stuck on a blocker for more than an HOUR!!!

- When starting a new feature, take the time to make sure we are on the right branch, pull upstream to main branch, etc

- Ping group each time we push/pull and start new features

- Post morning scrum meeting, 5-10 min to make sure eveyone is clear on path for the day and to assign feature for the day

- Post lunch 5-10 min scrum

- Morning/Evening show and tell: where each coding group briefly walks through the code they added the previous/current day so that everyone know what all the code is doing and where to find each component.

- Ping group if uncertain about naming to help make sure front and back correlate

