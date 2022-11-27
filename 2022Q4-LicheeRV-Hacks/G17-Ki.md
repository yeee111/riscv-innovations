# 基于OpenGauss的”轻量级可把玩“型数据库

## 参与人

G17-Ki

## 项目背景

* 中山大学[ SUN YAT-SEN UNIVERSITY](http://www.sysu.edu.cn/index.htm)计算机学院本科生课程【数据库系统概念】与华为OpenGauss开源项目合作，并激励学生基于OpenGauss开发相关应用，但目前教学大纲中只有基于软件实现的部分（比如基于Docker或其他容器），与其他科目较为割裂。
* 本人在参与OpenGauss社区讨论中注意到不少志同道合之人想要将OpenGauss部署在硬件环境直接操作，本人对此也十分感兴趣，想要尝试将该数据库部署在开发板上，为国产数据库平台提供一个简单的新思路

## 项目目标

* 使所有想要尝试OpenGauss的同学可以不必苦恼于软件配置，直接部署在硬件上就可以以开发板的形式对数据库进行增删改查
* 将开发板实现成为类似Switch的 ”易于把玩“设备，并且能够实现数据库操作的可视化
  * 可视化可以通过外联显示器、WIfi、网口链接到后续开发的Web程序
  * 使得所有人在操作数据库的时候**不必绑定于十分复杂的界面**

## 预期成果

* 初步实现OpenGauss在开发板上的部署
* 通过IO接口外接轻便设备实现简单操作
  * 对于操作表的切换
  * 更改表项数据
  * 实现简单查询和特权级用户层级功能

## 预期时间表

| 截止时间         | 目标工作                                 | 难度系数 |
| ---------------- | ---------------------------------------- | -------- |
| 2022.12.15       | 将OpenGauss成功部署在开发板上            | ⭐⭐⭐      |
| 2022.12.31       | 成功导入用于测试的表格（以及相关的约束） | ⭐⭐       |
| 2023农历新年之前 | 调试外接接口实现操作的可视化             | ⭐⭐⭐⭐     |

## 成果展示
