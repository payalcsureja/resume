# ReactJS Resume Portal
### <a href="https://payalcsureja.github.io/resume">LIVE DEMO</a>


## Make it Your Own!
### 1. Make sure you have what you need
To build this website, you will need to have Node >=6 downloaded and installed on your machine. If you don't already have it, you can get it <a href="https://nodejs.org/en/download/">HERE</a>
### 2. Build a Create-React-App
Next, you will build the initial application using a handy tool called Create-React-App. This allows you to get up and running with a React app without the headache of setting up build-tool configurations. Go <a href="https://reactjs.org/docs/installation.html">HERE</a> to get started.
When the app building is finished run `cd yourappname` and run `npm start` to test it out.
Hit ctrl+c in the terminal when you want to stop the server that the above command starts.
For this project we will also need to install JQuery and ReactGA, do this by running `npm install jquery --save` and `npm install react-ga --save` in your terminal while inside your project folder. YOU MUST RUN THESE COMMANDS.
### 3. Download the template
Once you have a React app up and running by following the steps in the above link, download my code by hitting the green "clone or download" button above and hit download zip. All you will have to do now is replace the "public" and "src" folders of your newly built app with mine that you just downloaded. If you run `npm start` now, you should see that your app renders the same as the one at the live demo link above.
### 4. Replace images and fonts
Next, you will want to replace the images, and fonts if you like, with your own. All you have to do is replace the images at public/images/header-background.jpg, public/images/testimonials-bg.jpg and public/favicon.ico with your own. <em>YOU MUST KEEP THE SAME NAMES ON THE IMAGES.</em>
### 5. Fill in your personal info
To populate the website with all of your own data, open the public/resumeData.json file and simply replace the data in there with your own. Images for the porfolio section are to be put in the public/images/portfolio folder.
### 6. Make any styling changes you would like
Of course, all of the code is there and nothing is hidden from you so if you would like to make any other styling changes, feel free!
### 7. Enjoy your new Resume Website
When you're all done, run `npm start` again and you'll see your new personal resume website! Congratulations!


## Credits
##### Udemy Course
<a href="https://www.udemy.com/projects-in-reactjs-the-complete-react-learning-course/learn/v4/overview">Projects in ReactJS: The Complete React Learning Course by Eduonix</a>

#### HTML Design Template
<a href="https://www.styleshout.com/free-templates/ceevee/">Ceevee Template by Styleshout</a>

<!--##### Header photo credit
<a href="https://unsplash.com/@mischievous_penguins?utm_medium=referral&amp;utm_campaign=photographer-credit&amp;utm_content=creditBadge">Casey Horner</a>-->

<!--##### Testimonial photo credit
<a href="https://unsplash.com/@samuelzeller?utm_medium=referral&amp;utm_campaign=photographer-credit&amp;utm_content=creditBadge">Samuel Zeller</a>-->

# ReactJS Resume Website Template
![ReactJS Resume Website Template](resume-screenshot.jpg?raw=true "ReactJS Resume Website Template")
### <a href="https://react-resume-template.herokuapp.com/">LIVE DEMO</a>

<!--
# To deply react app on git hub pages https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#github-pages

1)
npm install gh-pages --save-dev

2) changes to project package.json

  - Add homepage to package.json
    The step below is important!
    If you skip it, your app will not deploy correctly.

    Open your package.json and add a homepage field for your project:

    "homepage": "https://myusername.github.io/my-app",
    or for a GitHub user page:

    "homepage": "https://myusername.github.io",

    Create React App uses the homepage field to determine the root URL in the built HTML file.

        "homepage": "https://payalcsureja.github.io/resume",

  - deply step with predeploy step to run build and cleanup cache. predeploy script will run automatically before deploy is run.

    "deploy" : "npm run build && npm run cleanup && gh-pages -d build"
    "cleanup": "rm -rf node_modules/gh-pages/.cache"

    OR

    "predeploy": "npm run build",
    "deploy": "npm run cleanup && gh-pages -d build",
    "cleanup": "rm -rf node_modules/gh-pages/.cache"

    OR for multiple builds

    "predeployLive": "npm run build",
    "deployLive": "npm run cleanup && gh-pages -d build -b deploy -e build",
    "cleanup": "rm -rf node_modules/gh-pages/.cache"

    If you are deploying to a GitHub user page instead of a project page you'll need to make two additional modifications:

    First, change your repository's source branch to be any branch other than master.
    Additionally, tweak your package.json scripts to push deployments to master:
    "scripts": {
        "predeploy": "npm run build",
    -   "deploy": "gh-pages -d build",
    +   "deploy": "gh-pages -b master -d build",

Note:
1)cmd to clean cache if it fails and gives this secome time ProcessError: fatal: A branch named 'test-pages' already exists.
rm -rf node_modules/gh-pages/.cache

2) change got remote url to use either token or ssh authentication instead of username/password to use gh-pages deploy

# https https://help.github.com/articles/about-remote-repositories/
git remote add origin https://github.com/payalcsureja/resume.git
#ssh https://help.github.com/articles/changing-a-remote-s-url/
git remote set-url origin git@github.com:payalcsureja/resume.git
#token Create a new Personal Access Token https://github.com/settings/tokens
git remote set-url origin https://payalcsureja:<token>@github.com/payalcsureja/resume .

Troubleshooting
# "/dev/tty: No such a device or address"
If, when deploying, you get /dev/tty: No such a device or address or a similar error, try the follwing:

Create a new Personal Access Token
git remote set-url origin https://<user>:<token>@github.com/<user>/<repo> .
Try npm run deploy again

# Filename too long in git for windows
git config --system core.longpaths true

edit .gitconfig and add

[core]
longpaths = true

git clone -c core.longpaths=true <repo-url>

#https://itnext.io/so-you-want-to-host-your-single-age-react-app-on-github-pages-a826ab01e48
#for routhing and base url
#index.js
ReactDOM.render(<Router basename={process.env.PUBLIC_URL}>< App /></Router>, document.getElementById(‘root’));
#App.js
<Route exact path={`/`} render={ (routerProps) => < Home routerProps={routerProps} setUpGame={this.setUpGame} />} />
# hard refresh and routing with liinking
https://github.com/rafrex/spa-github-pages



-->