#开发者帮助文档
##下载
```git
git clone https://github.com/baukh789/GridManager.git
```

##启动
### 加载依赖包
```
	npm install
```
### 启动服务
```
npm run start
```
### 构建打包
```
npm run build
```
### 展示路径 
```
http://127.0.0.1:1987
```

##单元测试
- 执行命令
```
npm test
```
- 测试文件路径及文件名规范
```
/test/****_text.js
```

##问题汇总
### npm install 总是失败?
这是由于在国内加载时,有些依赖包无法加载导致的. 可以将package.json中的( karma-phantomjs-launcher )移除掉再进行install.

##参与开发
QQ群号: 151094839
