# Universal


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.6 as a quick-starter for angular application that needs Server-side rendering.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.



### Development (Client-side only rendering)
* run `npm run start` which will start `ng serve`

### Production (also for testing SSR/Pre-rendering locally)
* `npm run build:ssr && npm run serve:ssr` - Compiles your application and spins up a Node Express to serve your Universal application on `http://localhost:4000`.

* `npm run build:prerender && npm run serve:prerender` - Compiles your application and prerenders your applications files, spinning up a demo http-server so you can view it on `http://localhost:8080`

* `npm run build-demo:prerender` - does same thing as above but with demo configuration. (Please note, run this command always after `npm run build:prerender` command).
  
**Note**: To deploy your static site to a static hosting platform you will have to deploy the `dist/browser` folder, rather than the usual `dist`

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md). And to know more on Angular Universal visit the [Official Github Page](https://github.com/angular/universal-starter).
