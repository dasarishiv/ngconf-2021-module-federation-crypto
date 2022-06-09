# Module Federation Tutorial using @angular-architects/module-federation

# Tutorial

Due to limitations with npm, you must use yarn

Look at package.json

`"resolutions": { "webpack": "5.18.0" },`



//branch feature/workshop1

```
ng add @angular-architects/module-federation --project shell --port 5000
```

```
yarn start:mfe1

yarn start:shell
```


```
ng g application mfe2 --prefix=mfe2 --route=false --style=css

// repo branch demo3
```

```
ng add @angular-architects/module-federation --project mfe2 --port 3001
```