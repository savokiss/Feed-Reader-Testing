# Feed Reader Testing
- 这是 Udacity 纳米学位的 RSS 订阅阅读器测试项目
- 该项目将 RSS 源转换成 JSON 数据并展示在页面上，目前支持的 RSS 源有：Udacity Blog、CSS Tricks、HTML5 Rocks、Linear Digressions
- 该项目让学生通过完善测试用例来熟悉 Jasmine 框架，并掌握常规的单元测试、DOM 测试、异步测试等测试知识

## Stack
- Jasmine
- Jquery
- handlerbars
- normalize.css
- icomoon

## Testing
- 测试了 RSS 源数据定义且不为空
- 测试了 源数据中的 url 定义了且合法
- 测试了 源数据中的 name 定义了且不为空
- 测试了 侧边栏默认是隐藏的
- 测试了 侧边栏点击后的显示隐藏功能
- 测试了 异步请求成功后至少有一条 RSS 数据
- 测试了 切换不同的 RSS 源，页面中的内容会确实发生变化

## Get Started
- 在线访问： [http://savokiss.me/Feed-Reader-Testing](http://savokiss.me/Feed-Reader-Testing)
- 本地访问： clone 项目，运行 `index.html` 即可
- 点击侧边栏菜单切换 RSS 源
- 页面最下方可以看到测试用例的执行情况