# my-split-keyboard

### 成品展示
<img src='./images/split-keyboard.jpg' style='width:800px;'>

### 准备
- 硬件：
  - 3D打印机一台、及打印耗材
  - 焊烙铁一台、及焊锡丝
  - 主控：Pro Micro Atmege32u4 两个
  - USBISP 下载器一个 
    - 用来给主控烧录引导程序
  - 二极管，直接买100根备用
  - 杜邦线，焊接前测试用
  - PJ313 直插5脚（3节）的耳机插座，至少两个（多买点备用）
  - 3段式的耳机线
    - 多买两根没几块钱
  - 防滑贴
    - 打印的键盘模具放桌子上会比较滑
  - 螺丝+螺帽，M2.0 到 M3.5，
    - 各型号多买几个，不同模型打印出来需要的型号还不一样（我是把M1.0到M）
  - 镊子，至少一个吧

- 软件：
  - QMK MSYS: 用来编译固件代码，可以找个合适的布局手动修改适合自己的键位，再编译
  - avrdudess: 使用 USBISP下载器 ，给 Atmege32u4 刷引导程序
  - QMK Toolbox: 用来给 Atmege32u4 把编译好的固件代码烧录进去
  - VIA: 如果烧录的固件代码支持via改键的可以用，我没用

- 网站
  - [https://kbfirmware.com/](https://kbfirmware.com/) : 常规的一体键盘可以用它来生成固件代码，分体不行
  - [http://www.keyboard-layout-editor.com/#/](http://www.keyboard-layout-editor.com/#/) : 搭配kbfirmware用，生成布局的json，可以用来画个草图
  - [https://docs.qmk.fm/#/keycodes?id=keycodes-overview](https://docs.qmk.fm/#/keycodes?id=keycodes-overview) : QMK 文档
  - [https://www.printables.com/model](https://www.printables.com/model) : 3D模型图纸下载
  - [https://www.thingiverse.com/](https://www.thingiverse.com/) : 3D模型图纸下载
  - [https://github.com/gsihaj5/qmk_firmware](https://github.com/gsihaj5/qmk_firmware) : QMK 源码

### 
