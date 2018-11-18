# gift-the-code-2018
## Working on Gift the Code for the Movember Foundation. 


MO COINS DESCRIPTION:
- We are creating a loyalty-currency called "mo' coins" that people can earn through using our chrome extension & participating in activities which promote Movember, as well as through purchasing goods or services on Movember partner sites.
- Mo' Coins can be used to redeem for Mo swag (as well as other redemption opportunities in the future)


### Movember Chrome Extension:
---------------------------------
Link: https://github.com/thesillypeanut/gift-mocoins-chrome-extension

Description: 
- The main idea of this extension is to prompt an online shopper to top off their order to the nearest dollar ($99.90 -> $100).
- The difference can be either donated to the movember foundation or converted into mo' coins.
- The extension will also show facts about the movember movement, goals, different charities and more facts about men's mental health.
- This will increase the donations and the awareness of movember being more than just a month where people don't shave.
- Inspired by the Honey chrome extension

### Movember App-Engine:
Link: https://github.com/kristian-ott/gift-the-code-2018

Description: 
- We made a temporary app engine that we set up to access our SQL database, where data can be accessed using REST API.
- The app engine sets up the different endpoints and returns our database's information.

Examples API calls:

POST http://gift-the-code-api.appspot.com/members/
{
  "email": <email>,
  "firstName": <firstName>,
  "lastName": <lastName>,
}

GET http://gift-the-code-api.appspot.com/members/<member_id>


POST http://gift-the-code-api.appspot.com/postings/
{
  "email": <email>,
  "mopoints": <points>,
  "type": <credit or debit>,
}

GET http://gift-the-code-api.appspot.com/postings/<posting_id>


### Movember Presentation Resources:
Link: https://github.com/kayalash/kayalash.github.io


Move for movember - link to: https://ca.movember.com/get-involved/move
Host a mo-ment - https://ca.movember.com/get-involved/host
Make a donation - https://ca.movember.com/get-involved/donate
Complete a movember challenge - https://ca.movember.com/get-involved/network-challenges
Attend a event - https://ca.movember.com/events
