# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


## Deploy a React SPA (single page application) on Netlify

So far, we've created applications that we've run locally on our `localhost`. As you can imagine, this isn't how websites normally work! It's time to level up to deployment - hosting your app on a server outside of your own computer, provided by an external service, so that your app can be accessed through a URL from any browser/device. 

There are many tools out there to do this, both free and paid, but we'll start with getting a front end deployed using a tool called Netlify.

Note: The free tier of Netlify doesn't allow deployment of private organisation repositories, so as this repository is within the School of Code organisation, you'll need to go into this repo's settings and scroll down to the "danger zone" at the bottom and change the visibility to public before you deploy. Alternatively, each member of your pair can fork a copy of the repository into their own personal Github.

1. Have a look through the Netlify documentation:
 - https://docs.netlify.com/
 - Remember, you can find other resources/videos via Google - just search for deploying Create React App on Netlify (or similar).
 
Practice taking turns to explain the answers to these questions:
 - What is Netlify?
 - What problems does Netlify solve?
 - When would you use it?
 - When would you not use it?
 - What are some alternatives/competitors to Netlify? (Just to know what else is out there.)

2. Initialise your React app with Create React App. 
 - It can just be the standard "Hello World" boilerplate.
 - When you deploy your app to Netlify, Netlify will assume your React project is at the root of your repository. If it's not, you can still deploy but it'll take extra configuration. Have a google for how you can have the Create React App command not initialise the project in a subfolder (as it normally does).

3. Get it deployed to Netlify by following this documentation: https://docs.netlify.com/integrations/frameworks/create-react-app/#app.
 - You'll need to sign up for a Netlify account.
 - If you're using the repository within the SchoolOfCode organisation (set to public), in the "Import an existing project from a Git repository" screen, you'll need to use the dropdown to change from your personal Github account to the SchoolOfCode organisation. If you're using a forked version, you can leave this as your own Github username.
 - Ensure that it's configured for automatic deployment (so that every time you push to GitHub, Netlify automatically rebuilds and redeploys your app).
 - Once you deploy, you should be able to access your deployed app via a public URL that Netlify has given you.
 - Bonus: Change the public URL to something more meaningful/personalised.

4. Make a meaningful change to the app (commit and push to git) and ensure that automatic deployment has worked (troubleshoot if not).
 - You should see your changes appear at the public URL (after a few minutes).

5. Bonus tasks - keep exploring front end deployment! 
 - Research Netlify docs/ecosystem (for things like how to configure environment variables, etc.)
 - Research Netlify edge functions, analytics, forms, identity, etc.
 - Try a different way of deploying, such as using [Github pages](https://pages.github.com/) or [Vercel](https://vercel.com/docs). Compare and contrast with the experience on Netlify.
