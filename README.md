# Raspberry-HDMI-CSI-I2C
> Convert HDMI signal acquisition into CSI signal and I2C audio signal
## Introduction
Raspberry pi is a very popular device in the open source world.In many application scenarios, we need to collect the video and audio of HDMI input device.At present, there are some modules on the market that can convert HDMI signal to CSI signal.But they can't convert video and audio at the same time, and they are very expensive, and they are not easy to install on raspberry pi.Therefore, I design a module that can convert HDMI signals into video and audio signals at the same time, and it is not expensive. I named it **C780**.
## C780A picture
![](/images/C780A.jpg)
## Version
C780 module is divided into C780A and C780B versions according to the number of CSI-2 channels.C780A supports 2 CSI-2 channels, up to 1080P50fps HDMI input.And C780B supports 4 CSI-2 channels, up to 1080P60fps HDMI input.
## Hardware parameters
**C780A**
* HDMI input: supports up to 1080P50fps on raspberry pi(Limited by the number of CSI-2 channels)
* HDMI to CSI-2 bridge chip:Toshiba TC358743XBG
* 2 CSI-2 channels & clock
* CSI-2 interface: 15 pin FPC seat, spacing 1.0 mm
* Size: 30 x 65 mm (unbroken PCB size); 30 x 45 mm (PCB size after breaking)
* Install:6 x M2.5
* Power supply:3.3V
* Weight: 9g
## Test video
C780A test:https://www.youtube.com/watch?v=ecqyINoiHNQ

C780B test:https://www.youtube.com/watch?v=nc-hwPT2Uak&t=15s
