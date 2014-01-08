# HTML Toolkit Project

Small projects usually have traditional workflow:

* design -> pages' mocks in PSD
* psd2html -> HTML/CSS/JS static
* CMS -> finished site as it heart uses one of the popular CMS like Drupal, Joomla and so forth

Well, it's all about the second step: **PSD->HTML workflow**

Inevitably developers split mocks in some entities, blocks wich have independent meaning. Traditionally we do it only inside our minds and write code as it's need to be served for browser. In single files: html, css, js.

Modern even relative small web site is already enough complicated for using css preprocessors, dependencies manager and tools for routine tasks.

Approaches which assume splitting project into independent parts are wide spreaded within building huge web services: [SMACCS](http://smacss.com/), [OOCSS](http://coding.smashingmagazine.com/2011/12/12/an-introduction-to-object-oriented-css-oocss/), [BEM](http://bem.info/).

It's convinient to use [light BEM version](http://blog.sapegin.me/all/opor-methodology) for developing middle and even small web sites.

There is the next technology stack:

* [Stylus](http://learnboost.github.io/stylus/) with useful mixins
* [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate)'s normalize
* [Nunjucks](http://jlongster.github.io/nunjucks/) as a template enginge with `block`, `extend` and `incude` killer features
* [Bower](https://github.com/bower/bower) for downloading and managing libraries, jquery plugins
* [Grunt](https://github.com/gruntjs/grunt) for routine tasks and assembling project for transfering it for the next step

So, this project about **modern PSD->HTML workflow** and **tools for developing**:

* project stubbing
* CLI program which helps working with file structure, maybe it should be `yeoman` generator
* simple, powerful and robust developer's HTTP-server
* methodology and structure
* articles, experience
* something else...

If you want to help with something of the list above you should:

* find corresponding repo
* make issue
* create branch with name like `#1-make-some-killer-feature`
* make pull request, leave a comment with link to that issue

If you want to make new repo, you've got an idea — drop me a line