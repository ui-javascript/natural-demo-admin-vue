# README

- 这里主要是

    - 学习高版本angular与node.js
    - 学习了解webpack等脚手架的配置
    - gulp配置 给传统前后端不分离项目配的 -> https://github.com/natural-fe/natural-effects
    - 写H5页面(移动端)的脚手架
    - 多页面解决方案 
        - 基于Vue的多页面 -> https://github.com/natural-fe/natural-components
    - 兼容IE8的若干前端框架比较
    - 一些公司开源的脚手架比较
    - SSR、SEO优化等
    
# webpack

- webpack 自身只理解 JavaScript, 其他都当做模块处理

- 参考
    - webpack-study https://github.com/qq20004604/webpack-study
    - 静态站点 https://github.com/vhtml/webpack-MultiPage-static
    - https://github.com/ruanyf/css-modules-demos
    - https://github.com/css-modules/webpack-demo
    - https://www.jianshu.com/p/63eacd66eb50du
    - https://github.com/rt-zhangxuefei/vue-project-multipages-template

- happypack 
    - https://github.com/amireh/happypack
    - https://juejin.im/post/5a922e776fb9a06337575031

- 优化

    - NICE webpack打包优化探索 https://mp.weixin.qq.com/s/SzD22kTnYYfQShQwRaAGWA
        - https://github.com/zhuanzhuanfe
        - https://github.com/zhuanzhuanfe/zz-webpack-vue
        - https://github.com/zhuanzhuanfe/zz-webpack-react
        
    - 使用 webpack 优化资源 https://qiutc.me/post/resource-optimization-webpack.html
    - 优化Webpack构建性能的几点建议 https://www.cnblogs.com/powertoolsteam/p/Webpack.html
    - 借助webpack对项目进行分析优化 https://segmentfault.com/a/1190000014369413
        - https://segmentfault.com/u/athon
        - http://callmedadaxin.github.io/
    - webpack优化不完全指南 https://juejin.im/post/5a49fb696fb9a0451e402718
    - webpack打包优化（VUE Project）讲ddl优化配置 https://juejin.im/post/5a8797c15188257a836c385d
    - 晚晴幽草轩
        - 速度篇 https://jeffjade.com/2017/08/12/125-webpack-package-optimization-for-speed/
        - 体积篇 https://jeffjade.com/2017/08/06/124-webpack-packge-optimization-for-volume/
    - https://juejin.im/post/5a869044f265da4e9c632f94
    - https://github.com/DDFE/DDFE-blog/issues/23
    
# Parcel

- 估计要凉
- parcel极简入门 与 前端构建工具吐槽
    - https://github.com/Mcbai/Blog/issues/2
    - https://www.rails365.net/articles/cong-webpack-dao-quan-mian-yong-bao-parcel-1-tan-suo-parcel
    
- DEMO

    - Parcel + React https://www.cnblogs.com/huanent/p/8331295.html    
    - Parcel + Vue https://github.com/p2yang/parcel-vue


- Parcel VS Webpack 
    - https://github.com/gwuhaolin/parcel-vs-webpack

# SPA

- (NICE) https://github.com/nicejade/vue-boilerplate-template

```shell
# 全局安装
npm install -g  strip-ansi
... sass
... node-sass

使用npm install cnpm 可能出错
```

# 企业开源脚手架

- feflow 腾讯IVWEB前端工作流和规范 https://github.com/feflow/feflow
- athena2 https://github.com/o2team/athena2
- y-workflow  阅文 https://github.com/yued-fe/y-workflow
- 前端团队 Gulp & Webpack 工作流 迁移记(NICE) https://zhuanlan.zhihu.com/p/27355765?group_id=857652944793915392
- WeFlow https://github.com/Tencent/WeFlow
- QMUI_Web https://github.com/Tencent/QMUI_Web
- legoflow https://github.com/legoflow/legoflow

# H5移动端 

- 移动端页面适配———多方案解析 https://www.jianshu.com/p/3b45aa981e77 