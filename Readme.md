## Run the script in package.json with an appname; your app will be created or served.

## Usage example derived from the package.json
```bash
git clone https://github.com/MichaelDimmitt/quick-angular-non-global-install.git;
npm install;
npm run setup
npm run all <app name>
npm run app <app name>
npm run i <app name>
npm run make <app name>
```
## All of the frameworks have been aliased for your convenience:
```bash
npm run angular angular-project-name;
npm run vue vue-project-name;
npm run cra react-project-name;
npm run ember ember-project-name;
```

## Do a full install and build an example project for all frameworks in a single command.
npm run test

## Already created the app? No problem, the project will start the server!

## Future case
1) Coming soon! preact implementation.
1) Scripts will create projects into a folder matching that framework.
<br/> example: `npm run vue appname` will create a project at `./vue/appname`
2) cache installing, if user repeatedly uses the same framework. elsewise reinstall everything.
3) alternative solution, folder structure maintains its own nodemodules.

## Request for additional frameworks! [click-me](https://github.com/MichaelDimmitt/js-framework-house/issues/new)
issues tab: https://github.com/MichaelDimmitt/js-framework-house/issues/new

## Useful links:
Regarding Preact:
https://www.reddit.com/r/javascript/comments/5k682g/what_is_in_react_that_preact_does_not_have/
