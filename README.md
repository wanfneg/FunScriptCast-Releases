# FunScriptCast 功能说明

### 1. VR播放器联动
- 支持VR播放器联动：
  - HereSphere
    - 支持VR头显本地视频播放以及SMB局域网视频播放
    - 打开HereSphere，点击 User Settings，找到Advanced Settings， 勾选 Timestamp Server。然后点击 Timestamp Server 旁边的刷新按钮，记录下方出现的IP 地址
    - 在播放器连接处，填写前面记录的IP地址，端口号用默认的23554，点击连接播放器
    - 设置中，设定脚本文件夹，并将配套脚本放入该文件夹
  - DeoVR
    - 支持VR头显本地视频播放以及DLNA局域网视频播放，DLNA服务器部署：https://github.com/wanfneg/VR-DLNA/releases
    - 打开DeoVR，进入「Settings」→「Developer」，勾选「Enable Remote Control」
    - Quest：「设置」→「Wi-Fi」→「详情」→「IP 地址」
    - Pico：「设置」→「WLAN」→「添加网络」→「更多」→「IP 地址」
    - 在播放器连接处，填写前面记录的IP地址，端口号用默认的23554，点击连接播放器
    - 设置中，设定脚本文件夹，并将配套脚本放入该文件夹
- 关于是否支持在VR头显内安装本软件直接在VR头显内控制：
    - Quest：「设置」→「实验性」→打开「多任务无缝处理」
    - Pico：目前暂无「多任务无缝处理」，不支持
    - 其他品牌VR设备：请自行测试

---

### 2. 内置播放器联动
- 视频源：
  - 本地文件夹
  - WebDAV
  - DLNA
  - SMB
- 播放支持：
  - 外挂字幕 `.srt / .ass / .vtt`
  - VR视频模式

---

### 3. 预设模式
- 内置 9 种预设
- RANDOM 随机切换
- BOOST 狂暴加速
- 手动速度控制 1–500
