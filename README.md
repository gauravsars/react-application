commit-001:

steps for setting up react project using vite-js:
-download npm after that open folder in vs-code. Now run the below command to download vite-js.

npm create vite@latest ems-frontend

Scaffolding project in C:\react-app\react-application\ems-frontend...

Done. Now run:

  cd ems-frontend
  npm install    -->creates folder node_modules , updates the dependencies in package.json and downloads and stores these dependencies in node_modules folder. 
  npm run dev  --> starts the server.
  
  
  changes done :
  change port --> In vite.config-js update port 
  
  server: {
	port : 3000
  }
