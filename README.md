**这个项目适用于A12/A13处理器 包括iPhone XR / XS / XSMAX / 11 / SE2 以及部分iPad A12 / A13 设备**

适用于A12/A13处理器的全部IOS版本

前置准备条件：Waveshare RP2350 USB-A / Pi Pico 2 等受支持的开发板

通过usbliter8漏洞利用进入pwndfu 实现保留当前系统版本抹除屏幕锁（目前无法绕过iCloud激活锁以及物主锁）

1.连接电脑进入DFU模式

2.usbliter8漏洞利用！

3.插回电脑连接pwndfu

4.等待程序识别 同意协议开始抹除

5.引导刷写完成后开机！Boom锁定移除且保留原IOS版本（过程请勿断开连接 否则可能造成系统文件损坏）

后续展望：通过进一步开发漏洞 绕过MDM监管锁 绕过iCloud激活锁以及物主锁（不会公开 涉及违法风险 仅交流技术实现）

感谢https://github.com/prdgmshift/usbliter8提供漏洞利用工具以及思路
