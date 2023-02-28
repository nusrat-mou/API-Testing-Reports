#For Installation
- Install node.js and set in on the environment
- Install Newman --> Go to command prompt and type: npm install -g newman
Newman 
Install Command: npm install -g newman
Run Command: 
- newman run “Path/CollectionName.json” -e Path/EnvironmentName.json
- newman run “Collection Link” -e “Path”/EnvironmentName.json

Report: 
Install:
- npm install -g newman-reporter-html
- npm install -g newman-reporter-htmlextra
	
	
	
	
	
Run Command: 
- newman run “Collection Link” -e EnvironmentName.json -r cli,html
- newman run “Collection Link” -e EnvironmentName.json -r cli,htmlextra

***To see the newman report,you have to download the .html files or you can see from the image file that have been added in the newman folder***


