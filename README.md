### Installation:

To create a new project using Developer 715, simply run the following command:
```
npx Developer 715@latest
// For yarn 
yarn exec Developer 715
```

How to run project 
```
npm run Developer 715   // Project Back End Will Run @3000
npm run dev    // Complete Project Will Run @3001

// For yarn 
yarn run Developer 715
yarn run dev
```

How create Model
```
npm run create:model YourModelName
// For yarn 
yarn run create:model YourModelName
```

How create Controller
```
npm run create:controller YourControllerName
// For yarn 
yarn run create:controller YourControllerName
```

How create Middleware
```
npm run create:middleware YourMiddlewareName
// For yarn 
yarn run create:middleware YourMiddlewareName
```

How create Page
```
npm run create:page YourPageName
// For yarn 
yarn run create:page YourPageName
```

How create Component
```
npm run create:component YourComponentName
// For yarn 
yarn run create:component YourComponentName
```

How create Loader
```
npm run create:loader YourLoaderName
// For yarn 
yarn run create:loader YourLoaderName
```

How create Layout
```
npm run create:layout YourLayoutName
// For yarn
yarn run create:layout YourLayoutName
```




Project Structure 

```php
Developer 715/
│
├── app/                                      
│   ├── config/                                 
│   │   ├── cli.js
│   │   ├── config.js
│   │
│   ├── controllers
│   │   ├── todoController.js
│   │
│   ├── middlewares
│   │   ├── authMiddleware.js
│   │
│   ├── models
│   │   ├── todosModel.js
│   │
│   ├── storage/
│   │
│   ├── utility/
│   │   ├── emailUtility.js
│   │   ├── tokenUtility.js
│   │   ├── validationUtility.js
│   │
│   ├── dist/
│   │
│   ├── node_modules/
│   │
│   ├── public/
│   │
│   ├── routes/
│   │   ├── api.js
│   │   ├── web.jsx
│   │
│   ├── views/
│   │   ├── assets/
│   │   │   ├── css/
│   │   │   │    ├── style.js
│   │     
│   │   ├── components/
│   │   │   ├── CreateForm.jsx
│   │   │   ├── List.jsx 
│   │   
│   │   ├── layout/
│   │   │   ├── AppLayout.jsx
│   │   │
│   │   
│   │   ├── loader/
│   │   │   ├── ListLoader.jsx
│   │   │ 
│   │   ├── pages/
│   │   │   ├── CreatePage.jsx
│   │   │   ├── ListPage.jsx 
│   │     
│   │   ├── main.jsx  
│   │
│   │
│   ├── .gitattributes
│   ├── .gitignore
│   ├── app.js
│   ├── index.html
│   ├── LICENSE
│   ├── package.json
│   ├── package-lock.json
│   ├── postcss.config.js
│   ├── README.md
│   ├── tailwind.config.js
│   ├── vite.config.js
