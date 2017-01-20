<h1> Welntu</h1>
工大小助手-微信小程序
<h2>需求分析</h2>
* 教务在线
 * 查课表  
 * 查成绩
 * 考试安排
 * 更多    
  - 绩点查询  
  - 一键评课  
  - 挂科查询
* 学习助手
 * 题库
 * 资料导航
* 生活助手
 * 物业报修
 * 快递查询
* 更多
 * 反馈
 * 合作
<h2>目录结构</h2>
wecqupt
  ├─ app.json       // 全局配置文件，决定页面文件的路径、窗口表现、设置网络超时时间、设置多tab等     
  ├─ app.js         // 全局js，如执行App()函数来初始化注册小程序
  ├─ app.wxss       // 全局样式
  ├─ utils          // 模块化文件夹，利用module.exports暴露接口，通过require(path)使用模块接口
  │    └─ util.js   // 模块化例子
  ├─ images         // 图片文件夹
  └─ pages          // 页面文件夹
       ├─ index     // 主页
       │    ├─ index.wxml
       │    ├─ index.wxss
       │    └─ index.js
       ├─ study      // 资讯
       │    ├─ news.wxml    // 列表
       │    ├─ news.wxss
       │    ├─ news.js
       │    ├─ detail.wxml   // 详情
       │    ├─ detail.wxss
       │    └─ detail.js
       ├─ life      // 更多
       │    ├─ more.wxml    // 更多 (含绑定用户)
       │    ├─ more.wxss
       │    ├─ more.js
       │    ├─ about.wxml   // 关于
       │    ├─ about.wxss
       │    └─ about.js
       └─ core      // 主页功能文件夹
            ├─ kb       // 课表
            │    ├─ kb.wxml
            │    ├─ kb.wxss
            │    └─ kb.js
            └─ other    // 其他
                 └─ ..
