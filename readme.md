#Ionic2
..................................

1. npm install -g ionic cordova
   [
    cordova: the framework thst handles the webapp to nativeapp compilation steps
    ionic: the framework to creates the webapp
   ]
2. ionic start my-places blank --type=ionic-angular
3. In ionic views are the pages. It maintains a page stack and the page need to display should push to the       stack and pop to hide the page.
   Default routing starts: <ion-nav [root]="rootPage"></ion-nav>

# Generate a new page
1. Create a new page: ionic generate page new-place
2. Register the page in `app.module`