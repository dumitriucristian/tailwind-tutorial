#setting new project
#install tailwind
```npm init -y //create package.json``` 
```npm install tailwindcss //install tailwind```
```npm install tailwindcsss postcss-cli```
```npm install tailwindcss autoprefixer```
#configure npx
```npx tailwind init```
#create a postcss.config.js file that will tell us what module we want to export
#create file css/tailwind.css
#edit package.json file to create build folder
 "scripts": {
    "build": "postcss css/tailwind.css -o public/build/tailwind.css"
  },
#create public.index.html
#install live server from npm
```npm install -g live-server```
#set powershel script execution on windows
```Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted -Force;```
#run live sever
```line-server public```
#respnsove, hover, focus, responsive, active
Edit the variants section from tailwind.config.js  to obtain hover efects
