# Mini_HDMI
迷你HDMI转RGB驱动板

支持RGB屏幕分辨率：
480-272   
800-480   
1024-600   
1280-800   

触摸输入设备暂只支持1024-600 触摸IC：FT5426

bootloader使用swd接口烧录，之后只需一根USB数据线即可更新固件适配不同的屏幕
bootloader：PA9引脚接地上电进入USBbootloader
例：1024_600屏幕使用1024_600_Firmware.bin

第一次更新固件后暂时不要连接HDMI，因为程序第一次会写入EDID，连接HDMI接口可能会干扰写入，之后上电就无需重复写入了，直接接入HDMI接口即可

连接大屏尽量使用USB接口供电

视频演示：https://www.bilibili.com/video/BV12b4y1D7HF/

![TIM截图20210325000141](https://user-images.githubusercontent.com/23308519/138417830-e1c84cad-8b7f-41cf-89d7-91ec1023f105.jpg)

![TIM截图20210325000236](https://user-images.githubusercontent.com/23308519/138417864-7fb795ba-892a-499a-a7b8-9b2f394e9393.jpg)

![c5c54bcd8a8f4cbb613963a5f5d1953cc1005fd1](https://user-images.githubusercontent.com/23308519/138427380-d6260971-d797-4b29-8281-7b88856afefe.jpg)

