## andrew-cli

> 代替复制黏贴的脚手架

### 使用

## 1. 必须切换andrew-cli所在的npm服务


```shell
#安装npm源地址工具
npm install nrm -g
#查看当前学有所成 
nrm ls
#添加指定定源 
npm add andrew http://ip:port/
#查看是否成功 
nrm ls
#切换到指定源
nrm use andrew
```

## 2. 安装生成工具包

```shell
npm i -g andrew-cli
andrew-cli create projectName
```

## 3.跑起来
 生成的项目根目录
```shell
# 安装依赖
npm install
# 调试运行
npm run dev 
```

