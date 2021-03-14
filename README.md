# tube-gis 爆管监测系统前端
vue3.0 + typescript + 高德地图 + echarts + antv + sass + eslint

### 安装

1. 安装nvm（要求windows用户名是英文，如果非英文，创建一个英文用户，用英文用户安装并开发）
2. 配置 nvm 国内镜像地址
3. 在 nvm 内安装 node v14.18.
4. 配置 npm 国内镜像地址
5. 用 node 自带的 npm 安装 yarn
6. 配置 yarn 国内镜像地址
7. 拉取 git 之后运行下面的命令行安装依赖

```
yarn ci
```

### 开发
通过下面的命令启动开发热更新
```
yarn dev
```
**注意：每次pull-request分支前，记得先merge目标的分支到自己的分支上，保证自己的代码是基于目标分支开发的**
每个人从master分支clone自己的分支，在自己的分支上开发，开发完毕使用git-cz来commit，push代码到gitee上之后新建pull-request来申请提交到develop分支。
最终确认没问题后再次pull-request到master分支。

### 相关文档
-

### 参考文档
* vueRouter： https://next.router.vuejs.org/zh/introduction.html
* vue3.x： https://v3.cn.vuejs.org/guide/component-basics.html#%E5%9F%BA%E6%9C%AC%E5%AE%9E%E4%BE%8B
* antv： https://2x.antdv.com/docs/vue/introduce-cn/
* 高德2.0API: https://lbs.amap.com/api/jsapi-v2/guide/abc/quickstart
* echarts: https://echarts.apache.org/zh/option.html