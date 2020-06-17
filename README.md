# LachiesTypeScript_Todo
This is Lachies template for the TS todo list
//// when webpack gets booted with the update do this...

.////this will force it to use the bash

npm config set script-shell "C:\\Program Files\\Git\\bin\\bash.exe"


//then you haev to manually update the webpack for some reason it won;t do this on its own... 

npm install --save-dev concurrently live-server npx ts-loader typescript webpack webpack-cli webpack-node-externals

then make sure the updated JSON files checks your html and cSS

"serve": "npx live-server --watch=./dist,index.html,style.css --entry-file=./index.html"
