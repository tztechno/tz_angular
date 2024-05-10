npm install @angular/cli

npx ng new my-app

? Would you like to share pseudonymous usage data about this project with the Angular Team
at Google under Google's Privacy Policy at https://policies.google.com/privacy. For more
details and how to change this setting, see https://angular.io/analytics. Yes

Thank you for sharing pseudonymous usage data. Should you change your mind, the following
command will disable this feature entirely:

    ng analytics disable --global

Global setting: enabled
Local setting: No local workspace configuration file.
Effective status: enabled
? Which stylesheet format would you like to use? CSS             [ 
https://developer.mozilla.org/docs/Web/CSS                     ]
? Do you want to enable Server-Side Rendering (SSR) and Static Site Generation (SSG/Prerendering)? Yes

✔ Packages installed successfully.
    Directory is already under version control. Skipping initialization of git.

    npm start

npx ng generate component header
npx ng generate component footer
npx ng generate component main-content
npx ng generate component sidebar

cd my-app/src/app/main-content
open main-content.component.html

cd my-app/src/app
open app.component.html
npx ng serve