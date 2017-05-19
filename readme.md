#### Deployment instructions
https://www.polymer-project.org/1.0/start/toolbox/deploy
https://youtu.be/ByV3MWTa1fw | https://www.youtube.com/watch?v=ByV3MWTa1fw&list=PLOU2XLYxmsII5c3Mgw6fNYCzaWrsM3sMN&index=1
- polymer.json
- package.json
- gulpfile.js
- `npm install gulp` then `npm run build` or `gulp`
- For error debugging, run `polymer build -v`
- Test build with serve command: `polymer serve build/bundled -p 8081`
https://github.com/PolymerElements/generator-polymer-init-custom-build

#### Licence source
http://softwareengineering.stackexchange.com/a/68150

#### Backup instructions
Github backup instructions are at Dropbox/CodeBase/Automation/Shell/GitBackup.sh
(at bottom of page — currently labeled ITEM 4)

#### Polymer lint command
```
polymer lint --verbose --input src/app-main/app-main.html
polymer lint --help
polymer lint --verbose
```
"lint": { "rules": ["polymer-1", polymer-2", polymer-2-hybrid", ] }


#### Cloning a github repo
https://github.com/Polymer/shop
```
# Using CLI
mkdir shop
cd shop
polymer init shop

# Or cloning direct from GitHub
git clone https://github.com/Polymer/shop.git
cd shop
bower install
```

## Version History

### v01
1. Forked emna/v15
2. Created MVP (minimum viable product) for deployment and beta test release
3. TODO:
   a. Replace iron-data-table with Vaadin Grid 2.x -- for
	    1. CRUD and
			2. data refreshing
	 b. Improve UX
	    1. Minimize clicks
			2. More logical navigation layout
			
### v02
1. Extended swap/v01
2. Began experimenting with dashboard components
3. TODO:
   a. Improve UX
	 b. Improve navigation experience
	 c. Leverage other apps
	    1. Home Assistant | https://home-assistant.io/demo/ | https://github.com/home-assistant/home-assistant-polymer
			2. Polymer Admin | https://polymer-admin.firebaseapp.com/ | https://github.com/akveo/polymer-admin
			3. FitBit | https://www.microsoft.com/en-us/store/p/fitbit/9wzdncrfj1xx#
   d. Begin with PSK-2
	 e. Add dashboard components, paper drawer panel, minimizer, as described
	 f. Fix build error by starting with PSK-2 (zero build errors) and building incrementally