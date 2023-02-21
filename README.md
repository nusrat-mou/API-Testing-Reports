******For Installation*******
1. Install node.js and set in on the environment
2. Install Newman --> Go to command prompt and type: npm install -g newman
Newman 
Install Command: npm install -g newman
Run Command: 
1. newman run “Path/CollectionName.json” -e Path/EnvironmentName.json
2. newman run “Collection Link” -e “Path”/EnvironmentName.json

Report: 
Install:
1. npm install -g newman-reporter-html
2. npm install -g newman-reporter-htmlextra
	
	
	
	
	
Run Command: 
1. newman run “Collection Link” -e EnvironmentName.json -r cli,html
2. newman run “Collection Link” -e EnvironmentName.json -r cli,htmlextra

