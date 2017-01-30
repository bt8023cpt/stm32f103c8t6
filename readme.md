# stm32f103c8t6 微处理器学习笔记

## 涉及到的相关资源

### 软件资源

- MDK-ARM v5.22

![image](https://github.com/bt8023cpt/stm32f103c8t6/blob/master/image/MDK-ARM.png)

### 硬件资源

- stm32f103c8t6 最小系统

![image](https://github.com/bt8023cpt/stm32f103c8t6/blob/master/image/stm32f103c8t6.png)

- Micro-USB 供电线

### 注意事项

- stm32f103c8t6 属于中容量型的芯片，使用 startup_stm32f10x_md.s 启动文件，并需要定义 STM32F10X_MD,USE_STDPERIPH_DRIVER 这两个宏
