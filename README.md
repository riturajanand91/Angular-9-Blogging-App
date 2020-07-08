## Angular-9 Blogging App Auth0 + Bulma + Firebase (Realtime Database) + Rich text Editor + Disqus + Ngx pagination + NGX Spinner + Compodoc.
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

Whats like developing a **Blogging Application using Angular-9**.


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.3.

## Functionalities

1.  Mediumish layout Blog using Bulma.
2.  Auth0 for user authentication for admin part.
    -make sure to configure the port number in auth0.
3.  Rich text editor for better blogs interface to the writers and authors.
4.  CRUD Operations like
    - User can view and comment on blogs.
    - Logged in users can edit/add/delete blogs.
5.  Disqus comments for dynamic and realtime comments.
6.  NGX pagination for Pagination.
7.  NGX Spinner for Loading Data.
8.  Firebase for DB Functionalities.

1.  Security

- Implmented Auth0 Authentication and Authorization

## Tools and Technologies

- Technologies: HTML,Bulma CSS, Bootstrap, CSS, Angular-9, Firebase, Pagination,Rich text Editor,Disqus Comments PWA
- Database : Angular Firebase (Realtime Database).

#### This Projects covers all fundamentals of Angular.

- Multiple Modules.
- Shared and Child modules.
- Lazy loading.
- Reusable Components.
- Components, Template and DataBinding.
- Form Validation.
- Reactive Forms.
- HttpClient.
- Animations.
- Toastr Notifications.
- Dependency Injection.
- Multiple Routing & Navigation.
- Service Workers.
- Multiple Pipes.
- Filters.
- Authentication & Authorization.
- Auth Guards etc..

# Installation

1.  Angular CLI
    - [Download Angular CLI](https://cli.angular.io/)
2.  NodeJs
    - [Download Nodejs](https://nodejs.org/en/download/)
3.  Package Manager - NPM / Yarn
4.  Clone the repository and run `npm install` if you use **npm** as package manager or `yarn install` if you use **yarn** as package manager.

5.  Configure your firebase configuration `src/environments/firebaseConfig.ts`

    ```
    export const FireBaseConfig = {
        apiKey: "YOUR_API_KEY",
        authDomain: "YOUR_AUTH_DOMAIN",
        databaseURL: "YOUR_DATABASE_URL",
        projectId: "YOUR_PROJECT_ID",
        storageBucket: "YOUR_STORAGE_BUCKET",
        messagingSenderId: "YOUR_SENDER_ID"
    };
    ```
6.  Configure your disqus comments config in `src\app\shared\shared.module.ts`  
6. Run the Server.    

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Somethings wrong!!

- If you find that something's wrong with this package, you can let me know by raising an issue on the GitHub issue tracker
