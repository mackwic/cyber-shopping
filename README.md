Cyber-shopping
===============

An experimental interface for eshopping in html5

#### Status
<table>
  <tr>
    <td>Work in progress</td>
    <td><a href="https://waffle.io/mackwic/cyber-shopping"><img alt="Stories in Ready" src="https://badge.waffle.io/mackwic/cyber-shopping.png?label=ready&title=Ready"></a></td>
  </tr>
  <tr>
    <td>Build Status</td>
    <td><a href="https://drone.io/github.com/mackwic/cyber-shopping/latest"><img alt="Build Status" src="https://drone.io/github.com/mackwic/cyber-shopping/status.png"></a></td>
  </tr>
  <tr>
    <td>Code Quality Metrics</td>
    <td><a href="https://codeclimate.com/github/mackwic/cyber-shopping"><img alt="Code Climate" src="https://codeclimate.com/github/mackwic/cyber-shopping.png"></a></td>
  </tr>
</table>


Organization
------------
- [Agile Workspace](https://waffle.io/mackwic/cyber-shopping) (reference issues and pull requests in commits)
- API design
    * [Documentation](http://docs.cybershopping.apiary.io/)
    * [Mock testing; cybershopping.apiary.io](http://cybershopping.apiary.io)
- Quick backend
    * [Editable
      Content](https://docs.google.com/spreadsheets/d/1A6obfI6se66jtGIEi0F-S7dsO057p_MbhMjUGLhPkVk/edit?usp=sharing)
    * [JSON
      Content](https://spreadsheets.google.com/feeds/list/1A6obfI6se66jtGIEi0F-S7dsO057p_MbhMjUGLhPkVk/od6/public/values?alt=json) (content is in `data.feed.entry[n]['gsx$' + columnName]`)

## angular-brunch-seed-livescript
#### A started project for AngularJS using Brunch.io with LiveScript

[AngularJS](http://angularjs.org) + [Brunch](http://brunch.io) + [Bower](http://bower.io/) + [LiveScript](http://livescript.net/)

Features:
* LiveScript / LESS automatically compiled on save
* auto-reload during development saves you from manually refreshing the page
* Javascript / CSS minification for production
* [Karma](http://karma-runner.github.io/0.10/index.html) integration for
  unit tests
* Bootstrap integration with themes.

### How to use angular-brunch-seed-livescript

* `git clone https://github.com/white1033/angular-brunch-seed-livescript.git` to clone the **angular-brunch-seed-livescript** repository
* `cd angular-brunch-seed-livescript`
* `./scripts/init.sh` to install node packages

or if you have **Brunch** installed run:

`brunch new myapp --skeleton https://github.com/white1033/angular-brunch-seed-livescript`

### Running the app during development

* `./scripts/server.sh` to serve using **Brunch**

Then navigate your browser to [http://localhost:3333](http://localhost:3333)

#### Running the app in production

* `./scripts/production.sh` to minify javascript and css files.

#### Running unit tests

* `./scripts/test.sh` to run unit test with [Karma](http://karma-runner.github.io/0.10/index.html)
* Open the browser you would like to test to [http://localhost:3334](http://localhost:3334)

Notes:

- If you would like to write your test in livescript run `./scripts/compile-tests.sh` in a
seperate window.
- Testacular will run tests on save. To insure that changes are
saved be sure to have `./script/server.sh` or `./script/development.sh` running in the console.
- If you are on OS X you set the browsers that you would like to target
  in the `/test/karma.conf.js` file E.g. `browser = ["ChromeCanary", "Firefox"]`

#### End to end testing

WIP

#### Common issues

`EMFILE` error
- EMFILE means there're too many open files. Brunch watches all your project files and it's us
