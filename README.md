#vue 天气预报 demo

三个实例

>index.html:基本页面，展示实现效果

>index2.html:引入vue，实现了从地址组件 点击地址 传递到天气展示组件，
使用了 location.hash 改变客户端路由。
window.onhashchange 监听路由改变事件  触发改变app组件的ct(城市)

>index3.html:引入vue 和 axios.js
实现了天气初始化(广州市)，点击地址切换到对应城市的天气