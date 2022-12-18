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

### 遇到的问题

```shell
1.Error: A <Route> is only ever to be used as the child of <Routes> element, never rendered directly. Please wrap your <Route> in a <Routes>.
解决办法：修改react-router-dom版本
```
