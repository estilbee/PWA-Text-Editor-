# PWA-Text-Editor-

## About the Project 
The PWA Text-Editor is a single page application that allows you to create notes or enter code snippets either online or offline. In the event that one of the options is not supported by the browser, the app uses data persistence techniques to ensure the data you have entered remains in the cache. It uses data storing and retreiving methods through a package called `idb`. When you first open the web application, you will find that the IndexedDB has immediately created a database storage. After entering some text, when you close and re-open the web application, you will notice that your content has been retrieved from our IndexedDB. When you click the `install!` button you will download the web application as an icon on your desktop, this is made possible through the webpack configuration.

## Project Preview
![Jate](/client/src/images/jate.png)

## Project Link
[PWA-Text-Editor](https://estilbee-text-editor-pwa.herokuapp.com/)

## Technologies Used 
- HTML
- CSS
- JavaScript
- Webpack
- IndexedDB
