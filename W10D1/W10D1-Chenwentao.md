# IO

对于软件层：everything is file（字节序列），按照统一的操作

对于硬件层：对接设备，设置驱动

## 硬件层面

- 块设备：硬盘、光盘，USB

  把信息存储在固定大小的块中，每个块有自己的地址

- 字符设备：鼠标、键盘、打印机、网络接口

  以字符作为单位发送，或者接送一个字符流

设备控制器

DMA：直接内存读取

## 软件层面

- 程序控制IO：CPU控制
- 中断驱动IO
- 使用DMA的IO

## 中断

中断向量

精确中断与不精确中断

## X window system

UNIX系统的用户界面

X客户与X服务器