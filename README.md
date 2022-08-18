# 2022年夏季《移动软件开发》实验报告



<center>姓名：叶鹏  学号：20020007095</center>

| 姓名和学号         | 叶鹏，20020007095                                            |
| ------------------ | ------------------------------------------------------------ |
| 本实验属于哪门课程 | 中国海洋大学22夏《移动软件开发》                             |
| 实验名称           | 实验2：天气查询小程序                                        |
| 博客地址           | [Click me if you can](http://existot01.top/)                 |
| Github仓库地址     | [You won't miss that](https://github.com/ExistoT01/mobileSoftwareDesign-lab2) |

（备注：将实验报告发布在博客、代码公开至 github 是 **加分项**，不是必须做的）



## **一、实验目标**

1、学习使用快速启动模板创建小程序的方法；2、学习不使用模板手动创建小程序的方法。



## 二、实验步骤

1. 准备工作

   1. API密钥申请

      申请账号，新建应用，获取`key`值

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115086.png" alt="image-20220818194138636" style="zoom:80%;" />

   2. API调用方法

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115088.png" alt="image-20220818194626775" style="zoom:80%;" />

   3. 服务器域名配置

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115089.png" alt="image-20220818195244981" style="zoom:80%;" />

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115090.png" alt="image-20220818195358009" style="zoom:80%;" />

2. 项目创建

   <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115091.png" alt="image-20220818195829354" style="zoom:80%;" />

3. 页面配置

   <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115092.png" alt="image-20220818200022805" style="zoom:80%;" />

   <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115093.png" alt="image-20220818200034134" style="zoom:80%;" />

4. 视图设计

   1. 导航栏设计

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115094.png" alt="image-20220818200206447" style="zoom:80%;" />

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115095.png" alt="image-20220818200218285" style="zoom:80%;" />

   2. 页面设计

      1. 背景容器样式

         <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115096.png" alt="image-20220818200719429" style="zoom:80%;" />

      2. 地区选择器设计

         <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115097.png" alt="image-20220818200857750" style="zoom:80%;" />

         <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115098.png" alt="image-20220818200906783" style="zoom:80%;" />

      3. 文本设计

         <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115099.png" alt="image-20220818201507114" style="zoom:80%;" />

         <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115100.png" alt="image-20220818201516072" style="zoom:80%;" />

      4. 天气图标设计

         <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115101.png" alt="image-20220818201912070" style="zoom:80%;" />

         <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115102.png" alt="image-20220818201924786" style="zoom:80%;" />

      5. 多行天气信息设计

         <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115103.png" alt="image-20220818202759759" style="zoom:80%;" />

         <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115104.png" alt="image-20220818202808851" style="zoom:80%;" />

5. 逻辑实现

   1. 更新省市区信息

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115105.png" alt="image-20220818203603836" style="zoom:80%;" />

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115106.png" alt="image-20220818203616549" style="zoom:80%;" />

   2. 获取实况天气数据

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115107.png" alt="image-20220818210038510" style="zoom:80%;" />

   3. 更新页面天气信息

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115108.png" alt="image-20220818210710522" style="zoom:80%;" />

      <img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115109.png" alt="image-20220818210729239" style="zoom:80%;" />



## 三、程序运行结果

列出程序的最终运行结果及截图。

<img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115110.png" alt="image-20220818210739649" style="zoom:80%;" />

<img src="https://expicture.oss-cn-beijing.aliyuncs.com/img/202208182115111.png" alt="image-20220818210802847" style="zoom:80%;" />

## 四、问题总结与体会

本次实验制作了一个天气查询的小程序，在写程序的过程中学习到了`request`请求和`utils`模块的使用，了解到了`api`请求获取数据的过程，最终完成了一个可以查询全国城市天气的小程序，过程十分有趣。