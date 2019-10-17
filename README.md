## Getting started


```bash
npm install && hugo server
```

When changing stylsheets: npm run production to just recompile stylesheets

Update  "eclipsefdn-hugo-solstice-theme": "0.0.34" in package.json when some features are missing. 

## Extending the site

1. Clone out the repository and perform the changes on your local copy
2. Test your changes (using e.g. "hugo server")
3. On success, commit and push you changes to the master branch
4. Wait for the build to finish (approx. 1 minute). Click here to check the pipelines resp. if they have passed or failed with errors: https://gitlab.idial.institute/panorama.project/website/pipelines
5. After the build has finished, please check on the staging environment if the page is displayed correctly: https://gitlab-pages.idial.institute/panorama.project/website/
6. If you find any issues, go back to 1.
7. In case the page is as you expect it to look, feel free to deploy it using the "deploy_productive" button.