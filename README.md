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

## Install Node GCE

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
nvm install v14.18.0

npm install -g pm2
pm2 start npm --name "notes-api" -- run "start-prod"
pm2 restart notes-api
pm2 stop notes-api
pm2 start notes-api
```
