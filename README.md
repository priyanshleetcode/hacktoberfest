# hacktoberfest
this is the repository to make a small http local server


Installation:
Running on-demand:
Using npx you can run the script without installing it first:

npx http-server [path] [options]
Globally via npm
```
npm install --global http-server
```
This will install http-server globally so that it may be run from the command line anywhere.

Globally via Homebrew
brew install http-server
As a dependency in your npm package:
npm install http-server
Usage:
 http-server [path] [options]
[path] defaults to ./public if the folder exists, and ./ otherwise.

Now you can visit http://localhost:8080 to view your server

Note: Caching is on by default. Add -c-1 as an option to disable caching.
