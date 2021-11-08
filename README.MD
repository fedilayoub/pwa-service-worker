# Progressive Web Apps - Complete Guide
-This source code is part of Maximilian Schwarzmüller's "Progressive Web Apps - Complete Guide" course on udemy.com.  
-In the first section of this course I learned how effective are PWAs as  **reliable**, **fast** and **engaging** apps that will help me enhance the performance of my web app no matter if it's and SPA or old legacy web pages.  
PWAs gather both the capability of native apps and the reach of web page which makes it a powerful choice when it comes to build a web app.
## Service Worker  
A service worker is one of the core building blocks that allows my app:  
-To get offline support;  
-Enables other PWA features;  
-Background synchronisation;  
-Have mobile like push notification.  
As shown below, even if I'm offline, sw.js file that represents our service worker(when registered),It allows our app to keep working when I refresh the page.  
![example of the sercice worker role](https://github.com/fedilayoub/pwa-service-worker/blob/main/service_worker.jpg)  
# How to Use
You need [Node.js](https://nodejs.org) installed on your machine. Simply download the installer from [nodejs.org](https://nodejs.org) and go through the installation steps.

Once Node.js is installed, open your command prompt or terminal and **navigate into this project folder**. There, run `npm install` to install all required dependencies.

Finally, run `npm start` to start the development server and visit [localhost:3000](http://localhost:3000) to see the running application.
