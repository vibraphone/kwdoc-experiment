# SENSEI in situ

https://vibraphone.github.io/kwdoc-experiment/

This repository holds static web pages for SENSEI.
It should eventually be merged with the actual sensei repository.
Before you push commits to this repository, you should:

```sh
# Update dependencies from package.json:
npm install

# Verify that the documentation is built properly:
npm run doc:www
# Now visit http://127.0.0.1:4000/kwdoc-experiment and check it out.

# "Publish" the documentation
# This rewrites the gh-pages branch and pushes it:
npm run doc:publish
```

The content in the documentation directory is assembled
into static content and served using hexo when testing locally.
