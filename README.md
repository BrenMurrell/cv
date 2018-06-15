# My CV site

Welcome to my (in progress) CV / portfolio site. The source code for this site
is kept in a private repo on Bitbucket

## Deploying (Own notes)

This code lives in the /dist folder of the main repo after compiling. To deploy to gh pages:

* On first run in new environment, setup subtree (if not done already) `git remote add github https://github.com/BrenMurrell/cv.git`
* Compile the code `gulp compile`
* Push to gh-pages with `git subtree push --prefix dist github gh-pages`
* Check out [live site](https://brenmurrell.github.io/cv)
