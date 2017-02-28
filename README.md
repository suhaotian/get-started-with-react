## 学习资源

  [官网](facebook.github.io/react) （过一遍差不多都会了）

  [React 入门实例教程 - 阮一峰](http://www.ruanyifeng.com/blog/2015/03/react.html)

  [react 中文论坛](http://react-china.org/)

  [Awesome React](https://github.com/enaqx/awesome-react) （上面的都可以看下，没事多翻翻）


## 开始之前

  开始之前，安装个 [create-react-app](https://github.com/facebookincubator/create-react-app)
  ```shell
  npm install -g create-react-app

  create-react-app my-app
  cd my-app/
  npm start
  ```
  然后编辑 src 目录里面 App.js 保存就可以直接看效果了！

## 学习笔记

  ```js
  class HelloMessage extends React.Component {
    render() {
      return <div>Hello {this.props.name}</div>;
    }
  }
  ```
  
  
  
  react 就是 js + jsx，组件看成是函数， props 就是函数的参数，state 就是它的数据；
  调用 setState 就会执行 render 方法，render 方法可以看成是返回模板的地方。
  
  *搞清楚这几个概念：state, props, props.children, life cycle（生命周期），ref（找到真实的 DOM ）*
  
  文档已经写的挺好的，对着文档，边敲边看结果，明白的很快。 首页的几个 demo 也不错。
