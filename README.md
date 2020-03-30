# Starter-Kit-Gulp

Built to speed up the process of web development with Gulp setup. Font-awesome v5.13.0 is included in the package. You may remove it if it is not being used in your project. 

**Steps**
---------

 **Install Node**
	https://nodejs.org/en/

 **Install all the node packages** 
    
    npm install
    
 **Update the node packages** 
    
    npm update

**Start the scss conversion in parallel with browser-sync**

    gulp

 **Start building distribution folder** You will need to surround the css links and js scripts with inclusion code "build:css css/main.css" and "build:js js/main.js" in all html files before building.

    gulp build

 **Delete dist folder** 

    gulp clean
