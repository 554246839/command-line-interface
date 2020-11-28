## cli脚手架搭建

### step1
初始化npm
```js
npm init
```

### step2
新建bin文件，用于定义cli命令列表

### step3
在package.json文件中添加bin命令
```json
{
  "bin": {
    "testcli": "./bin/testcli.js"
  }
}
```

### step4
使用npm link进行全局命令注册

### step5
新建lib文件用于定义bin文件内命令的具体执行逻辑
