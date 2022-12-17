---
title: 关于
date: 2022-12-12 17:10:00
--- 


## Extend 124OJ!

欢迎来到 Ex124OJ，这是 CDQZ 124OJ 的用户脚本。

  - 下载数据
  - 讨论板块
  - 复制代码
  - 背景图片
  - 表格样式
  - ……

<div style="height:512px">
    <img id="img0" src="./img0.png" style="display:initial">
    <img id="img1" src="./img1.png" style="display:none">
    <img id="img2" src="./img2.png" style="display:none">
    <script>
        setTimeout(function play(i) {
            document.getElementById('img' + i).style = "display:none";
            document.getElementById('img' + (i + 1) % 3).style = "display:initial";
            setTimeout(play, 2000, (i + 1) % 3);
        }, 1500, 0)
    </script>
</div>

## 安装

  1. 在你的 Chrome, Edge, Firefox 浏览器上，安装扩展程序 Tampermonkey。\
     [Chrome 扩展程序](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)\
     [Edge 扩展程序](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)\
     [Firefox 扩展程序](https://addons.mozilla.org/firefox/addon/tampermonkey)\
     [Chrome .crx 文件](./Tampermonkey_4.18.0.crx)
  2. 打开 Greasyfork 上 [Ex124OJ 的发布主页](https://greasyfork.org/scripts/455093-ex124oj)。
  3. 点击 <img src="./button0.png" style="display:inline-block"> 按钮，添加用户脚本。

## 更新

一般情况下可以自动更新。

如无法自动更新，打开 [Ex124OJ 的发布主页](https://greasyfork.org/scripts/455093-ex124oj)，点击 <img src="./button1.png" style="display:inline-block"> 按钮，更新用户脚本。

发布主页也可以通过在 Tampermonkey 用户脚本管理界面点击 <img src="./button2.png" style="display:inline-block"> 来打开。

## 个性化

在标题栏中用户名左侧，我们放置了一个按钮 <img src="./ControlPanelEntrance.png" style="display:inline-block">，用以打开控制面板。

<img src="./ControlPanel.png">

## 致谢

作者：[@Sukwants](https://github.com/Sukwants)

如果你有好的 Idea 并愿意为 Ex124OJ 作贡献，欢迎你的加入。
