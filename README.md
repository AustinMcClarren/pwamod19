19 Progressive Web Applications (PWA) : Text Editor
License: MIT

Description
The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use. The integrated service worker and Cache API's ensure that the application will remain fully functional even without and active internet connection. This application allows the user to access visited pages even if the application is offline.

The URL of the GitHub repository is https://github.com/austinmcclarren/pwamod19.git

## Usage
``````    
GIVEN a completed text editor web application
WHEN I showcase the application in the video
THEN I should be able to explain all aspects of a PWA
WHEN I show the webpack plugins
THEN I explain how I have a generated HTML file, service worker, and a manifest file
WHEN I open the text editor
THEN I show that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I explain how the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I explain how the content in the text editor has been retrieved from our IndexedDB
WHEN I load my web application
THEN I should have, and can explain, the registered service worker using workbox
