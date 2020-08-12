# React


### Bookmark
1. [Official Tutorial](https://reactjs.org/tutorial/tutorial.html)
2. [Official Redux Document in Chinese](https://cn.redux.js.org/)
3. [Create react app tutorial](https://create-react-app.dev/docs/getting-started)
4. [React Hooks 入门教程](https://www.ruanyifeng.com/blog/2019/09/react-hooks.html)
5. [React Hooks 2](https://fenews.org/posts/getting-started-with-react-hooks/)
6. [React Environment Variable](https://medium.com/@trekinbami/using-environment-variables-in-react-6b0a99d83cf5)
7. [Fetch Data in React](https://pusher.com/tutorials/consume-restful-api-react)

### High Priority
1. [React OAuth document with example](https://medium.com/@franciscopa91/how-to-implement-oidc-authentication-with-react-context-api-and-react-router-205e13f2d49)
2. [npm module for React OAuth](https://www.npmjs.com/package/react-openidconnect)
3. [Auth0 & Elastic Search](https://medium.appbase.io/how-to-implement-authentication-for-your-react-app-cf09eef3bb0b1)
4. [Fetch COVID 19 data in React](https://medium.com/analytics-vidhya/fetching-covid-19-data-using-react-js-material-ui-and-material-table-part-2-8a1f88a954ba)
5. [Material UI table](https://material-table.com/#/)
6. [React OAuth document with Redux](https://difi.github.io/felleslosninger/oidc_sample_react.html)
7. [npm module for React OAuth]( https://www.npmjs.com/package/client-oauth2)
8. [React native applications with OAuth](https://scotch.io/tutorials/build-a-react-native-app-and-authenticate-with-oauth-20)

### Knowledge
1. [Function vs class component](https://reactjs.org/docs/components-and-props.html)
2. [How to pass props throug router](https://tylermcginnis.com/react-router-pass-props-to-components/)


### Bookmark for Authentication
Name | URL
--- | ---
Get parameter in OAuth flow | https://auth0.com/docs/api-auth/tutorials/implicit-grant
Property spread notation | https://stackoverflow.com/questions/31048953/what-do-these-three-dots-in-react-do

### Bookmark
Name | URL  
--- | ---
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
SSR (Server Side Reandering) | https://nextjs.org/
build and deployment | https://www.freecodecamp.org/news/how-to-set-up-deploy-your-react-app-from-scratch-using-webpack-and-babel-a669891033d4/
public reactjs server | https://blog.bitsrc.io/8-react-application-deployment-and-hosting-options-for-2019-ab4d668309fd
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
covid 19 - 1 | https://medium.com/@zudemwango/fetching-covid-19-data-using-react-js-material-ui-and-material-table-d41314706b59
covid 19 - 2 | https://medium.com/analytics-vidhya/fetching-covid-19-data-using-react-js-material-ui-and-material-table-part-2-8a1f88a954ba
parameter passing | https://medium.com/@cristi.nord/props-and-how-to-pass-props-to-components-in-react-part-1-b4c257381654
React CSS | https://blog.logrocket.com/the-best-styling-in-react-tutorial-youve-ever-seen-676f1284b945/#:~:text=Sharing%20styles%20across%20many%20React,styles%20reusable%20across%20multiple%20components.


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

