# ReactJS

### Bookmark
Name | URL  
--- | ---
ReactJS Basic 1 | https://www.w3schools.com/react/default.asp
ReactJS Basic 2 | https://www.tutorialspoint.com/reactjs/index.htm
ReactJS Basic 3 | https://www.taniarascia.com/getting-started-with-react/
ReactJS Basic Youtube | https://youtu.be/Ke90Tje7VS0
ReactJS 101 (in Chinese) | https://www.bookstack.cn/read/reactjs101-zh-tw/README.md
Basic Auth | https://medium.com/technoetics/create-basic-login-forms-using-create-react-app-module-in-reactjs-511b9790dede
Auth0 Example | https://medium.appbase.io/how-to-implement-authentication-for-your-react-app-cf09eef3bb0b
Material UI | https://material-ui.com
Material Video | https://www.youtube.com/watch?v=xm4LX5fJKZ8&t=329s
Online Editor | https://codesandbox.io/
Cluster | ???
SSR (Server Side Reandering) | https://nextjs.org/
build and deployment | https://www.freecodecamp.org/news/how-to-set-up-deploy-your-react-app-from-scratch-using-webpack-and-babel-a669891033d4/
public reactjs server | https://blog.bitsrc.io/8-react-application-deployment-and-hosting-options-for-2019-ab4d668309fd
Create react app | https://create-react-app.dev/docs/getting-started
Routing | https://codeburst.io/getting-started-with-react-router-5c978f70df91
CRUD | https://dzone.com/articles/consuming-rest-api-with-reactjs
CRUID Video | https://www.youtube.com/watch?v=eDomZxzi19Y&t=389s
Debug | https://codeburst.io/how-to-fetch-data-from-an-api-with-react-hooks-9e7202b8afcd
Fetch Data | https://medium.com/better-programming/how-to-fetch-data-from-an-api-with-react-hooks-9e7202b8afcd

### Setup develop environment
1. Install Node.js from https://nodejs.org/en/download/ (we just need  this for npm, we don't need nodejs)
2. Install VSCode and two plugins
    1. Simple React Snippets (Author: Burke Holland)
    2. Prettier - Code formatter (Author: Esben Petersen)
3. Go to preference --> settings to enable "format on save"    
4. npm install -g create-react-app@1.5.2 (install "create-react-app" module,  one time per server, -g means global)
5. npx create-react-app myfirstreact (this step will create a myfirstreact folder)   
   ---  If there is no public folder get generated, please run "npm rm -g create-react-app"     
6. cd myfirstreact 
7. npm start
8. home page shows up at http://localhost:3000/

### Deploy to Apache
1. Add context (ex: /xxx) path to "package.json" (add "homepage":"/xxx/" to package.json OR add "homepage":"." to package.json for any folder)
2. Create production build by "npm run build"
3. Copy the content of build folder to /htdocs/xxx/

### Debug
1. <div>{JSON.stringify(planets)}</div>

### Feedback 
1. All pages will be rendered on client side, but it can be renedered on server side by using nextjs.
2. There is no need to use .jsx as file extension, js is fine. http://babeljs.io/repl page can convert jsx to typical javascript
3. Function in javascript is the first method of class, so reference to function is actually a reference to object.

### Auth0 authentication
1. Registeration Information:    
     * Use google account to log in   
     * TENANT DOMAIN: dev-william.auth0.com   
     * App name: MyFirstAuth0App
     * Client ID: pt1y4xhB5TSfyEzXIFQIWITU35gGx21R
2. auth dashboard URL: https://manage.auth0.com/dashboard/us/dev-william/ 

