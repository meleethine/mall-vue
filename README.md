# 前言

1.	项目基于Vue-cli3开发，使用Element-ui搭配部分自定义功能组件实现大部分功能模块开发，通过对项目进行分析和构思，将页面及路由合理拆分

2.	通过路由导航守卫控制访问权限，并在axios请求拦截器添加token，保证用户的数据访问权限；通过多个role分控访问权限，在role中嵌套children属性实现多层权限列表。

3.	设置swich开关管理用户状态，发送put请求时携带一个用户id和用户状态，请求失败则按钮重置并提示，请求成功仅提示。

4.	通过指定不同的开发/发布模式打包入口、第三方库启用CDN、Element-UI组件按需加载、路由懒加载等操作优化项目。

5.	采用https协议对传输的数据进行加密处理,让网络传输更加安全。

6.	通过Echarts 实现各类统计数据可视化，如订单数据报表。


# 技术栈

vue2 + vue-router + ES6 + Element-UI + Axios + Echarts


# 项目运行

```
前端部分:

git clone https://github.com/meleethine/mall-vue-ui.git

或者

git clone git@github.com:meleethine/mall-vue-ui.git  

cd mall-vue-ui

npm install

npm run serve

后端部分:

git clone https://github.com/meleethine/mall-server.git

或者

git clone git@github.com:meleethine/mall-server.git  

cd mall-server

node app.js

```


# API文档

https://github.com/meleethine/mall-vue-ui/blob/main/API.md


# 目标功能
- [x] 用户登录 -- 完成
- [x] 退出登录 -- 完成
- [x] 用户管理 -- 完成
- [x] 角色列表权限管理 -- 完成
- [x] 权限列表权限管理 -- 完成
- [x] 商品分类管理 -- 完成
- [x] 商品列表管理 -- 完成
- [x] 商品参数管理 -- 完成
- [x] 订单管理 -- 完成
- [x] 数据统计-- 完成



# 项目截图

### 登录页面

<img src="https://github.com/meleethine/mall-vue-ui/blob/main/login.gif" width="720" height="405"/> 

### 用户管理

<img src="https://github.com/meleethine/mall-vue-ui/blob/main/screenshots/user.gif" width="720" height="405" object-fit:contain/> 

### 权限管理

<img src="https://github.com/meleethine/mall-vue-ui/blob/main/screenshots/power.gif" width="720" height="405" object-fit:contain/> 

### 商品管理

<img src="https://github.com/meleethine/mall-vue-ui/blob/main/screenshots/goods.gif" width="720" height="405" object-fit:contain/> 

### 订单管理

<img src="https://github.com/meleethine/mall-vue-ui/blob/main/screenshots/order.gif" width="720" height="405" object-fit:contain/> 

### 数据统计

<img src="https://github.com/meleethine/mall-vue-ui/blob/main/screenshots/statistic.gif" width="720" height="405" object-fit:contain/> 

