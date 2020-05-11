# ac-test-site
Quickly deploy a basic website to Netlify with the AC tracking code built in. Useful when you want to create multiple websites without the overhead of using a website builder.

[View Demo](https://ac-test-site.netlify.app/)

## One-click deploy
You'll need a Netlify account connected to GitHub. Click the button below and follow the instructions. You will need to enter the account id (the one in the tracking code) for the AC account you want to use. Additionally, add `*.netlify.app` to your allowed domains in Tracking settings.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/NickCiliak/ac-test-site)

### How to change your tracking id or site name after deployment
1. Go to your Netlify dashboard and click your site.
2. Go to Settings > Build & deploy > Environment. Under "Environment varibles", click "Edit variables".
3. Update the variables and click "Save".
4. Trigger a new deploy of the site by going to Deploys > Trigger Deploy.

## Development
1. Clone this repo
2. Run `npm install` to install dependencies.
3. Run `gulp` to build the project and start a development server.
