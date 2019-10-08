Workaround for Bug #1

This folder has been created as temporary Workaround for Bug #1, which prevents replacing the background image on the main site.

In order to set up the build environment, the server is executing 'npm install'. Unfortunately, this script will forcefully overwrite the background image bg-jumbotron.jpg as well. 

As a workaround, we will need to copy all files that would be replaced by npm install into this folder, and manually overwrite these in the build script. On the long term, there should be an option to manually specify the path to the figure resp. to prevent such a situation.
