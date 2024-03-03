 *******************************************************************************
 *******************************************************************************
commit - 001 : project setup.

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
  
  *****************************************************************************
  *****************************************************************************
  
  commit - 002: project structure
  
  we have config.js [ we can configure plugins , currently it has plugins: [react()]==> ?
  
  In typical react application we can find only one file index.html file--> points to the main.jsx file.
  main.jsx file is the entry point for all the java script code.
  
  Below code is responsible to render top level component in a div. Here App is the root level component. ==> ?.
  ReactDOM.createRoot(document.getElementById('root')).render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
)
If you go in the file App.jsx , you will find the base level or root component.
  function App() {
  const [count, setCount] = useState(0)
  
  clearing App.jsx, App.css , index.css. 
  
  commit - 002 : Project structure ,  Installing react developer toolkit extension and creating a new HelloWorld.jsx component and importing it as default component under App Component. ( Like how do we create a component).

  ***************************************************************************
  ***************************************************************************
  commit- 003 
  download bootstrap package using command npm install bootstrap --save. 
  Import the bootstrap library in main.jsx import 'bootstrap/dist/css/bootstrap.min.css
  Use bootstrap class in HelloWorld.jsx component. return <h1 className = "text-center"> Hello World ! </h1>


  ***************************************************************************
  ***************************************************************************
  
  
  
