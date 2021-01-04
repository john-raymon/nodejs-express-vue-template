# MEVN boilerplate. 

How to get it running:

Create an .env file with the keys from .env.example, create a secret key (for password encrypting purposes) and make sure the MongoDB URI works accordingly.
- then run the install script commands to install the server-side npm dependencies and client/ npm dependencies listed in the package.json files.

Run the script below to quickly install all dependencies and run both the Vue.js front-end dev-server and Node.js/Express.js back-end in a dev. mode.

```
yarn install && yarn --cwd client install && yarn dev-start
```
