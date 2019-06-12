#Annotations Comparator
This app is used to compare text annotations on a given manuscript. There are two main tools used for annotations comparison.

Compare Annotations - Given a manuscript which was annotated by multiple annotators, gathers all matching annotations and combine them to a single annotations box. This is mainly used in case there are more than 2 annotators for a given manuscript. The annotation box will be colored according to the match percentage of the annotations, see the color map in the top left corner of the app.
Compare Versions(diff) - Given a manuscript, chapter number, page number and two annotations versions, comparing annotations 1 to 1 and displays the diff between these two, using https://github.com/kpdecker/jsdiff diff library.
For developer notes, see - devnotes.txt.

This app extends the git of https://github.com/hodamr/ngx-manusctipts-viewer/ student work.

This project was generated with Angular CLI version 6.0.3.

Development server
Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

Code scaffolding
Run ng generate component component-name to generate a new component. You can also use ng generate directive|pipe|service|class|guard|interface|enum|module.

Build
Run ng build to build the project. The build artifacts will be stored in the dist/ directory. Use the --prod flag for a production build.

Use npm install --save-dev @angular-devkit/build-angular in case of Could not find module "@angular-devkit/build-angular" error.

Running unit tests
Run ng test to execute the unit tests via Karma.

Running end-to-end tests
Run ng e2e to execute the end-to-end tests via Protractor.

Further help
To get more help on the Angular CLI use ng help or go check out the Angular CLI README.
