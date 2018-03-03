# BitarHW2_WebAPI
the server can be ran by heroku locally or by node locally.
cannot deploy this to heroku for some reason, cannot figure out why, the build log on heroku says there is in error with the npm prune

here is the log:-

-----> Node.js app detected
-----> Creating runtime environment
       
       NPM_CONFIG_LOGLEVEL=error
       NODE_VERBOSE=false
       NODE_ENV=production
       NODE_MODULES_CACHE=true
-----> Installing binaries
       engines.node (package.json):  unspecified
       engines.npm (package.json):   unspecified (use default)
       
       Resolving node version 8.x...
       Downloading and installing node 8.9.4...
       Using default npm version: 5.6.0
-----> Restoring cache
       Skipping cache restore (not-found)
-----> Building dependencies
       Installing node modules (package.json + package-lock)
       added 54 packages in 1.554s
-----> Caching build
       Clearing previous node cache
       Saving 2 cacheDirectories (default):
       - node_modules
       - bower_components (nothing to cache)
-----> Pruning devDependencies
       Skipping because npm 5.6.0 sometimes fails when running 'npm prune' due to a known issue
       https://github.com/npm/npm/issues/19356
       
       You can silence this warning by updating to at least npm 5.7.1 in your package.json
       https://devcenter.heroku.com/articles/nodejs-support#specifying-an-npm-version
-----> Build succeeded!
-----> Discovering process types
       Procfile declares types -> web
-----> Compressing...
       Done: 17.8M
-----> Launching...
       Released v3
       https://bitarhw2.herokuapp.com/ deployed to Heroku
