# StarCraft2-CN-Replay-Repair
星际争霸2国服录像在线修复工具  

支持一次性修复多个文件，由于web应用的限制，我们无法修改文件的修改时间，为了方便区分，我们采用在修复后的名称中加入时间戳：
> MyReplay-20251201-FIXED.SC2Replay

估计这个月会推送录像的更新，到时这个项目的生命周期也随之结束，所以很高兴这个小工具能在这段时间帮到您。

推荐访问 https://probiusofficial.github.io/StarCraft2-CN-Replay-Repair/ 使用  

也可以自己把html down下来本地部署

## 原理和声明

该工具通过修改录像文件版本号部分的ViNT压缩数据区块从而达到修复目的，更多关于录像文件结构相关的部分请参考三方工具 [sc2reader](https://github.com/ggtracker/sc2reader) 或者暴雪官方开源的 [s2protocol](https://github.com/Blizzard/s2protocol) 。

由于工具只会修改特定数据区块，您需要清楚该工具无法让您观看不受支持的大版本录像，也无法用于修复由于星际争霸2客户端相关未知bug或者地图依赖配置不当导致的录像文件先天性结构缺失，异常，数据不同步等相关问题。
