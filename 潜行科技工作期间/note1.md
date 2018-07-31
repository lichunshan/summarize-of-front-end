# note1

https://git.chasing-innovation.com:3000/user/login

使用 reset.css 初始化
移动webapp  的a标签，设置为block，增大可点击区域，布局使用flex

在手机上面的一像素并不是1像素，手机有dpi的概念

windows下 通过命令行ipconfig 查看机器的ip  ，将ip地址去草料二维码生成一个二维码，之后就可以使用手机微信扫码看到我们的页面了
（前提：手机和电脑要链接同一个局域网）

mac 下通过ifconfig 查看机器的ip

消除空白字符： 给父元素的font-size设置为0

css sticky footer 布局

写css时最好将布局的代码写在最前面，因为这些代码会触发重绘

vue中使用v-if来判断异步获取的数据是否已经得到，没得到的时候就不渲染组件，直到有数据了才渲染，避免报错

先写好样式和布局，然后再写交互

在编写组件的时候，父组件可以调用子组件的方法，使用v-ref为子组件命名，然后就可以在父组件中取到子组件了。

vue组件编写规范，当组件内部的方法可以被外部组件调用的时候命名采用驼峰，不能被外部调用的时候就在函数名前面加上一个下划线

研究一下：vue的过渡动画

Vue.nextTick()

v-el在1.0中存在，2.0中已经废弃了使用v-ref替代

Vue.set(this.food, 'count', 1)

this.$emit('cart-add',event.target)子组件与父组件通信


编译和打包
优化：路由懒加载
如果静态资源放到cdn上可以在config文件夹下的index.js配置文件中配置assetsPublicPath为cdn的域名


部署上线：
ftp工具
scp要在本地客户端执行
上传权限问题
node启动和pm2启动