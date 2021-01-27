# JimuReport

积木报表，是一款免费的企业级Web报表工具，像搭建积木一样在线设计报表！功能涵盖，数据报表、打印设计、图表报表、大屏设计等！

- Web 版报表设计器，类似于excel操作风格，通过拖拽完成报表设计。
- 秉承“简单、易用、专业”的产品理念，极大的降低报表开发难度、缩短开发周期、节省成本、解决各类报表难题。


```
永久免费使用
专注于开源，打造“专业 易用 智能”的报表工具
开源宗旨：`功能永久免费、可以商用、代码不开放（大屏设计暂时不提供离线版本）`

领先的企业级Web报表软件，采用纯Web在线技术，专注于解决企业报表快速制作难题。
```

v1.1.09-beta | 20210125

快速体验： [www.jimureport.com](http://www.jimureport.com "www.jimureport.com")



产生背景
-----------------------------------
报表是企业IT服务必备的一项需求，但是行业内并没有一个免费好用的报表，大部分免费的报表功能较弱也不够智能，商业报表又很贵，所以有了研发一套免费报表的初衷。
做一个什么样的报表呢？随着低代码概念的兴起，原先的通过报表工具设计模板，再与系统集成的模式已经落伍，现在追求的是完全在线设计，傻瓜式的操作，实现简单易用又智能的报表！
目前积木报表已经实现了完全在线设计器，轻量级集成、类似excel的在线设计，像搭建积木一样在线设计报表！功能涵盖数据报表设计、打印设计、图表设计、大屏设计等！

- 2019年底启动积木报表研发工作，历经一年多的时间，2020-11-03发布第一版：[v1.0-beta出炉](https://www.oschina.net/news/119666/jimureport-1-0-beta-released)
- 2020年的持续打磨和研发，终于在2021-1-18发布了第一个正式版本 [v1.1.05](https://www.oschina.net/news/126916/jimureport-1-1-05-released)




开发文档
-----------------------------------

- [快速集成](http://report.jeecg.com/2078875)
- [操作手册](http://report.jeecg.com/1423422)




项目介绍
-----------------------------------

- 官方网站： http://www.jimureport.com
- 视频教程： http://jimureport.com/doc/video
- QQ交流群：212391162

![输入图片说明](https://oscimg.oschina.net/oscnet/up-093c83cd5f01bbbd6021c97c74af3df07f8.png "在这里输入图片标题")


功能清单
-----------------------------------

```
├─报表设计器
│  ├─数据源
│  │  ├─支持多种数据源，如Oracle,MySQL,SQLServer,PostgreSQL等主流的数据库
│  │  ├─支持SQL编写页面智能化，可以看到数据源下面的表清单和字段清单
│  │  ├─支持参数
│  │  ├─支持但数据源和多数数据源设置
│  ├─单元格格式
│  │  ├─边框
│  │  ├─字体大小
│  │  ├─字体颜色
│  │  ├─背景色
│  │  ├─字体加粗
│  │  ├─支持水平和垂直的分散对齐
│  │  ├─支持文字自动换行设置
│  │  ├─图片设置为图片背景
│  │  ├─支持无线行和无限列
│  │  ├─支持设计器内冻结窗口
│  │  ├─支持对单元格内容或格式的复制、粘贴和删除等功能
│  │  ├─等等
│  ├─报表元素
│  │  ├─文本类型：直接写文本；支持数值类型的文本设置小数位数
│  │  ├─图片类型：支持上传一张图表
│  │  ├─图表类型
│  │  ├─函数类型
│  │  └─支持求和
│  │  └─平均值
│  │  └─最大值
│  │  └─最小值
│  ├─背景
│  │  ├─背景颜色设置
│  │  ├─背景图片设置
│  │  ├─背景透明度设置
│  │  ├─背景大小设置
│  ├─数据字典
│  ├─报表打印
│  │  ├─自定义打印
│  │  └─医药笺、逮捕令、介绍信等自定义样式设计打印
│  │  ├─简单数据打印
│  │  └─出入库单、销售表打印
│  │  └─带参数打印
│  │  └─分页打印
│  │  ├─套打
│  │  └─不动产证书打印
│  │  └─发票打印
│  ├─数据报表
│  │  ├─分组数据报表
│  │  └─横向数据分组
│  │  └─纵向数据分组
│  │  └─多级循环表头分组
│  │  └─横向分组小计
│  │  └─纵向分组小计
│  │  └─合计
│  │  ├─交叉报表
│  │  ├─明细表
│  │  ├─带条件查询报表
│  │  ├─表达式报表
│  │  ├─带二维码/条形码报表
│  │  ├─多表头复杂报表
│  │  ├─主子报表
│  │  ├─预警报表
│  │  ├─数据钻取报表
│  ├─图形报表
│  │  ├─柱形图
│  │  ├─折线图
│  │  ├─饼图
│  │  ├─折柱图
│  │  ├─散点图
│  │  ├─漏斗图
│  │  ├─雷达图
│  │  ├─象形图
│  │  ├─地图
│  │  ├─仪盘表
│  │  ├─关系图
│  │  ├─图表背景
│  │  ├─图表动态刷新
│  │  ├─图表数据字典
│  ├─参数
│  │  ├─参数配置
│  │  ├─参数管理
│  ├─导入导出
│  │  ├─导入Excel
│  │  ├─导出Excel、pdf
│  ├─打印设置
│  │  ├─打印区域设置
│  │  ├─打印机设置
│  │  ├─预览
│  │  ├─打印页码设置
├─大屏设计器
│  ├─系统功能
│  │  ├─静态数据源和动态数据源设置
│  │  ├─基础功能
│  │  └─支持拖拽设计
│  │  └─支持增、删、改、查大屏
│  │  └─支持复制大屏数据和样式
│  │  └─支持大屏预览、分享
│  │  └─支持系统自动保存数据，同时支持手动恢复数据
│  │  └─支持设置大屏密码
│  │  └─支持对组件图层的删除、组合、上移、下移、置顶、置底等
│  │  ├─背景设置
│  │  └─大屏的宽度和高度设置
│  │  └─大屏简介设置
│  │  └─背景颜色、背景图片设置
│  │  └─封面图设置
│  │  └─缩放比例设置
│  │  └─环境地址设置
│  │  └─水印设置
│  │  ├─地图设置
│  │  └─添加地图
│  │  └─地图数据隔离
│  ├─图表
│  │  ├─柱形图
│  │  ├─折线图
│  │  ├─折柱图
│  │  ├─饼图
│  │  ├─象形图
│  │  ├─雷达图
│  │  ├─散点图
│  │  ├─漏斗图
│  │  ├─文本框
│  │  ├─跑马灯
│  │  ├─超链接
│  │  ├─实时时间
│  │  ├─地图
│  │  ├─全国物流地图
│  │  ├─地理坐标地图
│  │  ├─城市派件地图
│  │  ├─图片
│  │  ├─图片框
│  │  ├─轮播图
│  │  ├─滑动组件
│  │  ├─iframe
│  │  ├─video
│  │  ├─翻牌器
│  │  ├─环形图
│  │  ├─进度条
│  │  ├─仪盘表
│  │  ├─字浮云
│  │  ├─表格
│  │  ├─选项卡
│  │  ├─万能组件
└─其他模块
   └─更多功能开发中。。
```




