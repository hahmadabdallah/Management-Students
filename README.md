# project-management-students 

## Used technologies:
 <b> Front End  </b>
    <ul>
    <li>Angular 2</li>
      <li>AngularFire2</li>
        <li>Firebase SDK</li>
          <li>Bootstrap 4</li>
    </ul>
  
## Running Steps
   ###Install
   npm install firebase @angular/fire --save
   Deploying to Firebase:
Prerequisites
Create a free Firebase account at https://firebase.google.com
Create a project from your Firebase account console
Configure the authentication providers for your Firebase project from your Firebase account console

Enable Email/Password sign-in:

In the Firebase console, open the Auth section.
On the Sign in method tab, enable the Email/password sign-in method and click Save.


Open /src/environments/environment.ts and add your Firebase configuration:

export const environment = {
  production: false,
  firebase: {
    apiKey: '<your-key>',
    authDomain: '<your-project-authdomain>',
    databaseURL: '<your-database-URL>',
    projectId: '<your-project-id>',
    storageBucket: '<your-storage-bucket>',
    messagingSenderId: '<your-messaging-sender-id>'
  }
};

Clone the app, install package dependencies, and start the dev server @ localhost:4200
$ git clone https://github.com/r-park/todo-angular-firebase.git
$ cd 
$ npm install
$ npm serve

      
 ## Application Features:
   <ul>
    <li>register account </li>
    <li>Login by email ,Facebook,gmail</li>
    <li>Add,view delete ,update students </li>
    <li>Export PDF</li>
   </ul>
