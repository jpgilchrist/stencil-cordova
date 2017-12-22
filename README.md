# stencil-cordova
my attempt to use cordova and stencil... together.

I ran `cordova create` and cloned the stencil-starter and did a manual "merge" of the two folders... i.e., updated the `package.json`, copied files from stencil-starter to the cordova project... etc.


What I tried:
- `npm install`
- `npm run build` which generates the `www/` folder
- `cordova run android`
- This obviously renders the first page as it is all inline, but inspecting with chrome://inspect shows that none of the app.###.js files are loaded and they aren't found in the sources (dev tools)
- the assets are in the `platforms/android/assets/www` folder... 
