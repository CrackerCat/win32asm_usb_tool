## win32asm_usb_tool
win32asm汇编语言实现的简单可移动磁盘病毒专杀辅助工具  


## 主要文件功能

| **文件名**   | **依赖**     | **主要功能描述**                         |
| ------------ | ------------ | ---------------------------------------- |
| USB_Tool.Inc |              | 头文件、导入库  宏、常量、全局变量定义等 |
| myFunc.Asm   | USB_Tool.Inc | 自定义功能函数                           |
| USB_Tool.Asm | myFunc.Asm   | 主程序界面、核心功能实现等               |
| USB_Tool.rap |              | Radasm工程文件                          |


https://github.com/playGitboy/win32asm_usb_tool/blob/main/image/%E5%8A%9F%E8%83%BD%E9%80%BB%E8%BE%91.png


## 待处理
旧代码未更新，win10中可能热键注册失败导致无法呼出界面，待有空修复……
