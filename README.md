# 个人信息
#### 王瑄
#### 上海金融学院 2011.9-2015.7 本科 计算机科学与技术/金融
#### 前端工程师 两年半工作经验
# 技能介绍 
#### 精通JavaScript vue全家桶
#### 掌握ES6 JQ handlebar backbone fis3
#### 熟悉webpack 小程序
#### 了解react node 
# 工作经历
#### 2016.4-至今 上海舍汇信息技术有限公司（大房鸭） 前端
#### ————大房鸭PC端的开发、升级和维护
#### ————大房鸭h5和公众号的开发 微信搜索大房鸭可以查看公众号
#### ————大房鸭ATM大屏调试、与大房鸭APP实现页面内嵌和信息交互
#### 2015.10-2016.1 上海上业信息科技有限公司 前端
#### ————上业门户网站改版升级
#### ————乐学网页响应式搭建
#### ————外包教育网站的静态页面搭建 处理IE6-IE8兼容性问题
# 主要项目
#### 2018.3 H5社区顾问答题系统
社区顾问答题系统主要涉及正式测试和模拟测试，错题回顾，考试计时等多个相关功能。

使用vue+vuex+vueRouter+es6开发。主要问题在于接口多，返回形式不一致以及多种状态的存在。通过vuex存储数据，自己处理数据，优化数据结构。

帮助了社区顾问提升专业素质的同时，也为公司培训节约成。
#### 2018.1 PC端升级预约看房/价格走势功能
根据各种复杂情况进行预约看房，h5/web同时将价格走势图升级为echarts3。

预约看房需要满足复杂逻辑下的多种看房时间规则，展示天气情况。而PC端价格走势图插件老旧，多出调用比较混乱，H5则是使用canvans开发，功能相对简单。使用echart3.0统计PC和H5的价格走势插件，在移动端或者PC端都有明显性能的提升。而对时间规则的逻辑处理，更合理更方便用户预约看房，也帮助公司节约了时间成本。
#### 2017.10 H5摄影师列表/带看页面
为了方便摄影师及时填写带看反馈。包括接单列表，以及填写房源信息的功能。

从列表页到填写房源信息页面，除了相关信息的展示，多部操作，通过cookie记录相关信息。

摄影师之前只能自己记录信息，通过PC端进行传递，现在可以通过手机微信号接单，上门拍照的时候就可以核对、填写房源信息。
#### 2017.8 web端用户管理页面改版
页面功能散乱，用户使用不便，决定升级开发新页面

主要难点在于页面内容过多加载缓慢，涉及多个功能开发，根据需求升级新页 面，组件化开发。 通过归纳相似点，抽离出公用组件，通过复用大量减少了代码。优化房东上传 图片功能，使用data-*存储方式对比内容变更

用户管理页面升级，使得不论房东或者用户，都可以更清晰的进行使用管理。
#### 2017.5 H5房源列表页面及搜索页面
首次添加了公司公众号的入口，包括房源信息展示，房源搜索和条件筛选功能。

主要难点在h5房源列表页面涉及很多筛选功能，同时还有搜索房源的功能。 使用vue的数据驱动试图，减少dom操作，vuex管理搜索内容，通过vuerouter优化列表页和搜索页路由跳转，使用定时器进行函数节流和缓存数据规 避重复请求，通过页面滚动判断加载，优化页面加载性能。列表信息/头部/侧 边栏组件化，为以后多个页面的复用提供便捷。

h5房源列表页作为微信端的第一个入口，帮助公司提升了注册用户和用户访问 量。
#### 2016.8 h5博客项目
公司为了提高影响力，帮助用户了解二手房情况，决定开发博客项目

整个项目包含列表，详情，搜索页面。主要难点在于滚动加载，详情页面的登 录，留言，回复功能，同时与app联调交互数据 通过计算滚动距离，进行滚动加载，添加loading进行优化处理，使用七牛接口 压缩图片，提升性能加载。通过请求header添加信息，来处理安全登陆机制。 执行app的方法传递信息。

h5博客页面向用户普及房产知识，留言回复可以和用户进行互动，提升大房鸭 页面访问量和注册用户量。

