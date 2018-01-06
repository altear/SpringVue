# Web Application Using Spring Boot and Vue (and maybe a little bit of POSTGRES)

[Tutorial Source](https://randyyaj.github.io/post/20161129_vue_spring/)

## Install Vue for first time on server
Must have
- npm
```
npm install vue
npm install --global vue-cli
```

## Project Setup
```
cd app
vue init webpack frontend
cd frontend

#Install all dependencies
npm install

#Create a pom.xml file
touch pom.xml

#Run front end app on node server localhost:8080
npm run dev
```
