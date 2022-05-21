# Angular Material Forms

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### How to implement form array in angular

### Steps: 

- Create angular project with below command.
	"ng new angular-material-forms"

- After successfully creation of angular app, change file directory to project-name.
	"cd angular-material-forms"

- Open project in vs code using "code ."

- Then run the project using "ng serve".

- Open project in chrome using `localhost:4200`

- Open app component in vs code and remove the content which is created by angular cli while creating the app.

- Adding angular material using the command `ng add @angular/material`

- Select theme , Am selecting  `Indigo/Pink`

- Set up global Angular Material typography styles? Am selecting as `y`

- Set up browser animations for Angular Material? (Y/n) Select 'y'.

- Created Shared Module in the libs folder.And import , export material modules.

- Create Signup component in the apps/component folder.

- Add signup compopent in router and path as `signup`.

- Add ReactiveFormsModule, FormsModule in app.module.ts

- Open signup.component.ts , then add formbuilder as dependency in constuctor.

- Create form variable above the constructor.

- Create formInit method to intialize the form and call the method form either contructor or ngOninit.

- And create form group using form builder and add controls in that same form.

- Form Controls like firstName, secondName , email, username, password and mobile.

- Add The below html in signup.component.html.
  
  
  ### OUTPUT
  

