---
layout: default
title: 嵌入式系统编程与实践
---

## 课程信息

- 教室:	昌平新校区-205
- 时间:	6:40pm-9:30pm，周三（1～16周）
- 课程教授：燕博南 (主页：[bonany.cc](https://bonany.cc))
- 助教：符一涵
- Email:	bonanyan AT pku.edu.cn  

## 教学计划

[例程安排](/assets/lec/实践课_standalone_demo功能说明_final.pdf)

| *周* | *日期* | *类别*                                | *内容*                                                               | *主讲人*                                                                  | *备注*        |
| ---- | ------ | ------------------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------- |
| 1    | 9/11   | ⓵理论                                | 课程介绍 & 嵌入式系统开发概论 [\[slides\]](/assets/lec/L1_Intro.pdf) | 燕博南                                                                    |               |
| 2    | 9/18   | ⓵理论                                | 嵌入式系统组 成[\[slides\]](/assets/lec/L2_CPS.pdf)                  | 燕博南                                                                    |               |
| 3    | 9/25   | ⓵理论                                | 通信接口 [\[slides\]](/assets/lec/L3_Interface.pdf)                  | 燕博南                                                                    |               |
| 4    | 10/2   | 无课堂活动                            | 欢度假期🥳                                                          |                                                                           |               |
| 5    | 10/9   | ⓶实践                                | K210入门+PWM波                                                       | 周钜宸([1.1](/assets/lec/jz_11.pdf)),彭筵城([1.3](/assets/lec/yc_13.pdf)) | 课堂实验：1.2 |
| 6    | 10/16  | ⓵理论+⓶实践                         | 中断([slides](/assets/lec/L4_Intterupts.pdf))+UART编程                                                        | 王俊棋([1.4](/assets/lec/UART收发测试)),吴秋平([1.5](/assets/lec/1.5uart_dma.pdf)),黄森([1.6](/assets/lec/UART_dma_irq.pdf))，燕博南                                 |               |
| 7    | 10/23  | ⓶实践                                | UART中断、RTC、定时器                                                | 刘天驰	([1.7](/assets/lec/UART中断.pdf)),彭伟桀([2.1](/assets/lec/RTC.pdf)),张容(2.2)                                        |               |
| 8    | 10/30  | ⓶实践                                | SHA256、Servo、LCD                                                      | 周可行(2.3),张容(2.4),彭筵城(2.5)                                         |               |
| 9    | 11/6   | ⓶实践                                | 加速器模块：AES、FFT、Flash                                          | 范世昌(2.6),周钜宸(3.1),彭伟桀(3.2)                                       |               |
| 10   | 11/13  | ⓶实践                                | FLASH应用                                                            | 王俊棋(3.3),房宇轩(3.4),李国玮(3.5),崔璠(3.6)                             |               |
| 11   | 11/20  | ⓶实践                                | camera_lcd+watchdog                                                  | 范世昌(4.1),吴秋平(4.2)                                                   |               |
| 12   | 11/27  | ⓶实践                                | K210人工智能编程                                                     | 周可行(5.0),李国玮(5.1),房宇轩(5.2), 所有同学                             |               |
| 13   | 12/4   | ⓵理论                                | 创意项目开题+K210人工智能编程                                        | 黄森(6.1),崔璠(6.2)                                                       |               |
| 14   | 12/11  | ⓶实践                                | 课程总结 + 创意项目赶进度                                            |                                                                           |               |
| 15   | 12/18  | ⓶实践                                | 创意项目赶进度                                                       | 燕博南                                                                    |               |
| 16   | 12/25  | ⓷创意                                | 项目展示+互评打分                                                    | @所有人                                                                   |               |
| 17   | 25/1/1 | 晚25:59:59前提交Final Project zip大包 |                                                                      |                                                                           |               |

## Final Project说明

- 2024年1月5日23:59:59，到时候打包zip/tar提交（文件名：姓名_学号.zip）：
  - 源代码：（整体项目文件）
  - 项目演示视频 (.mp4格式)
  - 视频发布知情书(1)选项、(2)签名、(3)提交pdf（知情书）
  - 项目报告（包括但不限于实现的功能、实现的系统组成框图及主要模块说明、工作流程图/系统状态转移图、用到的硬件部件，如CPU、KPU、DVP、SPI、UART等）

## 课程资源

### 开发板资源  

- [开发者资料](/assets/doc/K210开发资料给客户_20221008.7z)
- 开发板型号: _PaddlePi_ 
- 例程：[https://github.com/kendryte/PaddlePi](https://github.com/kendryte/PaddlePi)

### 进阶开发板

- 开发板型号：_CanMV CM-1_

## 主要参考书：

- Introduction to Embedded Systems: A Cyber-Physical Systems Approach
  - [https://ptolemy.berkeley.edu/books/leeseshia/](https://ptolemy.berkeley.edu/books/leeseshia/)

## 成绩考核方式：

- 实践主讲（45%）
- 课程项目随堂报告展示（40%）
  - 实践随堂程序：5% × 3
  - 最终演示：25%
- 课程项目书面报告（15%）
