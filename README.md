ohs_client
==========

### Setup

* Install node and place $NODE_HOME/bin on the path

### Install
`npm install -g bower`

`npm install`

`bower install`

### Configure


### Running
To run for development (which does not have minification on the app code and goes straight into watch):

On OSX or Linux
`npm run dev`

On Windows Machines
`npm run windev`

To prepare for deployment (minifies app code and does not start watch after the build process):

`npm run deploy`

Port can be set via

`export PORT=XXXX`

or in the command line

`node app.js PORT`

Command line port setting takes precedence over setting the environment variable.
Default port is 3000
