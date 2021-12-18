#README

## Library

```sh
npm install nodemon --save-dev
npm install eslint --save-dev

npx eslint --init
```

## Package

```json
    "scripts": {
      "start": "nodemon server.js",
      "lint": "eslint ./"
    },
```

## Run Server

```
npm run start
npm run lint
```

## Git

```
git config --global user.name "Trisna Gelar"
git config --global user.email "trisgelar@gmail.com"
git config --global core.autocrlf true

git remote add origin https://github.com/trisgelar/notes-app-back-end.git
git branch -M main
git push -u origin main
```
