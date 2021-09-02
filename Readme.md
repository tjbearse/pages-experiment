
==static content==

==jekyll==
[Jekyll](https://jekyllrb.com/) can generate static sites and is supported by github pages

0. copy docker-compose and _setup.sh
0. run ./_setup.sh to get a jekyll quickstart (`docker-compose run jekyll jekyll new . --force`)
0. `docker-compose up` to run locally

additional configuration of jekyll (_config.yml) needed?
https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll

==gh-pages==
For publishing built content to github pages, e.g. webapp builds

0. setup github pages to use gh-pages branch
0. build some content into the build folder (fake-build used here)
0. `npm run pages` to copy the build folder into a gh-pages branch and push it
