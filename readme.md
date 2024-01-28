# Project setup

1. npm init -y (npm initialization)
2. npm install mongoose --save (mongoose installation)
3. npm i express (express installation)  
   npm i --save-dev @types/express
4. npm install -D typescript (typescript installation)  
   tsc --init  
   rootDir and outDir setup
5. npm i dotenv (dotenv installation)
6. npm i cors (cors installation)  
   npm i @types/cors
7. npm i ts-node-dev --save-dev (for run app when developing)
8. mongodb connection (database connection)
9. npm i zod (zod validator installation)
10. npm i http-status (for http-status code)
11. eslint installation

    1. add these two lines inside tsconfig.json file  
       "include": ["src"], // which files to compile  
       "exclude": ["node_modules"], // which files to skip
    2. npm install eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin --save-dev
    3. npx eslint --init
    4. add (inside eslintrc.json file)  
        "rules": {  
       "no-unused-vars": "error",  
       "no-unused-expressions": "error",  
       "prefer-const": "error",  
       "no-console": "error",  
       "no-undef": "error"  
       },  
       "globals": {  
       "process": "readonly"  
       }
    5. create .eslintignore file and add those files inside the file:  
       node_modules  
       dist

12. npm i bcrypt (bcrypt for password hashing)  
    npm i @types/bcrypt
13. npm i jsonwebtoken (jwt token)  
    npm i @types/jsonwebtoken