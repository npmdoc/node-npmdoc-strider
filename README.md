# api documentation for  [strider (v1.9.6)](https://github.com/Strider-CD/strider#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-strider.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-strider) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-strider.svg)](https://travis-ci.org/npmdoc/node-npmdoc-strider)
#### Brilliant continuous deployment platform

[![NPM](https://nodei.co/npm/strider.png?downloads=true)](https://www.npmjs.com/package/strider)

[![apidoc](https://npmdoc.github.io/node-npmdoc-strider/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-strider_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-strider/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-strider/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-strider/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "strider": "bin/strider"
    },
    "browser": {
        "bootstrap": "./vendor/bootstrap/js/bootstrap.js",
        "sortable": "./vendor/Sortable/js/Sortable.js",
        "bootbox": "./vendor/bootbox/js/bootbox.js",
        "codemirror": "./vendor/CodeMirror/js/codemirror.js",
        "codemirror-shell": "./vendor/CodeMirror/js/shell.js",
        "timeago": "./vendor/jquery-timeago/js/jquery.timeago.js",
        "ui-codemirror": "./public/libs/ui-codemirror.js",
        "ui-bootstrap": "./public/libs/ui-bootstrap.js"
    },
    "browserify": {
        "transform": [
            "browserify-shim"
        ]
    },
    "browserify-shim": "./shim.js",
    "bugs": {
        "url": "https://github.com/Strider-CD/strider/issues"
    },
    "dependencies": {
        "activedirectory": "^0.7.2",
        "ansi_up": "^1.3.0",
        "async": "^2.0.1",
        "bcryptjs": "^2.1.0",
        "bluebird": "^3.4.1",
        "body-parser": "^1.10.0",
        "chalk": "^1.1.3",
        "co-router": "^1.0.3",
        "compression": "^1.2.2",
        "connect-flash": "^0.1.1",
        "connect-mongo": "^1.3.2",
        "connect-slashes": "^1.3.1",
        "cookie-parser": "^1.3.3",
        "cors": "^2.5.2",
        "debug": "^2.2.0",
        "errorhandler": "^1.3.0",
        "everypaas": "0.0.8",
        "express": "^4.10.6",
        "express-session": "^1.9.3",
        "global-tunnel": "^1.2.0",
        "gravatar": "^1.1.0",
        "in-publish": "^2.0.0",
        "lodash": "^4.14.0",
        "md5": "^2.0.0",
        "method-override": "^2.3.0",
        "mongoose": "^4.7.6",
        "morgan-debug": "^1.0.0",
        "node-rsa": "^0.4.0",
        "passport": "^0.3.2",
        "passport-local": "^1.0.0",
        "path-to-regexp": "^1.0.2",
        "pug": "^2.0.0-beta4",
        "rc": "^1.0.3",
        "request": "^2.49.0",
        "semver": "^5.3.0",
        "serve-favicon": "^2.2.0",
        "socket.io": "^1.2.1",
        "socket.io-client": "^1.0.6",
        "sshpk": "^1.8.3",
        "step": "^0.0.6",
        "strider-bitbucket": "^1.2.0",
        "strider-build-badge": "^0",
        "strider-cli": "^2.0.0",
        "strider-custom": "^0.6.0",
        "strider-ecosystem-client": "^1.2.1",
        "strider-email-notifier": "^1.0.0",
        "strider-env": "^0.5.1",
        "strider-extension-loader": "^0.4.5",
        "strider-git": "^1.0.0",
        "strider-github": "^2.3.0",
        "strider-gitlab": "^1.2.3",
        "strider-heroku": "^0.1.1",
        "strider-mailer": "^0.2.0",
        "strider-metadata": "^0.0.3",
        "strider-node": "^1.0.0",
        "strider-python": "^0.2.1",
        "strider-ruby": "^0.0.2",
        "strider-simple-runner": "^1.0.0",
        "strider-slack": "^2.0.0",
        "strider-ssh-deploy": "^1.0.0",
        "swig": "^0.14.0",
        "thirty-two": "^1.0.1",
        "validator": "^5.5.0",
        "winston": "^2.2.0"
    },
    "description": "Brilliant continuous deployment platform",
    "devDependencies": {
        "angular": "1.5.7",
        "angular-route": "1.5.7",
        "apidoc": "^0.16.1",
        "apidoc-markdown": "github:zambonilli/node-apidoc-markdown",
        "babel-preset-es2015": "^6.9.0",
        "babelify": "^7.3.0",
        "bower-installer": "^1.2.0",
        "browserify": "^13.0.1",
        "browserify-shim": "^3.8.0",
        "chai": "^3.5.0",
        "chai-as-promised": "^5.3.0",
        "docpress": "0.7.1",
        "eslint": "^3.0.1",
        "expect.js": "^0.3.1",
        "git-update-ghpages": "^1.3.0",
        "httpcheck": "^0.3.0",
        "istanbul": "^0.4.4",
        "jquery": "^2.2.4",
        "less": "^2.2.0",
        "minifyify": "^7.3.3",
        "mkdirp": "^0.5.0",
        "mocha": "^3.0.0",
        "node-mocks-http": "^1.2.4",
        "sinon": "^1.10.3",
        "standard-version": "^4.0.0",
        "surge": "^0.18.0",
        "watchify": "^3.4.0",
        "wd": "^0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5bb821f5d266285ff5f09f803bd71e8fdbd3c22d",
        "tarball": "https://registry.npmjs.org/strider/-/strider-1.9.6.tgz"
    },
    "engines": {
        "node": ">=4.2",
        "npm": ">=2.0.0"
    },
    "gitHead": "9bb19dc4f3e6c7f6ed12a01d8fa29bab97c5f455",
    "homepage": "https://github.com/Strider-CD/strider#readme",
    "keywords": [
        "strider",
        "continuous integration",
        "continuous deployment",
        "testing",
        "deployment"
    ],
    "license": "BSD-3-Clause",
    "main": "main.js",
    "maintainers": [
        {
            "name": "niallo",
            "email": "niallo@beyondfog.com"
        },
        {
            "name": "peterbraden",
            "email": "peterbraden@peterbraden.co.uk"
        },
        {
            "name": "knownasilya",
            "email": "ilya@burstcreations.com"
        }
    ],
    "name": "strider",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/Strider-CD/strider.git"
    },
    "scripts": {
        "api-docs": "apidoc -i lib/ -o apidocs/",
        "api-docs:md": "apidoc-markdown -p apidocs -o docs/api.md",
        "build": "npm run pre && npm run styles && browserify -d -t [babelify --presets [ es2015 ] --only client] -p [minifyify --output dist/scripts/bundle.map] -e client/app.js -o dist/scripts/app.js",
        "build-debug": "npm run pre && npm run styles-debug && browserify -d -t [babelify --presets [ es2015 ] --only client] -e client/app.js -o dist/scripts/app.js",
        "debug": "node debug bin/strider --no-cluster",
        "deploy:docs": "npm run api-docs:md && npm run docs:build && npm run docs:publish",
        "dev": "npm run build-debug && bin/strider",
        "docs:build": "docpress b",
        "docs:publish": "git-update-ghpages -b master Strider-CD/strider-cd.github.com _docpress",
        "lint": "eslint *.js bin lib client",
        "pre": "mkdirp dist/scripts dist/styles",
        "prepublish": "in-publish && npm run build || not-in-publish",
        "release": "standard-version",
        "start": "bin/strider",
        "styles": "lessc client/styles/strider.less > dist/styles/styles.css",
        "styles-debug": "lessc --source-map client/styles/strider.less dist/styles/styles.css",
        "test": "npm run build && npm run lint && npm run test-unit",
        "test-unit": "mocha --recursive test/unit",
        "unitcov": "istanbul cover ./node_modules/mocha/bin/_mocha --recursive test/unit",
        "vendor": "bower-installer",
        "watch": "npm run pre && watchify -e client/app.js -o dist/scripts/app.js"
    },
    "version": "1.9.6"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module strider](#apidoc.module.strider)
1.  [function <span class="apidocSignatureSpan">strider.</span>backchannel (emitter, ws)](#apidoc.element.strider.backchannel)
1.  [function <span class="apidocSignatureSpan">strider.</span>websockets (sio, sessionStore)](#apidoc.element.strider.websockets)
1.  object <span class="apidocSignatureSpan">strider.</span>app
1.  object <span class="apidocSignatureSpan">strider.</span>auth
1.  object <span class="apidocSignatureSpan">strider.</span>backchannel.prototype
1.  object <span class="apidocSignatureSpan">strider.</span>email
1.  object <span class="apidocSignatureSpan">strider.</span>humane
1.  object <span class="apidocSignatureSpan">strider.</span>jobs
1.  object <span class="apidocSignatureSpan">strider.</span>libconfig
1.  object <span class="apidocSignatureSpan">strider.</span>logging
1.  object <span class="apidocSignatureSpan">strider.</span>middleware
1.  object <span class="apidocSignatureSpan">strider.</span>plugin_templates
1.  object <span class="apidocSignatureSpan">strider.</span>projects
1.  object <span class="apidocSignatureSpan">strider.</span>ssh
1.  object <span class="apidocSignatureSpan">strider.</span>swig_filters
1.  object <span class="apidocSignatureSpan">strider.</span>users
1.  object <span class="apidocSignatureSpan">strider.</span>websockets.prototype

#### [module strider.app](#apidoc.module.strider.app)
1.  [function <span class="apidocSignatureSpan">strider.app.</span>init (config)](#apidoc.element.strider.app.init)
1.  [function <span class="apidocSignatureSpan">strider.app.</span>run (app)](#apidoc.element.strider.app.run)

#### [module strider.auth](#apidoc.module.strider.auth)
1.  [function <span class="apidocSignatureSpan">strider.auth.</span>authenticate (req, res, next)](#apidoc.element.strider.auth.authenticate)
1.  [function <span class="apidocSignatureSpan">strider.auth.</span>forgot (req, res)](#apidoc.element.strider.auth.forgot)
1.  [function <span class="apidocSignatureSpan">strider.auth.</span>logout (req, res)](#apidoc.element.strider.auth.logout)
1.  [function <span class="apidocSignatureSpan">strider.auth.</span>requireAdminOr401 (req, res, next)](#apidoc.element.strider.auth.requireAdminOr401)
1.  [function <span class="apidocSignatureSpan">strider.auth.</span>requireProjectAdmin (req, res, next)](#apidoc.element.strider.auth.requireProjectAdmin)
1.  [function <span class="apidocSignatureSpan">strider.auth.</span>requireUser (req, res, next)](#apidoc.element.strider.auth.requireUser)
1.  [function <span class="apidocSignatureSpan">strider.auth.</span>requireUserOr401 (req, res, next)](#apidoc.element.strider.auth.requireUserOr401)
1.  [function <span class="apidocSignatureSpan">strider.auth.</span>reset (req, res)](#apidoc.element.strider.auth.reset)
1.  [function <span class="apidocSignatureSpan">strider.auth.</span>resetPost (req, res)](#apidoc.element.strider.auth.resetPost)
1.  [function <span class="apidocSignatureSpan">strider.auth.</span>setup (app)](#apidoc.element.strider.auth.setup)

#### [module strider.backchannel](#apidoc.module.strider.backchannel)
1.  [function <span class="apidocSignatureSpan">strider.</span>backchannel (emitter, ws)](#apidoc.element.strider.backchannel.backchannel)

#### [module strider.backchannel.prototype](#apidoc.module.strider.backchannel.prototype)
1.  [function <span class="apidocSignatureSpan">strider.backchannel.prototype.</span>jobDone (emitter, data)](#apidoc.element.strider.backchannel.prototype.jobDone)
1.  [function <span class="apidocSignatureSpan">strider.backchannel.prototype.</span>newJob (job)](#apidoc.element.strider.backchannel.prototype.newJob)
1.  [function <span class="apidocSignatureSpan">strider.backchannel.prototype.</span>onUpdate (project, event, args)](#apidoc.element.strider.backchannel.prototype.onUpdate)
1.  [function <span class="apidocSignatureSpan">strider.backchannel.prototype.</span>send (project, event, args)](#apidoc.element.strider.backchannel.prototype.send)
1.  [function <span class="apidocSignatureSpan">strider.backchannel.prototype.</span>sendJobs (project, event, args)](#apidoc.element.strider.backchannel.prototype.sendJobs)

#### [module strider.email](#apidoc.module.strider.email)
1.  [function <span class="apidocSignatureSpan">strider.email.</span>notifyEmailChange (user, oldEmail)](#apidoc.element.strider.email.notifyEmailChange)
1.  [function <span class="apidocSignatureSpan">strider.email.</span>notifyNewAdmin (user, email)](#apidoc.element.strider.email.notifyNewAdmin)
1.  [function <span class="apidocSignatureSpan">strider.email.</span>notifyPasswordChange (user)](#apidoc.element.strider.email.notifyPasswordChange)
1.  [function <span class="apidocSignatureSpan">strider.email.</span>revokeInvite (code, email)](#apidoc.element.strider.email.revokeInvite)
1.  [function <span class="apidocSignatureSpan">strider.email.</span>sendInvite (code, email)](#apidoc.element.strider.email.sendInvite)
1.  [function <span class="apidocSignatureSpan">strider.email.</span>sendInviteCollaboratorExistingUser (req, email, url)](#apidoc.element.strider.email.sendInviteCollaboratorExistingUser)
1.  [function <span class="apidocSignatureSpan">strider.email.</span>sendInviteCollaboratorNewUser (inviter, email, code, url)](#apidoc.element.strider.email.sendInviteCollaboratorNewUser)
1.  [function <span class="apidocSignatureSpan">strider.email.</span>sendPasswordReset (user)](#apidoc.element.strider.email.sendPasswordReset)

#### [module strider.humane](#apidoc.module.strider.humane)
1.  [function <span class="apidocSignatureSpan">strider.humane.</span>humaneDate (date, compareTo)](#apidoc.element.strider.humane.humaneDate)

#### [module strider.jobs](#apidoc.module.strider.jobs)
1.  [function <span class="apidocSignatureSpan">strider.jobs.</span>jobProject (project, prev, user)](#apidoc.element.strider.jobs.jobProject)
1.  [function <span class="apidocSignatureSpan">strider.jobs.</span>latestJobs (user, small, done)](#apidoc.element.strider.jobs.latestJobs)
1.  [function <span class="apidocSignatureSpan">strider.jobs.</span>small (job)](#apidoc.element.strider.jobs.small)
1.  [function <span class="apidocSignatureSpan">strider.jobs.</span>sort (a, b)](#apidoc.element.strider.jobs.sort)
1.  [function <span class="apidocSignatureSpan">strider.jobs.</span>status (job)](#apidoc.element.strider.jobs.status)

#### [module strider.libconfig](#apidoc.module.strider.libconfig)
1.  [function <span class="apidocSignatureSpan">strider.libconfig.</span>addPlugins (rc, env)](#apidoc.element.strider.libconfig.addPlugins)
1.  [function <span class="apidocSignatureSpan">strider.libconfig.</span>camel (words)](#apidoc.element.strider.libconfig.camel)
1.  [function <span class="apidocSignatureSpan">strider.libconfig.</span>deprecated (env)](#apidoc.element.strider.libconfig.deprecated)
1.  [function <span class="apidocSignatureSpan">strider.libconfig.</span>filterEnv (env, defaults)](#apidoc.element.strider.libconfig.filterEnv)
1.  [function <span class="apidocSignatureSpan">strider.libconfig.</span>getConfig ()](#apidoc.element.strider.libconfig.getConfig)
1.  [function <span class="apidocSignatureSpan">strider.libconfig.</span>smtp (rc)](#apidoc.element.strider.libconfig.smtp)
1.  object <span class="apidocSignatureSpan">strider.libconfig.</span>defaults

#### [module strider.logging](#apidoc.module.strider.logging)
1.  boolean <span class="apidocSignatureSpan">strider.logging.</span>emitErrs
1.  boolean <span class="apidocSignatureSpan">strider.logging.</span>exitOnError
1.  boolean <span class="apidocSignatureSpan">strider.logging.</span>padLevels
1.  boolean <span class="apidocSignatureSpan">strider.logging.</span>stripColors
1.  [function <span class="apidocSignatureSpan">strider.logging.</span>debug (msg)](#apidoc.element.strider.logging.debug)
1.  [function <span class="apidocSignatureSpan">strider.logging.</span>error (msg)](#apidoc.element.strider.logging.error)
1.  [function <span class="apidocSignatureSpan">strider.logging.</span>info (msg)](#apidoc.element.strider.logging.info)
1.  [function <span class="apidocSignatureSpan">strider.logging.</span>silly (msg)](#apidoc.element.strider.logging.silly)
1.  [function <span class="apidocSignatureSpan">strider.logging.</span>verbose (msg)](#apidoc.element.strider.logging.verbose)
1.  [function <span class="apidocSignatureSpan">strider.logging.</span>warn (msg)](#apidoc.element.strider.logging.warn)
1.  number <span class="apidocSignatureSpan">strider.logging.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">strider.logging.</span>_events
1.  object <span class="apidocSignatureSpan">strider.logging.</span>_names
1.  object <span class="apidocSignatureSpan">strider.logging.</span>domain
1.  object <span class="apidocSignatureSpan">strider.logging.</span>exceptionHandlers
1.  object <span class="apidocSignatureSpan">strider.logging.</span>filters
1.  object <span class="apidocSignatureSpan">strider.logging.</span>id
1.  object <span class="apidocSignatureSpan">strider.logging.</span>levels
1.  object <span class="apidocSignatureSpan">strider.logging.</span>profilers
1.  object <span class="apidocSignatureSpan">strider.logging.</span>rewriters
1.  object <span class="apidocSignatureSpan">strider.logging.</span>transports
1.  string <span class="apidocSignatureSpan">strider.logging.</span>level

#### [module strider.middleware](#apidoc.module.strider.middleware)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>anonProject (req, res, next)](#apidoc.element.strider.middleware.anonProject)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>bodySetter (req, res, next)](#apidoc.element.strider.middleware.bodySetter)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>custom404 (req, res, next)](#apidoc.element.strider.middleware.custom404)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>project (req, res, next)](#apidoc.element.strider.middleware.project)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>projectPlugin (req, res, next)](#apidoc.element.strider.middleware.projectPlugin)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>projectProvider (req, res, next)](#apidoc.element.strider.middleware.projectProvider)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>requireBody (paramsList)](#apidoc.element.strider.middleware.requireBody)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>require_admin (req, res, next)](#apidoc.element.strider.middleware.require_admin)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>require_auth (req, res, next)](#apidoc.element.strider.middleware.require_auth)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>require_auth_browser (req, res, next)](#apidoc.element.strider.middleware.require_auth_browser)
1.  [function <span class="apidocSignatureSpan">strider.middleware.</span>require_project_admin (req, res, next)](#apidoc.element.strider.middleware.require_project_admin)

#### [module strider.plugin_templates](#apidoc.module.strider.plugin_templates)
1.  [function <span class="apidocSignatureSpan">strider.plugin_templates.</span>engine (path, options, fn)](#apidoc.element.strider.plugin_templates.engine)
1.  [function <span class="apidocSignatureSpan">strider.plugin_templates.</span>registerBlock (block, render)](#apidoc.element.strider.plugin_templates.registerBlock)
1.  [function <span class="apidocSignatureSpan">strider.plugin_templates.</span>registerTemplate (name, template, dir)](#apidoc.element.strider.plugin_templates.registerTemplate)

#### [module strider.projects](#apidoc.module.strider.projects)
1.  [function <span class="apidocSignatureSpan">strider.projects.</span>allProjects (done)](#apidoc.element.strider.projects.allProjects)

#### [module strider.ssh](#apidoc.module.strider.ssh)
1.  [function <span class="apidocSignatureSpan">strider.ssh.</span>generateKeyPair (comment, callback)](#apidoc.element.strider.ssh.generateKeyPair)

#### [module strider.swig_filters](#apidoc.module.strider.swig_filters)
1.  [function <span class="apidocSignatureSpan">strider.swig_filters.</span>scriptjson (input)](#apidoc.element.strider.swig_filters.scriptjson)

#### [module strider.users](#apidoc.module.strider.users)
1.  [function <span class="apidocSignatureSpan">strider.users.</span>makeAdmin (user, done)](#apidoc.element.strider.users.makeAdmin)

#### [module strider.websockets](#apidoc.module.strider.websockets)
1.  [function <span class="apidocSignatureSpan">strider.</span>websockets (sio, sessionStore)](#apidoc.element.strider.websockets.websockets)
1.  [function <span class="apidocSignatureSpan">strider.websockets.</span>init (server, sessionStore)](#apidoc.element.strider.websockets.init)

#### [module strider.websockets.prototype](#apidoc.module.strider.websockets.prototype)
1.  [function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>addSocket (uid, socket)](#apidoc.element.strider.websockets.prototype.addSocket)
1.  [function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>connected (socket)](#apidoc.element.strider.websockets.prototype.connected)
1.  [function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>removeSocket (uid, socket)](#apidoc.element.strider.websockets.prototype.removeSocket)
1.  [function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>send (users, args)](#apidoc.element.strider.websockets.prototype.send)
1.  [function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>sendEach (users, fn)](#apidoc.element.strider.websockets.prototype.sendEach)
1.  [function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>sendPublic (users, args)](#apidoc.element.strider.websockets.prototype.sendPublic)



# <a name="apidoc.module.strider"></a>[module strider](#apidoc.module.strider)

#### <a name="apidoc.element.strider.backchannel"></a>[function <span class="apidocSignatureSpan">strider.</span>backchannel (emitter, ws)](#apidoc.element.strider.backchannel)
- description and source-code
```javascript
function BackChannel(emitter, ws) {
  this.ws = ws;
  this.users = {};
  this.public = {};
  this.waiting = {};

  emitter.on('job.prepare', prepareJob.bind(null, emitter));
  emitter.on('job.new', this.newJob.bind(this));
  emitter.on('browser.update', this.onUpdate.bind(this));
  emitter.on('job.done', this.jobDone.bind(this, emitter));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.websockets"></a>[function <span class="apidocSignatureSpan">strider.</span>websockets (sio, sessionStore)](#apidoc.element.strider.websockets)
- description and source-code
```javascript
function UserSockets(sio, sessionStore) {
  this.sio = sio;
  this.sockets = {};
  this.sessionStore = sessionStore;
  //sio.enable('browser client minification');  // send minified client
  //sio.enable('browser client etag');          // apply etag caching logic based on version number
  //sio.enable('browser client gzip');
  //sio.set('log level', 1);
  //sio.set('authorization', authorize.bind(this, sessionStore))
  sio.use(authorize.bind(this, sessionStore));
  sio.sockets.on('connection', this.connected.bind(this));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.strider.app"></a>[module strider.app](#apidoc.module.strider.app)

#### <a name="apidoc.element.strider.app.init"></a>[function <span class="apidocSignatureSpan">strider.app.</span>init (config)](#apidoc.element.strider.app.init)
- description and source-code
```javascript
init = function (config) {
  var mongodbUrl = config.db_uri;
  debug('Using MongoDB URL: %s', mongodbUrl);

  mongoose.connect(mongodbUrl, function (error) {
    if (error) {
      console.log('Could not connect to DB: %s', error);
      process.exit(1);
    }
  });

  mongoose.connection.on('error', function (error) {
    debug('MongoDB connection error: %s', error);
  });

  sessionStore = new mongoStore({
    mongooseConnection: mongoose.connection
  });

  swig.init({
    root: config.viewpath,
    // allows errors to be thrown and caught by express instead of suppressed by Swig
    allowErrors: true,
    cache: false,
    filters: require('./swig-filters'),
    tags: require('./swig-tags').tags,
    extensions: {plugin: pluginTemplates}
  });

  var app = express();

  if (isDevelopment) {
    app.use(morganDebug('strider:http', 'dev'));
  }

  if (isTest) {
    // awesome view testingness
    require('./views-test')(app);
  }

  app.set('views', path.join(__dirname, 'views'));
  app.engine('html', pluginTemplates.engine);

  if (config.cors) {
    app.use(cors(config.cors));
  }

  app.use(middleware.bodySetter);
  // parse application/x-www-form-urlencoded
  app.use(bodyParser.urlencoded({extended: false, limit: config.body_parser_limit}));
  // parse application/json
  app.use(bodyParser.json({limit: config.body_parser_limit}));
  app.use(cookieParser());
  app.use(compression());
  app.use(methodOverride());
  app.use(serveFavicon(path.join(__dirname, '..', 'public', 'favicon.ico'), {maxAge: 2592000000}));

  app.use(expressSession({
    secret: config.session_secret, store: sessionStore,
    cookie: {maxAge: MONTH_IN_MILLISECONDS},
    resave: false,
    saveUninitialized: true
  }));
  app.use(connectFlash());

  app.use(function (req, res, next) {
    res.locals.models = models;
    next();
  });

  auth.setup(app); // app.use(passport) is included

  app.use('/vendor', express.static(path.join(__dirname, '..', 'vendor'), {maxAge: MONTH_IN_MILLISECONDS}));
  app.use(express.static(path.join(__dirname, '..', 'dist'), {maxAge: MONTH_IN_MILLISECONDS}));
  app.use(express.static(path.join(__dirname, '..', 'public'), {maxAge: MONTH_IN_MILLISECONDS}));

  if (!config.smtp) {
    debug('No SMTP creds - forgot password flow will not work');
  }

  // Routes
  app.get('/', routes.index);
  app.get('/about', function (req, res) {
    res.render('about');
  });

  app.get('/status', routes.status);
  app.post('/login', function (req, res, next) {
    if (!req.user) {
      return next();
    }

    res.redirect('/');
  }, auth.authenticate);
  app.get('/logout', auth.logout);
  app.get('/forgot', function (req, res) {
    res.render('forgot.html', {
      user: req.user,
      messages: req.flash('error')
    });
  });
  app.post('/forgot', auth.forgot);
  app.get('/reset/:token', auth.reset);
  app.post('/reset/:token', auth.resetPost);

  // Compiled plugin config assets
  app.get('/scripts/plugin-config-compiled.js', apiConfig.server('config', 'js'));
  app.get('/styles/plugin-config-compiled.css', apiConfig.server('config', 'css'));
  app.get('/scripts/account-plugins-compiled.js', apiConfig.server('account', 'js'));
  app.get('/styles/account-plugins-compiled.css', apiConfig.server('account', 'css'));
  app.get('/scripts/plugin-status-compiled.js', apiConfig.server('status', 'js'));
  app.get('/styles/plugin-status-compiled.css', apiConfig.server('status', 'css'));

  app.get('/admin/projects', auth.requireAdminOr401, routesAdmin.projects);
  app.get('/admin/users', auth.requireAdminOr401, routesAdmin.users);
  app.get('/admin/jobs', auth.requireAdminOr401, function (req, res) {
    res.render('admin/jobs.html', {
      version: pjson.version
    });
  });
  app.get('/admin/make_admin', auth.requireAdminOr401, routesAdmin.makeAdmin);
  app.post('/admin/remove_user', auth.requireAdminOr401, routesAdmin.removeUser);
  app.get('/admin/invites', auth.requireAdminOr401, routesAdmin.invites);
  app.get('/admin/:org/:repo/job/:job_id', auth.requireAdminOr401, routesAdmin.job);
  app.get('/admin/plugins', auth.requireAdminOr401, ...
```
- example usage
```shell
...
var k;
// override with c
for (k in c) {
  appConfig[k] = c[k];
}

// Initialize the (web) app
var appInstance = app.init(appConfig);
var cb = callback || defaultCallback;

function defaultCallback(err) {
  if (err) {
    throw err;
  }
}
...
```

#### <a name="apidoc.element.strider.app.run"></a>[function <span class="apidocSignatureSpan">strider.app.</span>run (app)](#apidoc.element.strider.app.run)
- description and source-code
```javascript
run = function (app) {
  var config = require('./config');

  if (isDevelopment) {
    app.use(errorHandler({dumpExceptions: true, showStack: true}));
  }

  if (isProduction) {
    app.use(errorHandler({dumpExceptions: true, showStack: false}));
  }

  // Custom 404 handler.
  // Run after extensions, which might load static middlewares.
  app.use(middleware.custom404);

  // Initialize socket.io
  var server = app.listen(config.port, config.host);
  var sockets = websockets.init(server, sessionStore);
  new Backchannel(common.emitter, sockets);

  console.log(chalk.green('Express server listening on port %s in %s mode'), config.port, app.settings.env);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.strider.auth"></a>[module strider.auth](#apidoc.module.strider.auth)

#### <a name="apidoc.element.strider.auth.authenticate"></a>[function <span class="apidocSignatureSpan">strider.auth.</span>authenticate (req, res, next)](#apidoc.element.strider.auth.authenticate)
- description and source-code
```javascript
function authenticate(req, res, next) {
  if (http.IncomingMessage.prototype.logIn
      && http.IncomingMessage.prototype.logIn !== IncomingMessageExt.logIn) {
    require('../framework/connect').__monkeypatchNode();
  }


  // accumulator for failures from each strategy in the chain
  var failures = [];

  function allFailed() {
    if (callback) {
      if (!multi) {
        return callback(null, false, failures[0].challenge, failures[0].status);
      } else {
        var challenges = failures.map(function(f) { return f.challenge; });
        var statuses = failures.map(function(f) { return f.status; });
        return callback(null, false, challenges, statuses);
      }
    }

    // Strategies are ordered by priority.  For the purpose of flashing a
    // message, the first failure will be displayed.
    var failure = failures[0] || {}
      , challenge = failure.challenge || {}
      , msg;

    if (options.failureFlash) {
      var flash = options.failureFlash;
      if (typeof flash == 'string') {
        flash = { type: 'error', message: flash };
      }
      flash.type = flash.type || 'error';

      var type = flash.type || challenge.type || 'error';
      msg = flash.message || challenge.message || challenge;
      if (typeof msg == 'string') {
        req.flash(type, msg);
      }
    }
    if (options.failureMessage) {
      msg = options.failureMessage;
      if (typeof msg == 'boolean') {
        msg = challenge.message || challenge;
      }
      if (typeof msg == 'string') {
        req.session.messages = req.session.messages || [];
        req.session.messages.push(msg);
      }
    }
    if (options.failureRedirect) {
      return res.redirect(options.failureRedirect);
    }

    // When failure handling is not delegated to the application, the default
    // is to respond with 401 Unauthorized.  Note that the WWW-Authenticate
    // header will be set according to the strategies in use (see
    // actions#fail).  If multiple strategies failed, each of their challenges
    // will be included in the response.
    var rchallenge = []
      , rstatus, status;

    for (var j = 0, len = failures.length; j < len; j++) {
      failure = failures[j];
      challenge = failure.challenge;
      status = failure.status;

      rstatus = rstatus || status;
      if (typeof challenge == 'string') {
        rchallenge.push(challenge);
      }
    }

    res.statusCode = rstatus || 401;
    if (res.statusCode == 401 && rchallenge.length) {
      res.setHeader('WWW-Authenticate', rchallenge);
    }
    if (options.failWithError) {
      return next(new AuthenticationError(http.STATUS_CODES[res.statusCode], rstatus));
    }
    res.end(http.STATUS_CODES[res.statusCode]);
  }

  (function attempt(i) {
    var layer = name[i];
    // If no more strategies exist in the chain, authentication has failed.
    if (!layer) { return allFailed(); }

    // Get the strategy, which will be used as prototype from which to create
    // a new instance.  Action functions will then be bound to the strategy
    // within the context of the HTTP request/response pair.
    var prototype = passport._strategy(layer);
    if (!prototype) { return next(new Error('Unknown authentication strategy "' + layer + '"')); }

    var strategy = Object.create(prototype);


    // ----- BEGIN STRATEGY AUGMENTATION -----
    // Augment the new strategy instance with action functions.  These action
    // functions are bound via closure the the request/response pair.  The end
    // goal of the strategy is to invoke *one* of these action methods, in
    // order to indicate successful or failed authentication, redirect to a
    // third-party identity provider, etc.

    /**
     * Authenticate 'user', with optional 'info'.
     *
     * Strategies should call this function to successfully authenticate a
     * user.  'user' should be an object supplied by the application after it
     * has been given an opportunity to verify credentials.  'info' is an
     * optional argument containing additional ...
```
- example usage
```shell
...

function setupPasswordAuth() {
  passport.use(new LocalStrategy({
usernameField: 'email'
  }, function (username, password, done) {
console.log('username: %s', username);

User.authenticate(username, password, function (err, user) {
  if (err || !user) {
    console.log('no user');
    return done(null, false, {message: 'Incorrect username.'});
  }

  return done(null, user);
});
...
```

#### <a name="apidoc.element.strider.auth.forgot"></a>[function <span class="apidocSignatureSpan">strider.auth.</span>forgot (req, res)](#apidoc.element.strider.auth.forgot)
- description and source-code
```javascript
function forgot(req, res) {
  var email = req.body.email.toLowerCase();

  User.findOne({email: {$regex: new RegExp(email, 'i')}}, function (error, user) {
    if (error) {
      req.flash('error', 'An error occured while attempting to reset your password.');
      return res.redirect('/forgot');
    }

    if (user) {
      randomBytes(20).then(function (buffer) {
        return buffer.toString('hex');
      }).then(function (token) {
        user.resetPasswordToken = token;
        user.resetPasswordExpires = Date.now() + 3600000; // 1 hour

        return new BluebirdPromise(function (resolve, reject) {
          user.save(function (err, u) {
            if (err) {
              reject(err);
            } else {
              resolve(u);
            }
          });
        });
      }).then(function (user) {
        mailer.sendPasswordReset(user);
        req.flash('info', 'Please check your email for the password reset url. Thank you!');
        res.redirect('/');
      }).catch(function (error) {
        console.error('Password reset error: ', error);
      });
    } else {
      req.flash('error', 'We could not find a user with that email.');
      return res.redirect('/forgot');
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.auth.logout"></a>[function <span class="apidocSignatureSpan">strider.auth.</span>logout (req, res)](#apidoc.element.strider.auth.logout)
- description and source-code
```javascript
function logout(req, res) {
  req.logout();
  res.redirect('/');
}
```
- example usage
```shell
...

var _authenticate = passport.authenticate('local', {
successRedirect: '/',
failureRedirect: '/login?failed=true'
});

function logout(req, res) {
req.logout();
res.redirect('/');
}

function forgot(req, res) {
var email = req.body.email.toLowerCase();

User.findOne({email: {$regex: new RegExp(email, 'i')}}, function (error, user) {
...
```

#### <a name="apidoc.element.strider.auth.requireAdminOr401"></a>[function <span class="apidocSignatureSpan">strider.auth.</span>requireAdminOr401 (req, res, next)](#apidoc.element.strider.auth.requireAdminOr401)
- description and source-code
```javascript
function requireAdminOr401(req, res, next) {
  if (!req.user || !req.user['account_level'] || req.user.account_level < 1) {
    res.status(401).send('not authorized');
  } else {
    next();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.auth.requireProjectAdmin"></a>[function <span class="apidocSignatureSpan">strider.auth.</span>requireProjectAdmin (req, res, next)](#apidoc.element.strider.auth.requireProjectAdmin)
- description and source-code
```javascript
function requireProjectAdmin(req, res, next) {
  if (!req.project) return res.status(404).send('Project not loaded');
  if (!req.user) return res.status(401).send('No user');
  var isAdmin = req.user.account_level && req.user.account_level > 0;
  var notAuthed = (!req.accessLevel || req.accessLevel < 2) && !isAdmin;
  if (notAuthed) return res.status(401).send('Not authorized for configuring this project');
  next();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.auth.requireUser"></a>[function <span class="apidocSignatureSpan">strider.auth.</span>requireUser (req, res, next)](#apidoc.element.strider.auth.requireUser)
- description and source-code
```javascript
function requireUser(req, res, next) {
  if (req.user) {
    next();
  } else {
    req.session.return_to = req.url;
    res.redirect('/login');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.auth.requireUserOr401"></a>[function <span class="apidocSignatureSpan">strider.auth.</span>requireUserOr401 (req, res, next)](#apidoc.element.strider.auth.requireUserOr401)
- description and source-code
```javascript
function requireUserOr401(req, res, next) {
  if (req.user) {
    next();
  } else {
    res.status(401).send('not authorized');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.auth.reset"></a>[function <span class="apidocSignatureSpan">strider.auth.</span>reset (req, res)](#apidoc.element.strider.auth.reset)
- description and source-code
```javascript
function reset(req, res) {
  var token = req.params.token;

  User.findOne({
    resetPasswordToken: token,
    resetPasswordExpires: {$gt: Date.now()}
  }, function (err, user) {
    if (!user) {
      req.flash('error', 'Password reset token is invalid or has expired.');
      return res.redirect('/forgot');
    }

    res.render('reset.html', {
      token: token,
      user: user
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.auth.resetPost"></a>[function <span class="apidocSignatureSpan">strider.auth.</span>resetPost (req, res)](#apidoc.element.strider.auth.resetPost)
- description and source-code
```javascript
function resetPost(req, res) {
  var password = req.body.password;
  var confirmation = req.body.passwordConfirmation;

  if (password === confirmation) {
    User.findOne({
      resetPasswordToken: req.params.token,
      resetPasswordExpires: {$gt: Date.now()}
    }, function (err, user) {
      if (!user) {
        req.flash('error', 'Password reset token is invalid or has expired.');
        return res.redirect('back');
      }

      user.password = password;
      user.resetPasswordToken = undefined;
      user.resetPasswordExpires = undefined;

      user.save(function (err) {
        if (err) {
          req.flash('error', 'Couldn\'t save changes with new password.');
          return res.redirect('/');
        }

        req.login(user, function (err) {
          if (err) {
            req.flash('error', 'You\'r user authentication was not successful.');
          }

          res.redirect('/');
        });
      });
    });
  } else {
    res.redirect(req.header('Referer'));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.auth.setup"></a>[function <span class="apidocSignatureSpan">strider.auth.</span>setup (app)](#apidoc.element.strider.auth.setup)
- description and source-code
```javascript
function setup(app) {
  app.registerAuthStrategy = function (strategy) {
    passport.use(strategy);
  };

  app.authenticate = function () {
    console.log('AUTHENTICATE', arguments);

    var res = passport.authenticate.apply(passport, arguments);
    console.log('!!!', res);

    return function (req) {
      console.log('>>>> AUTHENTICATE', req._passport, req._passport.instance._strategies.github);
      res.apply(this, arguments);
    };
  };

  setupPasswordAuth(app);

  // serialize user on login
  passport.serializeUser(function (user, done) {
    done(null, user.id);
  });

  // deserialize user on logout
  passport.deserializeUser(function (id, done) {
    User.findById(id, function (err, user) {
      done(err, user);
    });
  });

  app.use(passport.initialize());
  app.use(passport.session());
  app.use(basicAuth);

  // Middleware to setup view parameters with user
  app.use(function (req, res, next) {
    if (req.user) {
      req.user.gravatar = utils.gravatar(req.user.email);
    }

    res.locals.currentUser = req.user || null;
    next();
  });

  registerRoutes(app);
}
```
- example usage
```shell
...
app.use(connectFlash());

app.use(function (req, res, next) {
  res.locals.models = models;
  next();
});

auth.setup(app); // app.use(passport) is included

app.use('/vendor', express.static(path.join(__dirname, '..', 'vendor'), {maxAge: MONTH_IN_MILLISECONDS}));
app.use(express.static(path.join(__dirname, '..', 'dist'), {maxAge: MONTH_IN_MILLISECONDS}));
app.use(express.static(path.join(__dirname, '..', 'public'), {maxAge: MONTH_IN_MILLISECONDS}));

if (!config.smtp) {
  debug('No SMTP creds - forgot password flow will not work');
...
```



# <a name="apidoc.module.strider.backchannel"></a>[module strider.backchannel](#apidoc.module.strider.backchannel)

#### <a name="apidoc.element.strider.backchannel.backchannel"></a>[function <span class="apidocSignatureSpan">strider.</span>backchannel (emitter, ws)](#apidoc.element.strider.backchannel.backchannel)
- description and source-code
```javascript
function BackChannel(emitter, ws) {
  this.ws = ws;
  this.users = {};
  this.public = {};
  this.waiting = {};

  emitter.on('job.prepare', prepareJob.bind(null, emitter));
  emitter.on('job.new', this.newJob.bind(this));
  emitter.on('browser.update', this.onUpdate.bind(this));
  emitter.on('job.done', this.jobDone.bind(this, emitter));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.strider.backchannel.prototype"></a>[module strider.backchannel.prototype](#apidoc.module.strider.backchannel.prototype)

#### <a name="apidoc.element.strider.backchannel.prototype.jobDone"></a>[function <span class="apidocSignatureSpan">strider.backchannel.prototype.</span>jobDone (emitter, data)](#apidoc.element.strider.backchannel.prototype.jobDone)
- description and source-code
```javascript
jobDone = function (emitter, data) {
  var self = this;
  Job.findById(data.id, function (err, job) {
    if (err) return debug('Error finding job', err.message);
    if (!job) return debug('job.done but job not found:', data.id);
    _.extend(job, data);
    try {
      job.duration = data.finished.getTime() - data.started.getTime();
    } catch (ignore) {
      job.duration = 1;
    }
    job.markModified('phases');
    job.markModified('plugin_data');
    job.test_exitcode = job.phases.test && job.phases.test.exitCode;
    job.deploy_exitcode = job.phases.deploy && job.phases.deploy.exitCode;
    job.save();
    job = job.toJSON();

    Project.findOne({name: job.project}).lean().exec(function (err, project) {
      if (err) return debug('Error finding project for job', err.message, job.project);
      if (!project) return debug('Project for job.done not found', job.project);

      job.project = utils.sanitizeProject(project);
      job.status = jobs.status(job);
      self.sendJobs(project.name, 'job.done', [job]);
      emitter.emit('job.doneAndSaved', job);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.backchannel.prototype.newJob"></a>[function <span class="apidocSignatureSpan">strider.backchannel.prototype.</span>newJob (job)](#apidoc.element.strider.backchannel.prototype.newJob)
- description and source-code
```javascript
newJob = function (job) {
  debug('new job was created');
  var self = this;
  var name = job.project.name;

  this.waiting[name] = [];
  this.public[name] = job.project.public;

  async.parallel({
    collaborators: function (paraCallback) {
      User.collaborators(name, 0, function (err, users) {
        paraCallback(err, users);
      });
    },

    admins: function (paraCallback) {
      User.admins(paraCallback);
    }
  }, function (err, users) {
    if (err) return debug('new job: Failed to query for users');
    if (!users.collaborators) return debug('new job: no users found');
    self.users[name] = [];

    users.collaborators.forEach(function (user) {
      self.users[name].push(user._id.toString());
    });
    // also send to system admins
    users.admins.forEach(function (user) {
      self.users[name].push(user._id.toString());
    });

    // Admins maybe collaborators, so unique the array
    self.users[name] = _.uniq(self.users[name]);

    var njob = jobs.small(job);

    njob.project = utils.sanitizeProject(job.project);
    self.sendJobs(name, 'job.new', [njob]);

    var waiting = self.waiting[name];
    if (Array.isArray(waiting)) {
      waiting.forEach(function (item) {
        self.send.apply(self, [name].concat(item));
      });
    }
    delete self.waiting[name];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.backchannel.prototype.onUpdate"></a>[function <span class="apidocSignatureSpan">strider.backchannel.prototype.</span>onUpdate (project, event, args)](#apidoc.element.strider.backchannel.prototype.onUpdate)
- description and source-code
```javascript
onUpdate = function (project, event, args) {
  if (this.waiting[project]) {
    return this.waiting[project].push([event, args]);
  }
  this.send(project, event, args);
  if (event === 'job.status.started') {
    Job.findById(args[0], function (err, job) {
      if (err) return debug('[backchannel][job.status.started] error getting job', args[0], err);
      if (!job) return debug('[backchannel][job.status.started] job not found', args[0]);
      job.started = args[1];
      job.save();
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.backchannel.prototype.send"></a>[function <span class="apidocSignatureSpan">strider.backchannel.prototype.</span>send (project, event, args)](#apidoc.element.strider.backchannel.prototype.send)
- description and source-code
```javascript
send = function (project, event, args) {
  if (this.users[project]) {
    this.ws.send(this.users[project], [event, args, 'yours']);
  }
  if (this.public[project]) {
    this.ws.sendPublic(this.users[project], [event, args, 'public']);
  }
}
```
- example usage
```shell
...
    console.error('Invalid auth header');
    return next();
  }

  User.authenticate(plain[0], plain.slice(1).join(':'), function (err, user) {
    if (err || !user) {
      console.log('basic auth: user not found');
      return res.status(401).send('Invalid username/password in basic auth');
    }

    req.user = user;

    return next();
  });
}
...
```

#### <a name="apidoc.element.strider.backchannel.prototype.sendJobs"></a>[function <span class="apidocSignatureSpan">strider.backchannel.prototype.</span>sendJobs (project, event, args)](#apidoc.element.strider.backchannel.prototype.sendJobs)
- description and source-code
```javascript
sendJobs = function (project, event, args) {
  if (this.users[project]) {
    this.ws.sendEach(this.users[project], function (user) {
      return [event, args.map(function (job) {
        job = _.assign({}, job);
        job.project = _.assign({}, job.project);
        job.project.access_level = User.projectAccessLevel(user, job.project);
        return job;
      }), 'yours'];
    });
  }
  if (this.public[project]) {
    this.ws.sendPublic(this.users[project], [event, args.map(function (job) {
      job = _.assign({}, job);
      job.project = _.assign({}, job.project);
      job.project.access_level = 0;
      return job;
    }), 'public']);
  }
}
```
- example usage
```shell
...

// Admins maybe collaborators, so unique the array
self.users[name] = _.uniq(self.users[name]);

var njob = jobs.small(job);

njob.project = utils.sanitizeProject(job.project);
self.sendJobs(name, 'job.new', [njob]);

var waiting = self.waiting[name];
if (Array.isArray(waiting)) {
  waiting.forEach(function (item) {
    self.send.apply(self, [name].concat(item));
  });
}
...
```



# <a name="apidoc.module.strider.email"></a>[module strider.email](#apidoc.module.strider.email)

#### <a name="apidoc.element.strider.email.notifyEmailChange"></a>[function <span class="apidocSignatureSpan">strider.email.</span>notifyEmailChange (user, oldEmail)](#apidoc.element.strider.email.notifyEmailChange)
- description and source-code
```javascript
notifyEmailChange = function (user, oldEmail) {
  var currentTime = new Date();
  var subject = '[STRIDER] - Email Address Change Notification - ${currentTime.getHours()}:${currentTime.getMinutes()}';
  var to = user.email;
  var bodyText = text.notify_email_change({ old_email: oldEmail, user: user });
  var bodyHtml = html.notify_email_change({ old_email: oldEmail, user: user });

  mailer.send(to, subject, bodyText, bodyHtml);
  mailer.send(oldEmail, subject, bodyText, bodyHtml);

  console.log('send email change notification to ${oldEmail} and ${to}');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.email.notifyNewAdmin"></a>[function <span class="apidocSignatureSpan">strider.email.</span>notifyNewAdmin (user, email)](#apidoc.element.strider.email.notifyNewAdmin)
- description and source-code
```javascript
notifyNewAdmin = function (user, email) {
  var currentTime = new Date();
  var subject = '[STRIDER] - New Admin  - ${user} - ${currentTime.getHours()}:${currentTime.getMinutes()}';
  var body = 'Hello Core,\n\nYou have a new admin colleague: ${user}\n\nHopefully this isn't unexpected.\n\nRegards,\n - StriderCD
.com\n   Brilliant Continuous Delivery';

  mailer.send(email, subject, body, body);
  console.log('Sending admin notification for new admin ${user}');
}
```
- example usage
```shell
...
    if (env === 'production') {
      getAdmins(function (err, admins) {
        admins
          .filter(function removeSelf(admin) {
            return admin.email !== user.email;
          })
          .forEach(function notifyAdmin(admin) {
            email.notifyNewAdmin(user, admin.email);
          });
      });
    }

    done(null, num);
  });
}
...
```

#### <a name="apidoc.element.strider.email.notifyPasswordChange"></a>[function <span class="apidocSignatureSpan">strider.email.</span>notifyPasswordChange (user)](#apidoc.element.strider.email.notifyPasswordChange)
- description and source-code
```javascript
notifyPasswordChange = function (user) {
  var currentTime = new Date();
  var subject = '[STRIDER] - Password Change Notification - ${currentTime.getHours()}:${currentTime.getMinutes()}';
  var bodyText = text.notify_password_change();
  var bodyHtml = html.notify_password_change();
  var to = user.email;

  mailer.send(to, subject, bodyText, bodyHtml);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.email.revokeInvite"></a>[function <span class="apidocSignatureSpan">strider.email.</span>revokeInvite (code, email)](#apidoc.element.strider.email.revokeInvite)
- description and source-code
```javascript
revokeInvite = function (code, email) {
  var subject = 'Strider Invitation';
  var bodyHtml = html.revoke_invite({code: code, strider_server_name: config.server_name});
  var bodyText = text.revoke_invite({code: code, strider_server_name: config.server_name});

  mailer.send(email, subject, bodyText, bodyHtml);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.email.sendInvite"></a>[function <span class="apidocSignatureSpan">strider.email.</span>sendInvite (code, email)](#apidoc.element.strider.email.sendInvite)
- description and source-code
```javascript
sendInvite = function (code, email) {
  var subject = 'Strider Invitation';
  var bodyHtml = html.invite({code: code, strider_server_name: config.server_name});
  var bodyText = text.invite({code: code, strider_server_name: config.server_name});

  mailer.send(email, subject, bodyText, bodyHtml);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.email.sendInviteCollaboratorExistingUser"></a>[function <span class="apidocSignatureSpan">strider.email.</span>sendInviteCollaboratorExistingUser (req, email, url)](#apidoc.element.strider.email.sendInviteCollaboratorExistingUser)
- description and source-code
```javascript
sendInviteCollaboratorExistingUser = function (req, email, url) {
  // not actually properly capitalized right now
  var displayName = url.replace(/^.*com\//gi, '');
  var subject = '[STRIDER] Invite to ${displayName}';
  var to = email;
  var pugVariables = {
    inviter: req.user.email,
    display_name: displayName,
    strider_server_name: config.server_name
  };
  var bodyText = text.collaborator_invite_existing_user(pugVariables);
  var bodyHtml = html.collaborator_invite_existing_user(pugVariables);

  mailer.send(to, subject, bodyText, bodyHtml);

  console.log('send collaborator invite to existing user ${email} for ${displayName}');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.email.sendInviteCollaboratorNewUser"></a>[function <span class="apidocSignatureSpan">strider.email.</span>sendInviteCollaboratorNewUser (inviter, email, code, url)](#apidoc.element.strider.email.sendInviteCollaboratorNewUser)
- description and source-code
```javascript
sendInviteCollaboratorNewUser = function (inviter, email, code, url) {
  // not actually properly capitalized right now
  var displayName = url.replace(/^.*com\//gi, '');
  var subject = '[STRIDER] Invite to ${displayName}';
  var to = email;
  var pugVariables = {
    inviter: inviter.email,
    display_name: displayName,
    code: code,
    strider_server_name: config.server_name
  };

  var bodyText = text.collaborator_invite_new_user(pugVariables);
  var bodyHtml = html.collaborator_invite_new_user(pugVariables);

  mailer.send(to, subject, bodyText, bodyHtml);

  console.log('send collaborator invite to new user ${email} for ${displayName}');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.email.sendPasswordReset"></a>[function <span class="apidocSignatureSpan">strider.email.</span>sendPasswordReset (user)](#apidoc.element.strider.email.sendPasswordReset)
- description and source-code
```javascript
sendPasswordReset = function (user) {
  var currentTime = new Date();
  var templateOptions = {
    token: user.resetPasswordToken,
    strider_server_name: config.server_name
  };
  var subject = '[STRIDER] - Password Reset - ${currentTime.getHours()}:${currentTime.getMinutes()}';
  var bodyText = text.send_password_reset(templateOptions);
  var bodyHtml = html.send_password_reset(templateOptions);
  var to = user.email;

  mailer.send(to, subject, bodyText, bodyHtml);
}
```
- example usage
```shell
...
          reject(err);
        } else {
          resolve(u);
        }
      });
    });
  }).then(function (user) {
    mailer.sendPasswordReset(user);
    req.flash('info', 'Please check your email for the password reset url. Thank you!');
    res.redirect('/');
  }).catch(function (error) {
    console.error('Password reset error: ', error);
  });
} else {
  req.flash('error', 'We could not find a user with that email.');
...
```



# <a name="apidoc.module.strider.humane"></a>[module strider.humane](#apidoc.module.strider.humane)

#### <a name="apidoc.element.strider.humane.humaneDate"></a>[function <span class="apidocSignatureSpan">strider.humane.</span>humaneDate (date, compareTo)](#apidoc.element.strider.humane.humaneDate)
- description and source-code
```javascript
function humaneDate(date, compareTo) {
  if (!date) {
    return;
  }

  var lang = {
    ago: 'Ago',
    from: '',
    now: 'Just Now',
    minute: 'Minute',
    minutes: 'Minutes',
    hour: 'Hour',
    hours: 'Hours',
    day: 'Day',
    days: 'Days',
    week: 'Week',
    weeks: 'Weeks',
    month: 'Month',
    months: 'Months',
    year: 'Year',
    years: 'Years'
  };
  var formats = [
    [60, lang.now],
    [3600, lang.minute, lang.minutes, 60], // 60 minutes, 1 minute
    [86400, lang.hour, lang.hours, 3600], // 24 hours, 1 hour
    [604800, lang.day, lang.days, 86400], // 7 days, 1 day
    [2628000, lang.week, lang.weeks, 604800], // ~1 month, 1 week
    [31536000, lang.month, lang.months, 2628000], // 1 year, ~1 month
    [Infinity, lang.year, lang.years, 31536000] // Infinity, 1 year
  ];
  var isString = typeof date == 'string';
  date = isString ?
    new Date(date.replace(/-/g, '/').replace(/[TZ]/g, ' ')) :
    date;

  compareTo = compareTo || new Date;
  var seconds = (compareTo - date +
      (compareTo.getTimezoneOffset() -
        // if we received a GMT time from a string, doesn't include time zone bias
        // if we got a date object, the time zone is built in, we need to remove it.
        (isString ? 0 : date.getTimezoneOffset())
      ) * 60000
    ) / 1000;

  var token;
  if (seconds < 0) {
    seconds = Math.abs(seconds);
    token = lang.from ? ' ${lang.from}' : '';
  } else {
    token = lang.ago ? ' ${lang.ago}' : '';
  }

<span class="apidocCodeCommentSpan">  /*
   * 0 seconds && < 60 seconds        Now
   * 60 seconds                       1 Minute
   * > 60 seconds && < 60 minutes     X Minutes
   * 60 minutes                       1 Hour
   * > 60 minutes && < 24 hours       X Hours
   * 24 hours                         1 Day
   * > 24 hours && < 7 days           X Days
   * 7 days                           1 Week
   * > 7 days && < ~ 1 Month          X Weeks
   * ~ 1 Month                        1 Month
   * > ~ 1 Month && < 1 Year          X Months
   * 1 Year                           1 Year
   * > 1 Year                         X Years
   *
   * Single units are +10%. 1 Year shows first at 1 Year + 10%
   */
</span>
  function normalize(val, single) {
    var margin = 0.1;
    if (val >= single && val <= single * (1 + margin)) {
      return single;
    }
    return val;
  }

  for (var i = 0, format = formats[0]; formats[i]; format = formats[++i]) {
    if (seconds < format[0]) {
      if (i === 0) {
        // Now
        return format[1];
      }

      var val = Math.ceil(normalize(seconds, format[3]) / (format[3]));
      return '${val} ${(val != 1 ? format[2] : format[1])}${(i > 0 ? token : '')}';
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.strider.jobs"></a>[module strider.jobs](#apidoc.module.strider.jobs)

#### <a name="apidoc.element.strider.jobs.jobProject"></a>[function <span class="apidocSignatureSpan">strider.jobs.</span>jobProject (project, prev, user)](#apidoc.element.strider.jobs.jobProject)
- description and source-code
```javascript
function jobProject(project, prev, user) {
  prev.forEach(function (job) {
    job.status = status(job);
  });

  project = utils.sanitizeProject(project);
  project.prev = prev;

  if (user) {
    project.access_level = User.projectAccessLevel(user, project);
  }

  return project;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.jobs.latestJobs"></a>[function <span class="apidocSignatureSpan">strider.jobs.</span>latestJobs (user, small, done)](#apidoc.element.strider.jobs.latestJobs)
- description and source-code
```javascript
function latestJobs(user, small, done) {
  if (arguments.length === 2) {
    done = small;
    small = false;
  }
  var tasks = { public: latestPublicJobs.bind(null, user, small) };
  if (user) {
    tasks.yours = latestUsersJobs.bind(null, user, small);
  }
  async.parallel(tasks, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.jobs.small"></a>[function <span class="apidocSignatureSpan">strider.jobs.</span>small (job)](#apidoc.element.strider.jobs.small)
- description and source-code
```javascript
function small(job) {
  var big = ['phases', 'plugin_data', 'std', 'stderr', 'stdout', 'stdmerged'];
  var njob = {};
  if (job.toJSON) job = job.toJSON();
  for (var name in job) {
    if (big.indexOf(name) !== -1) continue;
    njob[name] = job[name];
  }
  njob.status = status(job);
  return njob;
}
```
- example usage
```shell
...
users.admins.forEach(function (user) {
  self.users[name].push(user._id.toString());
});

// Admins maybe collaborators, so unique the array
self.users[name] = _.uniq(self.users[name]);

var njob = jobs.small(job);

njob.project = utils.sanitizeProject(job.project);
self.sendJobs(name, 'job.new', [njob]);

var waiting = self.waiting[name];
if (Array.isArray(waiting)) {
  waiting.forEach(function (item) {
...
```

#### <a name="apidoc.element.strider.jobs.sort"></a>[function <span class="apidocSignatureSpan">strider.jobs.</span>sort (a, b)](#apidoc.element.strider.jobs.sort)
- description and source-code
```javascript
function jobSort(a, b) {
  if (a.nojobs) {
    if (b.nojobs) return 0;
    return -1;
  }
  if (b.nojobs) return 1;
  if (a.status === 'running') {
    if (b.status === 'running') return 0;
    return -1;
  }
  if (b.status === 'running') return 1;
  if (a.status === 'submitted') {
    if (b.status === 'submitted') return 0;
    return -1;
  }
  if (b.status === 'submitted') return 1;
  if (!a.finished || !a.finished.getTime) return -1;
  if (!b.finished || !b.finished.getTime) return 1;
  return b.finished.getTime() - a.finished.getTime();
}
```
- example usage
```shell
...
}

return project;
}

function latestJob(project, user, small, done) {
var query = Job.find({project: project.name.toLowerCase(), archived: null})
  .sort({finished: -1})
  .limit(6)
  .lean();

if (small) {
  query = query.select('-phases -std');
}
...
```

#### <a name="apidoc.element.strider.jobs.status"></a>[function <span class="apidocSignatureSpan">strider.jobs.</span>status (job)](#apidoc.element.strider.jobs.status)
- description and source-code
```javascript
function status(job) {
  if (job.errored) return 'errored';
  if (!job.started) return 'submitted';
  if (!job.finished) return 'running';
  if (job.test_exitcode !== 0) return 'failed';
  if (job.type !== TEST_ONLY && job.deploy_exitcode !== 0) return 'failed';
  return 'passed';
}
```
- example usage
```shell
...
    console.error('Invalid auth header');
    return next();
  }

  User.authenticate(plain[0], plain.slice(1).join(':'), function (err, user) {
    if (err || !user) {
      console.log('basic auth: user not found');
      return res.status(401).send('Invalid username/password in basic auth');
    }

    req.user = user;

    return next();
  });
}
...
```



# <a name="apidoc.module.strider.libconfig"></a>[module strider.libconfig](#apidoc.module.strider.libconfig)

#### <a name="apidoc.element.strider.libconfig.addPlugins"></a>[function <span class="apidocSignatureSpan">strider.libconfig.</span>addPlugins (rc, env)](#apidoc.element.strider.libconfig.addPlugins)
- description and source-code
```javascript
function addPlugins(rc, env) {
  var parts;
  if (!rc.plugins) rc.plugins = {};
  for (var key in env) {
    if (!key.match(/^plugin_/i)) continue;
    parts = key.toLowerCase().split('_');
    if (parts.length === 2) {
      try {
        rc.plugins[parts[1]] = JSON.parse(env[key]);
      } catch (e) {
        console.warn('Ignoring config because it\'s not valid JSON: ', key, env[key]);
      }
      continue;
    }
    if (!rc.plugins[parts[1]]) rc.plugins[parts[1]] = {};
    rc.plugins[parts[1]][camel(parts.slice(2))] = env[key];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.libconfig.camel"></a>[function <span class="apidocSignatureSpan">strider.libconfig.</span>camel (words)](#apidoc.element.strider.libconfig.camel)
- description and source-code
```javascript
function camel(words) {
  return words[0] + words.slice(1)
    .map(function (word) {
      return word[0].toUpperCase() + word.slice(1);
    }).join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.libconfig.deprecated"></a>[function <span class="apidocSignatureSpan">strider.libconfig.</span>deprecated (env)](#apidoc.element.strider.libconfig.deprecated)
- description and source-code
```javascript
function deprecated(env) {
  var nenv = _.extend({}, env);
  if (env.APP_ID) {
    console.warn('WARNING: You are using APP_ID to configure Github OAuth application id.');
    console.warn('This name has been deprecated. Please use PLUGIN_GITHUB_APP_ID instead.\n');
    nenv.PLUGIN_GITHUB_APP_ID = env.APP_ID;
  }
  if (env.APP_SECRET) {
    console.warn('WARNING: You are using APP_SECRET to configure Github OAuth application secret.');
    console.warn('This name has been deprecated. Please use PLUGIN_GITHUB_APP_SECRET instead.\n');
    nenv.PLUGIN_GITHUB_APP_SECRET = env.APP_SECRET;
  }
  if (env.GITHUB_APP_ID) {
    console.warn('WARNING: You are using GITHUB_APP_ID to configure Github OAuth application id.');
    console.warn('This name has been deprecated. Please use PLUGIN_GITHUB_APP_ID instead.\n');
    nenv.PLUGIN_GITHUB_APP_ID = env.GITHUB_APP_ID;
  }
  if (env.GITHUB_SECRET) {
    console.warn('WARNING: You are using GITHUB_SECRET to configure Github OAuth application secret.');
    console.warn('This name has been deprecated. Please use PLUGIN_GITHUB_APP_SECRET instead.\n');
    nenv.PLUGIN_GITHUB_APP_SECRET = env.GITHUB_SECRET;
  }
  if (env.GITHUB_API_ENDPOINT) {
    console.warn('WARNING: You are using GITHUB_API_ENDPOINT to configure Github API base URL.');
    console.warn('This name has been deprecated. Please use PLUGIN_GITHUB_API_BASE instead.\n');
    nenv.PLUGIN_GITHUB_API_BASE = env.GITHUB_API_ENDPOINT;
  }
  return nenv;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.libconfig.filterEnv"></a>[function <span class="apidocSignatureSpan">strider.libconfig.</span>filterEnv (env, defaults)](#apidoc.element.strider.libconfig.filterEnv)
- description and source-code
```javascript
function filterEnv(env, defaults) {
  var res = {};
  for (var k in env) {
    if (defaults[k.toLowerCase()] !== undefined) {
      res['strider_${k.toLowerCase()}'] = env[k];
    } else {
      res[k] = env[k];
    }
  }
  return res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.libconfig.getConfig"></a>[function <span class="apidocSignatureSpan">strider.libconfig.</span>getConfig ()](#apidoc.element.strider.libconfig.getConfig)
- description and source-code
```javascript
function getConfig() {
  process.env = filterEnv(deprecated(process.env), envDefaults);
  var rc = require('rc')('strider', defaults);

  if (!rc.smtp) rc.smtp = smtp(rc);
  if (!rc.smtp) rc.stubSmtp = true;

  rc.ldap = getConfigByName('ldap');

  addPlugins(rc, process.env);

  // BACK COMPAT until we get strider config into plugins...
  if (hasGithub) {
    rc.plugins.github = rc.plugins.github || {};
    rc.plugins.github.hostname = rc.server_name;
  }

  debug(rc);

  return rc;
}
```
- example usage
```shell
...





'use strict';

module.exports = require('./libconfig').getConfig();
...
```

#### <a name="apidoc.element.strider.libconfig.smtp"></a>[function <span class="apidocSignatureSpan">strider.libconfig.</span>smtp (rc)](#apidoc.element.strider.libconfig.smtp)
- description and source-code
```javascript
function smtp(rc) {
  if (!rc.smtp_host) {
    return;
  }

  var options = {
    host: rc.smtp_host,
    port: rc.smtp_port,
    from: rc.smtp_from,
    secure: rc.smtp_secure
  };

  if (rc.smtp_user) {
    options.auth = {
      user: rc.smtp_user,
      pass: rc.smtp_pass
    };
  }

  return options;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.strider.logging"></a>[module strider.logging](#apidoc.module.strider.logging)

#### <a name="apidoc.element.strider.logging.debug"></a>[function <span class="apidocSignatureSpan">strider.logging.</span>debug (msg)](#apidoc.element.strider.logging.debug)
- description and source-code
```javascript
debug = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
...
// socket callback. Adds a new socket
connected: function (socket) {
  var session = socket.handshake.session;

  if (session && session.passport) {
    this.addSocket(session.passport.user, socket);
  } else {
    console.debug('Websocket connection does not have authorization - nothing to do.');
  }
},
// send a message to a number of users
// send([uid, uid, ...], arguments)
send: function (users, args) {
  for (var i = 0; i < users.length; i++) {
    if (!this.sockets[users[i]]) continue;
...
```

#### <a name="apidoc.element.strider.logging.error"></a>[function <span class="apidocSignatureSpan">strider.logging.</span>error (msg)](#apidoc.element.strider.logging.error)
- description and source-code
```javascript
error = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
...

    loadExtensions(loader, extdir, context, appInstance, function () {
      // kill zombie jobs
      killZombies(function () {
var tasks = [];

if (!common.extensions.runner || typeof common.extensions.runner !== 'object') {
  console.error('Strider seems to have been misconfigured - there are no available runner plugins. ' +
    'Please make sure all dependencies are up to date.');
  process.exit(1);
}

Object.keys(common.extensions.runner).forEach(function (name) {
  var runner = common.extensions.runner[name];
...
```

#### <a name="apidoc.element.strider.logging.info"></a>[function <span class="apidocSignatureSpan">strider.logging.</span>info (msg)](#apidoc.element.strider.logging.info)
- description and source-code
```javascript
info = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.logging.silly"></a>[function <span class="apidocSignatureSpan">strider.logging.</span>silly (msg)](#apidoc.element.strider.logging.silly)
- description and source-code
```javascript
silly = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.logging.verbose"></a>[function <span class="apidocSignatureSpan">strider.logging.</span>verbose (msg)](#apidoc.element.strider.logging.verbose)
- description and source-code
```javascript
verbose = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.logging.warn"></a>[function <span class="apidocSignatureSpan">strider.logging.</span>warn (msg)](#apidoc.element.strider.logging.warn)
- description and source-code
```javascript
warn = function (msg) {
  // build argument list (level, msg, ... [string interpolate], [{metadata}], [callback])
  var args = [level].concat(Array.prototype.slice.call(arguments));
  target.log.apply(target, args);
}
```
- example usage
```shell
...
  for (var key in env) {
    if (!key.match(/^plugin_/i)) continue;
    parts = key.toLowerCase().split('_');
    if (parts.length === 2) {
      try {
        rc.plugins[parts[1]] = JSON.parse(env[key]);
      } catch (e) {
        console.warn('Ignoring config because it\'s not valid JSON: ', key, env[key]);
      }
      continue;
    }
    if (!rc.plugins[parts[1]]) rc.plugins[parts[1]] = {};
    rc.plugins[parts[1]][camel(parts.slice(2))] = env[key];
  }
}
...
```



# <a name="apidoc.module.strider.middleware"></a>[module strider.middleware](#apidoc.module.strider.middleware)

#### <a name="apidoc.element.strider.middleware.anonProject"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>anonProject (req, res, next)](#apidoc.element.strider.middleware.anonProject)
- description and source-code
```javascript
function anonProject(req, res, next) {
  var name = '${req.params.org}/${req.params.repo}';

  name = name.toLowerCase();

  Project.findOne({name: name})
    .populate('creator')
    .exec(function (err, project) {
      if (err) {
        return res.status(500).send({
          error: 'Failed to find project',
          info: err
        });
      }

      if (!project) {
        return res.status(404).send('Project not found');
      }

      if (!project.creator) {
        return res.status(400).send('Project malformed; project creator user is missing.');
      }

      req.project = project;
      req.accessLevel = User.projectAccessLevel(req.user, project);

      if (req.user && project.creator) {
        req.user.isProjectCreator = project.creator._id.toString() === req.user._id.toString();
      }

      next();
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.middleware.bodySetter"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>bodySetter (req, res, next)](#apidoc.element.strider.middleware.bodySetter)
- description and source-code
```javascript
function bodySetter(req, res, next) {
  if (req._post_body) {
    return next();
  }

  req.post_body = req.post_body || '';

  if ('POST' !== req.method) {
    return next();
  }

  req._post_body = true;

  req.on('data', function (chunk) {
    req.post_body += chunk;
  });

  next();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.middleware.custom404"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>custom404 (req, res, next)](#apidoc.element.strider.middleware.custom404)
- description and source-code
```javascript
function custom404(req, res, next) {
  if (req.method !== 'GET') {
    return next();
  }

  res.statusCode = 404;
  res.render('doesnotexist.html');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.middleware.project"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>project (req, res, next)](#apidoc.element.strider.middleware.project)
- description and source-code
```javascript
function project(req, res, next) {
  if (req.params.org === 'auth') {
    return next();
  }

  anonProject(req, res, function () {
    if (req.accessLevel > -1) {
      return next();
    }

    if (!req.user) {
      req.session.return_to = req.url;
      return res.redirect('/login');
    }

    res.status(401).send('Not authorized');
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.middleware.projectPlugin"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>projectPlugin (req, res, next)](#apidoc.element.strider.middleware.projectPlugin)
- description and source-code
```javascript
function projectPlugin(req, res, next) {
  var pluginid;
  // if only 3 args, then get pluginid from params ":plugin"
  if (arguments.length === 4) {
    pluginid = req;
    req = res;
    res = next;
    next = arguments[3];
  } else {
    pluginid = req.params.plugin;
  }

  var branch = req.project.branch(req.query.branch);
  var plugin = null;

  if (!branch) {
    return res.status(404).send('Specified branch not found for the project');
  }
  // if it's just mirroring master
  if (branch.mirror_master) {
    return res.status(400).send('Branch not individually configurable');
  }

  for (var i = 0; i < branch.plugins.length; i++) {
    if (branch.plugins[i].id === pluginid) {
      plugin = branch.plugins[i];
      break;
    }
  }

  if (plugin === null) {
    return res.status(404).send('Plugin not enabled for the specified project');
  }

  req.pluginConfig = function (config, next) {
    if (arguments.length === 0) {
      return plugin.config;
    }

    plugin.config = config;
    req.project.markModified('branches');
    req.project.save(function (err) {
      next(err, config);
    });
  };

  req.userConfig = function (config, next) {
    if (!req.user.isProjectCreator) {
      if (arguments.length === 0) {
        return false;
      }

      return next(new Error('Current user is not the creator - cannot set the creator config'));
    }

    if (arguments.length === 0) {
      return req.project.creator.jobplugins[pluginid];
    }

    var schema = common.userConfigs.job && common.userConfigs.job[pluginid];

    if (!schema) {
      return next(new Error('Plugin ${pluginid} doesn't define any user config'));
    }

    config = utils.validateAgainstSchema(config, schema);
    // TODO: validation
    req.project.creator.jobplugins[pluginid] = config;
    req.project.creator.markModified('jobplugins');

    req.project.creator.save(function (err) {
      next(err, config);
    });
  };

  next();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.middleware.projectProvider"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>projectProvider (req, res, next)](#apidoc.element.strider.middleware.projectProvider)
- description and source-code
```javascript
function projectProvider(req, res, next) {
  var project = req.project;

  req.providerConfig = function (config, next) {
    if (arguments.length === 0) {
      return project.provider.config;
    }

    project.provider.config = config;
    project.markModified('provider');
    project.save(next);
  };
  // make this conditional?
  if (project.provider.account) {
    var account = project.creator.account(project.provider.id, project.provider.account);

    req.accountConfig = function (config, next) {
      if (arguments.length === 0) {
        return account.config;
      }

      account.config = config;
      project.creator.markModified('accounts');
      project.creator.save(next);
    };
  }

  next();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.middleware.requireBody"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>requireBody (paramsList)](#apidoc.element.strider.middleware.requireBody)
- description and source-code
```javascript
function requireBody(paramsList) {
  return function (req, res, next) {
    var errors = [];
    var status = 'ok';

    for (var i = 0; i < paramsList.length; i++) {
      var val = req.body[paramsList[i]];

      if (!val) {
        errors.push('required parameter \'${paramsList[i]}\' not found.');
        status = 'error';
      }
    }

    if (errors.length === 0) {
      next();
    } else {
      return res.status(400).json({
        errors: errors,
        status: status
      });
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.middleware.require_admin"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>require_admin (req, res, next)](#apidoc.element.strider.middleware.require_admin)
- description and source-code
```javascript
function requireAdminOr401(req, res, next) {
  if (!req.user || !req.user['account_level'] || req.user.account_level < 1) {
    res.status(401).send('not authorized');
  } else {
    next();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.middleware.require_auth"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>require_auth (req, res, next)](#apidoc.element.strider.middleware.require_auth)
- description and source-code
```javascript
function requireUserOr401(req, res, next) {
  if (req.user) {
    next();
  } else {
    res.status(401).send('not authorized');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.middleware.require_auth_browser"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>require_auth_browser (req, res, next)](#apidoc.element.strider.middleware.require_auth_browser)
- description and source-code
```javascript
function requireUser(req, res, next) {
  if (req.user) {
    next();
  } else {
    req.session.return_to = req.url;
    res.redirect('/login');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.middleware.require_project_admin"></a>[function <span class="apidocSignatureSpan">strider.middleware.</span>require_project_admin (req, res, next)](#apidoc.element.strider.middleware.require_project_admin)
- description and source-code
```javascript
function requireProjectAdmin(req, res, next) {
  if (!req.project) return res.status(404).send('Project not loaded');
  if (!req.user) return res.status(401).send('No user');
  var isAdmin = req.user.account_level && req.user.account_level > 0;
  var notAuthed = (!req.accessLevel || req.accessLevel < 2) && !isAdmin;
  if (notAuthed) return res.status(401).send('Not authorized for configuring this project');
  next();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.strider.plugin_templates"></a>[module strider.plugin_templates](#apidoc.module.strider.plugin_templates)

#### <a name="apidoc.element.strider.plugin_templates.engine"></a>[function <span class="apidocSignatureSpan">strider.plugin_templates.</span>engine (path, options, fn)](#apidoc.element.strider.plugin_templates.engine)
- description and source-code
```javascript
function engine(path, options, fn) {
  options.filename = path;

  fs.readFile(path, 'utf8', function (err, str) {
    if (err) return fn(err);
    engine.render(str, options, fn);
  });
}
```
- example usage
```shell
...

if (isTest) {
  // awesome view testingness
  require('./views-test')(app);
}

app.set('views', path.join(__dirname, 'views'));
app.engine('html', pluginTemplates.engine);

if (config.cors) {
  app.use(cors(config.cors));
}

app.use(middleware.bodySetter);
// parse application/x-www-form-urlencoded
...
```

#### <a name="apidoc.element.strider.plugin_templates.registerBlock"></a>[function <span class="apidocSignatureSpan">strider.plugin_templates.</span>registerBlock (block, render)](#apidoc.element.strider.plugin_templates.registerBlock)
- description and source-code
```javascript
function registerBlock(block, render) {
  cache[block] = render;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.plugin_templates.registerTemplate"></a>[function <span class="apidocSignatureSpan">strider.plugin_templates.</span>registerTemplate (name, template, dir)](#apidoc.element.strider.plugin_templates.registerTemplate)
- description and source-code
```javascript
function registerTemplate(name, template, dir) {
  cache[name] = function (context, cb) {
    if (/\.html$/.test(template)){
      dir = dir || '.';
      template = fs.readFileSync(path.join(dir, template), 'utf8');
    }

    cb(null, template);
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.strider.projects"></a>[module strider.projects](#apidoc.module.strider.projects)

#### <a name="apidoc.element.strider.projects.allProjects"></a>[function <span class="apidocSignatureSpan">strider.projects.</span>allProjects (done)](#apidoc.element.strider.projects.allProjects)
- description and source-code
```javascript
function allProjects(done) {
  User.find({}, function (err, users) {
    if (err) return done(err);

    Project.find()
      .sort({_id: -1})
      .exec(function (err, projects) {
        if (err) return done(err);
        done(null, projects.map(function (project) {
          project = utils.sanitizeProject(project);
          project.created_date = utils.timeFromId(project._id);
          project.users = [];
          for (var i = 0; i < users.length; i++) {
            if ('undefined' !== typeof users[i].projects[project.name]) {
              project.users.push({
                email: users[i].email,
                access: users[i].projects[project.name]
              });
            }
          }
          return project;
        }));
      });
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.strider.ssh"></a>[module strider.ssh](#apidoc.module.strider.ssh)

#### <a name="apidoc.element.strider.ssh.generateKeyPair"></a>[function <span class="apidocSignatureSpan">strider.ssh.</span>generateKeyPair (comment, callback)](#apidoc.element.strider.ssh.generateKeyPair)
- description and source-code
```javascript
generateKeyPair = function (comment, callback) {
  debug('Generating SSH key pair...');
  try {
    var key = new NodeRSA();
    key.generateKeyPair();
    var privateKeyPem = key.exportKey('pkcs1-private-pem');
    var publicKeyPem = key.exportKey('pkcs1-public-pem');
    var publicKey = sshpk.parseKey(publicKeyPem, 'pem');
    publicKey.comment = comment;

    callback(null, privateKeyPem, publicKey.toString());

  } catch (error) {
    callback(error);
  }
}
```
- example usage
```shell
...
 * @param comment {string} The comment to put on the public key.
 * @param callback
 */
exports.generateKeyPair = function (comment, callback) {
  debug('Generating SSH key pair...');
  try {
var key = new NodeRSA();
key.generateKeyPair();
var privateKeyPem = key.exportKey('pkcs1-private-pem');
var publicKeyPem = key.exportKey('pkcs1-public-pem');
var publicKey = sshpk.parseKey(publicKeyPem, 'pem');
publicKey.comment = comment;

callback(null, privateKeyPem, publicKey.toString());
...
```



# <a name="apidoc.module.strider.swig_filters"></a>[module strider.swig_filters](#apidoc.module.strider.swig_filters)

#### <a name="apidoc.element.strider.swig_filters.scriptjson"></a>[function <span class="apidocSignatureSpan">strider.swig_filters.</span>scriptjson (input)](#apidoc.element.strider.swig_filters.scriptjson)
- description and source-code
```javascript
scriptjson = function (input) {
  return JSON.stringify(input).replace(/<\//g, '<\\/');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.strider.users"></a>[module strider.users](#apidoc.module.strider.users)

#### <a name="apidoc.element.strider.users.makeAdmin"></a>[function <span class="apidocSignatureSpan">strider.users.</span>makeAdmin (user, done)](#apidoc.element.strider.users.makeAdmin)
- description and source-code
```javascript
function makeAdmin(user, done) {
  if (typeof user !== 'string' && user.email) {
    user = user.email;
  }

  User.update({ email: user }, { account_level: 1 }, {}, function (err, num) {
    if (err) return done(err);
    if (!num) return done();

    console.log('Admin status granted to: ${user}');

    // if in production, notify all other admins about new admin
    if (env === 'production') {
      getAdmins(function (err, admins) {
        admins
          .filter(function removeSelf(admin) {
            return admin.email !== user.email;
          })
          .forEach(function notifyAdmin(admin) {
            email.notifyNewAdmin(user, admin.email);
          });
      });
    }

    done(null, num);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.strider.websockets"></a>[module strider.websockets](#apidoc.module.strider.websockets)

#### <a name="apidoc.element.strider.websockets.websockets"></a>[function <span class="apidocSignatureSpan">strider.</span>websockets (sio, sessionStore)](#apidoc.element.strider.websockets.websockets)
- description and source-code
```javascript
function UserSockets(sio, sessionStore) {
  this.sio = sio;
  this.sockets = {};
  this.sessionStore = sessionStore;
  //sio.enable('browser client minification');  // send minified client
  //sio.enable('browser client etag');          // apply etag caching logic based on version number
  //sio.enable('browser client gzip');
  //sio.set('log level', 1);
  //sio.set('authorization', authorize.bind(this, sessionStore))
  sio.use(authorize.bind(this, sessionStore));
  sio.sockets.on('connection', this.connected.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.websockets.init"></a>[function <span class="apidocSignatureSpan">strider.websockets.</span>init (server, sessionStore)](#apidoc.element.strider.websockets.init)
- description and source-code
```javascript
init = function (server, sessionStore) {
  return common.ws = new UserSockets(io.listen(server), sessionStore);
}
```
- example usage
```shell
...
var k;
// override with c
for (k in c) {
  appConfig[k] = c[k];
}

// Initialize the (web) app
var appInstance = app.init(appConfig);
var cb = callback || defaultCallback;

function defaultCallback(err) {
  if (err) {
    throw err;
  }
}
...
```



# <a name="apidoc.module.strider.websockets.prototype"></a>[module strider.websockets.prototype](#apidoc.module.strider.websockets.prototype)

#### <a name="apidoc.element.strider.websockets.prototype.addSocket"></a>[function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>addSocket (uid, socket)](#apidoc.element.strider.websockets.prototype.addSocket)
- description and source-code
```javascript
addSocket = function (uid, socket) {
  if (!this.sockets[uid]) {
    this.sockets[uid] = new UserSocket(uid);
  }
  this.sockets[uid].add(socket);
}
```
- example usage
```shell
...
  return socks.remove(socket);
},
// socket callback. Adds a new socket
connected: function (socket) {
  var session = socket.handshake.session;

  if (session && session.passport) {
    this.addSocket(session.passport.user, socket);
  } else {
    console.debug('Websocket connection does not have authorization - nothing to do.');
  }
},
// send a message to a number of users
// send([uid, uid, ...], arguments)
send: function (users, args) {
...
```

#### <a name="apidoc.element.strider.websockets.prototype.connected"></a>[function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>connected (socket)](#apidoc.element.strider.websockets.prototype.connected)
- description and source-code
```javascript
connected = function (socket) {
  var session = socket.handshake.session;

  if (session && session.passport) {
    this.addSocket(session.passport.user, socket);
  } else {
    console.debug('Websocket connection does not have authorization - nothing to do.');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.websockets.prototype.removeSocket"></a>[function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>removeSocket (uid, socket)](#apidoc.element.strider.websockets.prototype.removeSocket)
- description and source-code
```javascript
removeSocket = function (uid, socket) {
  var socks = this.sockets[uid];
  if (!socks) return false;
  return socks.remove(socket);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.strider.websockets.prototype.send"></a>[function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>send (users, args)](#apidoc.element.strider.websockets.prototype.send)
- description and source-code
```javascript
send = function (users, args) {
  for (var i = 0; i < users.length; i++) {
    if (!this.sockets[users[i]]) continue;
    this.sockets[users[i]].emit(args);
  }
}
```
- example usage
```shell
...
    console.error('Invalid auth header');
    return next();
  }

  User.authenticate(plain[0], plain.slice(1).join(':'), function (err, user) {
    if (err || !user) {
      console.log('basic auth: user not found');
      return res.status(401).send('Invalid username/password in basic auth');
    }

    req.user = user;

    return next();
  });
}
...
```

#### <a name="apidoc.element.strider.websockets.prototype.sendEach"></a>[function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>sendEach (users, fn)](#apidoc.element.strider.websockets.prototype.sendEach)
- description and source-code
```javascript
sendEach = function (users, fn) {
  for (var i = 0; i < users.length; i++) {
    if (!this.sockets[users[i]] || !this.sockets[users[i]].user) continue;
    this.sockets[users[i]].emit(fn(this.sockets[users[i]].user));
  }
}
```
- example usage
```shell
...
  if (this.public[project]) {
    this.ws.sendPublic(this.users[project], [event, args, 'public']);
  }
},

sendJobs: function (project, event, args) {
  if (this.users[project]) {
    this.ws.sendEach(this.users[project], function (user) {
      return [event, args.map(function (job) {
        job = _.assign({}, job);
        job.project = _.assign({}, job.project);
        job.project.access_level = User.projectAccessLevel(user, job.project);
        return job;
      }), 'yours'];
    });
...
```

#### <a name="apidoc.element.strider.websockets.prototype.sendPublic"></a>[function <span class="apidocSignatureSpan">strider.websockets.prototype.</span>sendPublic (users, args)](#apidoc.element.strider.websockets.prototype.sendPublic)
- description and source-code
```javascript
sendPublic = function (users, args) {
  for (var id in this.sockets) {
    if (users.indexOf(id) !== -1) continue;
    this.sockets[id].emit(args);
  }
}
```
- example usage
```shell
...

BackChannel.prototype = {
send: function (project, event, args) {
  if (this.users[project]) {
    this.ws.send(this.users[project], [event, args, 'yours']);
  }
  if (this.public[project]) {
    this.ws.sendPublic(this.users[project], [event, args, 'public']);
  }
},

sendJobs: function (project, event, args) {
  if (this.users[project]) {
    this.ws.sendEach(this.users[project], function (user) {
      return [event, args.map(function (job) {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
