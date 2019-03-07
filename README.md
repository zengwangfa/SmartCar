<<<<<<< HEAD
# ETA-Quadcopter

#### 介绍
2018全国大学生“恩智浦“杯智能汽车竞赛 

集美大学 双车会车组——【高斯洛必达队】

# 1.智能车控制中心

| 硬件 | 描述 |
| -- | -- |
|芯片型号| K60N512 |
|CPU| Cortex-M4 |
|FLASH| 512K |
|SRAM| 128K |
|主频| 180MHz |
|单元| FPU |



# 2.目录说明
```
+——ETA-Quadcopter
|--------+ docs: 【一些方法与调试文档】
|--------+ hardware:【相关电路设计】      
|            └──MOS_Motor_drive 【驱动电路】
|            └──... 【...】
|--------+ software:【相关软件设计】
|            └──2018.08.21(The end) 【程序】
|            └──... 【...】
|-----README.md

```


# 3.硬件架构
```
+——Smart_Car
|--------+──K60N512 【Center Control】                  
|        |       └──【Normal Peripheral】
|        |       ├── LED [GPIO]   
|        |       ├── KEY [GPIO]     
|        |       ├── OLED [Software SPI]                   
|        |       └──......  
|        |       └── 【Important Peripheral】
|        |       ├── Electromagnetic Induction [ADC] 
|        |       ├── 鹰眼OV7725 [DMA]   
|        |       ├── Bluetooth to Debug [UART]
|        |       ├── Zigbee to Debug [UART]
|        |       └──...... 
|        +──Vehicle Devices
|        ├── Motor [PWM]
|        └──...... 
```



# 4.软件架构
```
+——Smart_Car
|    └──Peripherals Init 【系统内核初始化】                  
|    ├──Flash Read 【读取FLASH参数】
|    ├── Mode 【选择模式】 
|           └── Speed control 【速度控制】 
|           ├── Steering control 【方向控制】 
|           ├── Communication control 【通讯逻辑控制】 
|    		└──...... 
```


#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request


=======
# 13th-NXP-JMU双车会车2018

#### 介绍
2018 JMU双车会车所有资料

#### 软件架构
仅此纪念.


#### 安装教程

1. xxxx
2. xxxx
3. xxxx

#### 使用说明

1. xxxx
2. xxxx
3. xxxx

#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request


#### 码云特技

1. 使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2. 码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3. 你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4. [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5. 码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6. 码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
>>>>>>> 80ea09866f9c41da42c5403c1ddf254d5c0693b9
