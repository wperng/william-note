# ReactJS

### High Priority
1. Login: https://medium.com/better-programming/building-secure-login-flow-with-oauth-2-openid-in-react-apps-ce6e8e29630a
2. Login: https://medium.appbase.io/how-to-implement-authentication-for-your-react-app-cf09eef3bb0b
2. Login Module: https://www.npmjs.com/package/react-openidconnect
2. Table: https://medium.com/analytics-vidhya/fetching-covid-19-data-using-react-js-material-ui-and-material-table-part-2-8a1f88a954ba
3. Table component: https://material-table.com/#/

### Bookmark
Name | URL  
--- | ---
Good | https://reactjs.org/docs/components-and-props.html
How to pass props throug router | https://tylermcginnis.com/react-router-pass-props-to-components/
Oauth Module | https://www.npmjs.com/package/client-oauth2, https://scotch.io/tutorials/build-a-react-native-app-and-authenticate-with-oauth-20
Official Tutorial | https://reactjs.org/tutorial/tutorial.html
Basic Tutorial | https://www.robinwieruch.de/react-function-component#react-function-component-example
ReactJS Basic 1 | https://www.w3schools.com/react/default.asp
ReactJS Basic 2 | https://www.tutorialspoint.com/reactjs/index.htm
ReactJS Basic 3 | https://www.taniarascia.com/getting-started-with-react/
ReactJS Basic Youtube | https://youtu.be/Ke90Tje7VS0
*ReactJS Component | https://www.freecodecamp.org/news/how-to-write-your-first-react-js-component-d728d759cabc/ <BR/> https://www.taniarascia.com/getting-started-with-react/
ReactJS Chrome Plugin | https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi
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
Router | https://reacttraining.com/react-router/web/example/basic
CRUD | https://dzone.com/articles/consuming-rest-api-with-reactjs
CRUID Video | https://www.youtube.com/watch?v=eDomZxzi19Y&t=389s
Debug | https://codeburst.io/how-to-fetch-data-from-an-api-with-react-hooks-9e7202b8afcd
Fetch Data | https://medium.com/better-programming/how-to-fetch-data-from-an-api-with-react-hooks-9e7202b8afcd
Route | https://www.youtube.com/watch?v=Law7wfdg_ls
Route | https://www.youtube.com/watch?v=XRfD8xIOroA
Route | https://learnwithparam.com/blog/how-to-pass-props-in-react-router/
Authentication Login | https://www.youtube.com/watch?v=Y0-qdp-XBJg
Mutiple Step Form | https://www.youtube.com/watch?v=zT62eVxShsY&t=1924s
OAuth | https://medium.com/better-programming/building-secure-login-flow-with-oauth-2-openid-in-react-apps-ce6e8e29630a
OpenID Connector | https://www.npmjs.com/package/react-openidconnect
covid 19 - 1 | https://medium.com/@zudemwango/fetching-covid-19-data-using-react-js-material-ui-and-material-table-d41314706b59
covid 19 - 2 | https://medium.com/analytics-vidhya/fetching-covid-19-data-using-react-js-material-ui-and-material-table-part-2-8a1f88a954ba
parameter passing | https://medium.com/@cristi.nord/props-and-how-to-pass-props-to-components-in-react-part-1-b4c257381654


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
7. (optional for just download from git) npm install
8. npm start
9. home page shows up at http://localhost:3000/

### Deploy to Apache
1. Add context (ex: /xxx) path to "package.json" (add "homepage":"/xxx/" to package.json OR add "homepage":"." to package.json for any folder)
2. Create production build by "npm run build" (You may need to run "npm install" first)
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

