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