# Backend Challenge
## Introduction
Please complete the challenge below. Spend no longer than 4 hours and be prepared to discuss your logic and design decisions. You can use whichever language/framework you feel most comfortable with. Upon sending us your solution, please also include a short summary explaining the approach you have taken, why you think it's appropriate, any libraries or frameworks you have used, and how you might improve it if you had more time.

## The Challenge
Build a simple API service which exposes two endpoints to read and update a hotel resource. Your service should interface with a database of your choice. A hotel resource has the following shape:
```javascript
{
  "id": "xxxx-xxxx-xxxx-xxxx", //uuid
  "name": "The Grand Hotel",
  "contact": {
    "name": "Joe Bloggs",
    "position": "General Manager",
    "mobile": "+44 7658 475 807",
    "email": "joe@thegrandhotel.com"
  },
  "roomCount": 250,
  "enabled": true,
  "updatedAt": "2020-01-016T20:13:34Z",
  "createdAt": "2019-12-03T14:43:01Z"
}
```
## Bonus Step
Add a cache feature to your service to improve the speed of the API and reduce the number of unnessesary calls to the database.

## Things to think about
* Language/frameworks: Choose whatever language you will write your best code in. Please do not choose a language/technology that you are unfamiliar with.
* Testing: use whatever tools you prefer to test your code appropriately
* Try to implement appropriate separation of concerns & modular code
* Think hard about naming of functions and variables. Your code must be readable
* Code style & file structure is up to you, but make sure it is consistent and easy to understand

## Don't forget...
- [ ] Create a new repo. Please don't name your repo 'hotelflex' or anything similar (we don't want future candidates copying your code)
- [ ] Ensure all code is sufficiently tested
- [ ] Write brief summary on the approach you took, the tools you used, and how it could be improved with more time (max 500 words)
- [ ] Include instructions on how to build/ run your solution
- [ ] Send us a link to your new repo
