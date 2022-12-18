## README

### 环境搭建

```shell
npx create-react-app react-travel --template typescript
npm install antd @ant-design/icons
npm install react-router-dom@5.2.0
npm install @types/react-router-dom --save-dev
```

UI框架
[Ant Design](https://ant.design/index-cn)

### 路由系统

网站路由系统的要求

+ 路由导航与原生浏览器操作行为一致`<BorwserRouter />`
+ 路由的路径解析原理与原生浏览器一致，可以自动识别url路径`<Route />`
+ 路径的切换以页面为单位，不要页面堆叠`<Switch />`


### 遇到的问题

```shell
1.Error: A <Route> is only ever to be used as the child of <Routes> element, never rendered directly. Please wrap your <Route> in a <Routes>.
解决办法：修改react-router-dom版本
```
