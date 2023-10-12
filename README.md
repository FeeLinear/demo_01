# demo_01
源代码来自于jQuery之家，如有侵权，请联系


### 1、配置镜像源
```js
npm config set registry http://10.200.0.5:8081/repository/npm-group
sass_binary_site 需要单独配置：
npm config set sass_binary_site http://cdn.npm.taobao.org/dist/node-sass
```

### 2、配置npm
```js
npm config set always-auth true
npm login   // 输入对应的账号和密码
```

### 3、安装依赖
```js
npm i
```

### 4、开发模式启动
```js
npm run dll
npm run serve
```
### 5、生产打包
```js
npm run build
```
