#### Setup Steps:
* Clone the directory to your machine, cd into it
* Make sure your machine has `node` and `npm` installed
* Run `npm install` in your console
* Run `npm run start`
* To see tests, run `npm test` in your console . These will be based off snapshots saved in **/lib/web/__tests__/__snapshots__**, if they are outdated, blank the file and re-run to create fresh snapshots. If the change is expected you can invoke Jest with `npm test -- -u` to overwrite the existing snapshot.

#### Tech Used:
* React: Front-end rendering
* Node: Sprucing up the server
* Webpack: Hot reloading
* Axios: API requests
* API Cache: Node module that allows to cache responses for a certain amount of time
* Babel: In order to compile and write the front-end in ES6
* Jest: For React testing, in confjunction with React Test Renderer

#### About the Application
