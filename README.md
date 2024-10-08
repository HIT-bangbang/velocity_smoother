# 说明

本仓库收集ROS中常用的速度平滑器

## 功能包介绍

1. velocity_smoother_ema(https://github.com/seifEddy/velocity_smoother_ema.git)

ema算法的速度滤波器（其实就是一阶低通滤波器）。个人感觉写的不完善，它要求必须是定频的速度输入，定频的速度输出。可以修改一下，通过获取时间戳的方式来动态计算两个速度指令时间间隔，然后去做ema算法里面去。