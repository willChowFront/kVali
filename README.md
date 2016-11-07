#轻任务应用源码
##源码结构
```
app_task/
  |
  ├── task/
  |   ├── build/
  |   |   ├──  打包相关配置，不需要修改的
  |   ├── config/
  |   |   ├── 可根据自身需要修改的打包相关配置，如端口，打包文件生成路径
  |   ├── node_modules/
  |   ├── src/
  |   |   ├── api/
  |   |   |   ├── 获取后台数据的相关ajax请求，基于VueResource
  |   |   ├── assets/
  |   |   |   ├── css fonts image等静态资源
  |   |   ├── components/
  |   |   |   ├── active-projects.vue
  |   |   |   ├── project-item.vue
  |   |   |   ├── ...
  |   |   |   ├── 相对细化的组件
  |   |   ├── views/
  |   |   |   ├── home.vue
  |   |   |   ├── error.vue
  |   |   |   ├── ...
  |   |   |   ├── 页面级别的组件
  |   |   ├── plugins/
  |   |   |   ├── 自定义Vue插件
  |   |   ├── utils/
  |   |   |   ├── 实用工具
  |   |   ├── vendor/
  |   |   |   ├── 第三方插件
  |   |   ├── vuex/
  |   |   |   ├── vuex架构相关的js
  |   |   ├── App.vue
  |   |   ├── index.html
  |   |   ├── main.js
  |   |   ├── routes.js
  |   ├── .babelrc
  |   ├── .editorconfig
  |   ├── .eslintrc.js
  |   ├── package.json
  |   ├── sftp-config.json
  ├── .gitignore
  └── README.md
```
