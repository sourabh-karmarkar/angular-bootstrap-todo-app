# SourabhTodoList

### [Follow this Angular tutorial link](https://www.youtube.com/watch?v=0LhBvp8qpro)

### Prerequisites

- Install [NodeJS](https://nodejs.org/en/)

- Install [Angular](https://angular.io/)
```
npm install -g @angular/cli
```

- Initialize a new angular app
```
ng new angular-bootstrap-todo-app
```

- Install [bootstrap](https://getbootstrap.com/)
```
npm install bootstrap
```

- Install [jquery](https://jquery.com/)
```
npm install jquery
```

- Generate a todo component
```
ng generate component MyComponents/todos
```

- Create a production build
```
ng build --configuration production
```

-----------------------------------

## Deployment process

- Create a GH-pages Branch
```
git branch gh-pages
git checkout gh-pages
git push origin gh-pages
```

- On the toolbar under the repo name, click Settings > Pages.
Under Build and deployment, select Deploy from a branch. Next, select gh-pages as the name of the branch, then click Save. This will create a GH-pages link at the top right under the GH-pages label.

- Copy this link to the published site as illustrated below. You will use the link to set up the base-ref during deployment.

- Install Angular-CLI-GHpages
```
ng add angular-cli-ghpages
```

- Configure your app to a remote server.
```
ng deploy --base-href=https://GithubUserName.github.io/GithubRepoName/
```

- Go to github pages section and visit the link where the app is deployed.

Deployment was done by following this tutorial to [deploy an angular app](https://www.makeuseof.com/angular-app-github-deploy-using-angular-cli/)

-----------------------------------

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build --configuration production` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
