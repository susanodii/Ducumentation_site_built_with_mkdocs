<h1> Deploying your docs</h1>
---


A basic guide to deploying your docs to various hosting providers

### GitHub Pages

If you host the source code for a project on GitHub, you can easily use GitHub Pages to host the documentation for your project. After you checkout the primary working branch (usually master) of the git repository where you maintain the source documentation for your project, run the following command:

```
mkdocs gh-deploy --clean
```

That's it! Behind the scenes, MkDocs will build your docs and use the ghp-import tool to commit them to the gh-pages branch and push the gh-pages branch to GitHub.


Use mkdocs gh-deploy --help to get a full list of options available for the gh-deploy command.

Be aware that you will not be able to review the built site before it is pushed to GitHub. Therefore, you may want to verify any changes you make to the docs beforehand by using the build or serve commands and reviewing the built files locally.
