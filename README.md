# nuxt-express-jest-ts

> Express & Jest & Typescript in Nuxt.js app

## Build Setup

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

```

## Current Problems
(except code structure)

``` bash
# jest makes the test pass with [Vue warn]
$ yarn jest

```

>  [Vue warn]: Property or method "author" is not defined on the instance but
 referenced during render. Make sure that this property is reactive, either in the data option, or for class-based components, by initializing the property. See: https://vuejs.org/v2/guide/reactivity.html#Declaring-Reactive-Properties.
    
    found in
    
    ---> <Anonymous>
           <Root>