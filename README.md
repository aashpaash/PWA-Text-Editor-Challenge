# PWA-Text-Editor-Challenge

### Access Links
Deploy:
GitHub: https://github.com/aashpaash/PWA-Text-Editor-Challenge
## User Story
AS A developer <br>
I WANT to create notes or code snippets with or without an internet connection<br>
SO THAT I can reliably retrieve them for later use<br>

## Accptance Criteria
GIVEN a text editor web application<br>
WHEN I open my application in my editor
THEN I should see a client server folder structure<br>
WHEN I run `npm run start` from the root directory<br>
THEN I find that my application should start up the backend and serve the client<br>
WHEN I run the text editor application from my terminal<br>
THEN I find that my JavaScript files have been bundled using webpack<br>
WHEN I run my webpack plugins<br>
THEN I find that I have a generated HTML file, service worker, and a manifest file<br>
WHEN I use next-gen JavaScript in my application<br>
THEN I find that the text editor still functions in the browser without errors<br>
WHEN I open the text editor<br>
THEN I find that IndexedDB has immediately created a database storage<br>
WHEN I enter content and subsequently click off of the DOM window<br>
THEN I find that the content in the text editor has been saved with IndexedDB<br>
WHEN I reopen the text editor after closing it<br>
THEN I find that the content in the text editor has been retrieved from our IndexedDB<br>
WHEN I click on the Install button<br>
THEN I download my web application as an icon on my desktop<br>
WHEN I load my web application<br>
THEN I should have a registered service worker using workbox<br>
WHEN I register a service worker<br>
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets<br>
WHEN I deploy to Heroku<br>
THEN I should have proper build scripts for a webpack application<br>

## Cited Sources
### Code: 
Starter Code: https://github.com/coding-boot-camp/cautious-meme
Lesson 19-PWA Activities 


### Docs: 
mdn web docs_ : https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Add_to_home_screen <br>
web.dev : https://web.dev/learn/pwa/ <br>
webpack.js : https://webpack.js.org/