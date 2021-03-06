# 1-1 React 出现的历史背景及特性介绍

项目起源于 FaceBook 在迭代他们的产品中，在开发一个看似很简单的功能的时候，结果虽然在短期内快速的开完并且上线成功，但是线上却是 bug 四起，这让当时的 FaceBook 开始思考问题到底出现在了哪里：
    
1. 传统的 UI 操作太过复杂
2. 应用的状态分散在各处，难以维护

在此基础上，FaceBook 发布了全新编程思想的前端框架 React 

1. React 始终刷新 “整个” 页面
2. 概念很简单：
    1. 1个概念 组件
    2. 4个必须的api 
        1. ReactDOM.render 方法让 React 组件渲染到某个具体的 DOM 节点。
        2. 组件的 render 方法 
        3. 组件的 setState 方法，用于改变组件状态，触发 render 
        4. 如何通过 props 给 React 组件传递参数
    3. 单向数据流 基于Flux架构
    4. 完善的错误提示
3. 基于 Flux 架构：单向数据流 
   Flux 衍生的项目：Redux，MobX
