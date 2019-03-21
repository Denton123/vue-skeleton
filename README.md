# object

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

### 步骤:
#####1、新建template.html，代码和index.html一样，只是在div#app里面添加<!--vue-ssr-outlet-->
#####2、新建Skeleton.vue和skeleton.entry.js
#####3、新建webpack.skeleton.conf.js打包skeleton.entry.js为skeleton.json
#####4、新建skeleton.js将骨架屏注入index.html
