# node-todo-cicd
```
sudo apt install nodejs
```
```
sudo apt install npm
```
```
npm install
```
```
node app.js
```

## To run locally
make sure you have node installed already

from your terminal cd into the project folder
```
run npm install
```
```
run node app.js
```
the app will be running on http://localhost:8000

## To run the app locally and in the background 

download pm2

in the home directory of your terminal run `npm install pm2 -g`

from your terminal cd into the project folder

run `npm install` if you have not already 

run `pm2 start app.js` to start the app

the app will be running in the background on http://localhost:8000

run `pm2 stop app.js` to stop the app
