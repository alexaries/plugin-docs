## 说明
采用git-book+markdown编写文档

### 安装
- win
```
npm install gitbook -g
npm install gitbook-cli -g
npm install gh-pages -g
```

- mac
```
sudo npm install gitbook -g
sudo npm install gitbook-cli -g
sudo npm install gh-pages -g
```

## 构建
```
gitbook build
```
## 运行 
```
gitbook serve
```
## 发布到GitHub上
一般输入密码错误,会导致出现错误
```
fatal: A branch named 'gh-pages' already exists.
```
删除全局安装的模块缓存
```
/usr/local/lib/node_modules/gh-pages/.cache
```
如果还是无法解决,可以尝试重新安装该模块
```
npm uninstall gh-pages -g
npm install gh-pages -g
```

