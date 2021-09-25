# Monorepo with npm workspaces and Typescript

For now this application doesn't solve any specific domain problem. I mean, it's pretty simple, just importing local modules through monorepo structure.

---

## Running the application

**1. Install dependencies**<br/>
 Make sure you're on the root folder **monorepo** and run: 
 ```ts
    npm install
 ```
 This step is necessary due to the fact this application have interdependent dependencies through local modules.

 **2. Build modules**<br/>
 ```ts
    lerna run build
 ```

 **3. Start the modules**
 ```ts
    lerna run start
 ```
 This application uses [Lerna](https://github.com/lerna/lerna).

## Technologies

 - NodeJs
 - Typescript
 - Npm
 - Lerna

## Next Steps

 - Explanation over Typescript, Lerna and local modules
 - Add Jest for test files