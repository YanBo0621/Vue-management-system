# client

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Run your tests

```
npm run test
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

proxy: {
//配置跨域
"/api": {
target: "http://localhost:5000/api",
ws: true,
changOrigin: true,
pathRewrite: {
"^/api": ""
}
}
},
