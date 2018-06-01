# Image voting website
Sample appication that is using Google Go, VueJs and external APIs

# About:

A simple web app which shows pictures of funny cows and allows users to vote on the best pictures.
It contains a JSON API with 2 endpoints:
  - get a list of funny pictures and number of votes.
  - accept and count votes.
  
Number of votes is preserved between app restarts.
One user can vote one time on one picture.

# Technologies:

- Vue.js to handle frontend logic and communicate voting actionto the backend.
- Golang with JSON API service
- External image APIs:
   - Imgur https://apidocs.imgur.com/ 
   - Giphy https://developers.giphy.com/
