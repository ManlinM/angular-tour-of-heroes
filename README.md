# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.2.

## First Step
- created the heroes component using 'ng g c'
- created an interface for the component to use for the hero obj
- implemented ngModel for two way data binding in the form
## Second Step
- Added a list of mock heroes, and used ngFor to display the list of heroes
- Added styles to the list
- implemented class.className and ngClass to alter some styles on the selected hero
## Third Step
- Added hero detail component to make the application easier to update and maintain
- Implemented property binding so that the parent componet can pass data to the child
  - Used @Input for selectedHero in hero-detail component, so that selectedHero is available for binding
