#Front End Engineering Notes
##October 13, 2015

####Install fest
 - Install nvm: `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.29.0/install.sh | bash`
  - check: `which nvm`
 - Use nvm to install node: `nvm install stable`
  - check: `which node`
 - Use npm to install serve: `npm install -g serve`
  - check: `which serve`

####Serve
 - cd to the directory where you have your index.html file
 - run `serve` in the terminal
 - go to `localhost:3000` in your browswer
 - voila - a website!
 - to get to it on another device on the network, go into system preferences-> network to find your ip address
 - on another device on the network, go to http://<ip address>:3000
