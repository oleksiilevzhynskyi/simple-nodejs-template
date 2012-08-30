# Simple Node.js template

* `git clone git@github.com:levzhinsky/simple-nodejs-template.git`
* Change package.json. Set name, dependencies.
* Write some code
* Deploy to heroku

## Deploy to Heroku
* `heroku login`
* `heroku apps:create %APPNAME%`
* `git push heroku master`
* `heroku ps:scale web=1`
* `heroku open`

Use `heroku logs` for see logs.
