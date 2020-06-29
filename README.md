# vue_shop

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

### Lints and fixes files
```
npm run lint
```


### 登陆页面的说明
···
1. components中的Login.vue
2. 由页面制作、登录表单、表单验证以及axios登录提交组成
---
**出错日志：**
- 当使用表单rules验证时，浏览器会打印async-validator验证警告，只要将node_modules\async-validator\es\util.js中的console.log(type, errors);注释掉即可。
···

#### 代码的格式化说明
- .prettierrc定义这个文件在项目的根目录，然后输入，格式化文件就会按下面的要求进行代码的格式化；
···
{
    "semi": false,   // 去掉分号
    "singleQuote": true   	// 单引号
}
···
### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
