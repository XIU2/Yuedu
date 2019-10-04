# 「阅读」APP 精品书源

[![GitHub license](https://img.shields.io/badge/license-GPL--3.0-orange?style=flat-square)](https://github.com/XIU2/yuedu/blob/master/LICENSE)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg?style=flat-square)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg?style=flat-square)](https://996.icu)

本项目每天抓取「阅读」官方微信公众号中分享的优质精品书源，制作成一个单独的书源文件，方便大家一键导入！  
彻底解决了「阅读」官方公众号每次更新都需要打开微信手动复制导入的痛点了！现在只需要定期重复导入该书源（二维码或URL）即可，省时省力！  
> 为了避免阅读作者打爆我的狗头，所以... **「阅读」官方微信公众号：「开源阅读软件」**  

> 之所以搬到 Github，主要是莫名其妙好像又火了，现在一天几十万访问量，而且每天还在稳定增加，我怕我的小服务器以后撑不住，干脆就给搬到 Github 上面了！

****

### 更新日志：
- **新增：** 校验书源功能。  
—— 脚本会把无法访问的书源网站去除。  
—— 该功能对于那些书源规则失效（而不是书源网站挂了）的书源是无效的，所以依然可能存在小部分失效书源。
- **修复：** 昨天脚本新抓取的书源有问题，已经修复了格式不对的问题（以后每次更新前会先检查JSON格式是否正确再更新）。
- **新增：** 历史书源文件：https://github.com/XIU2/yuedu/tree/master/old
- **新增：** 网站将显示书源更新时间及数量。

****

### 软件介绍：
「阅读」我就不多介绍了，我见过不少人安利，我直接贴酷安的介绍吧。
https://www.coolapk.com/apk/com.gedoor.monkeybook

****

### 下载地址：
- **软件下载地址：** https://www.coolapk.com/apk/com.gedoor.monkeybook
- **软件开源地址：** https://github.com/gedoor/MyBookshelf
- **官方下载地址：** https://github.com/gedoor/MyBookshelf/releases

****

### 书源地址：
书源每日更新，大家可以定期导入一次~ 放心！导入时会自动去重复的！
- **书源分享地址：** https://xiu2.github.io/yuedu/
- **网络导入地址：** https://xiu2.github.io/yuedu/shuyuan

- **本地导入地址：** 去上面的书源分享地址里点击 **\[下载文件\]**
- **历史书源文件：** https://github.com/XIU2/yuedu/tree/master/old

****

### 导入步骤：
#### 二维码导入(推荐)：
打开「阅读」APP点击左上角的 **\[三横杠\] 按钮 - \[书源管理\]**(最下方第一张图)，这时候再点击右上角的 **\[三圆点\] 按钮 - \[二维码导入\]**(最下方第二张图) - 然后手机扫描下方二维码即可即可。  

![](https://github.com/XIU2/yuedu/raw/master/dist/img/img-01.png)

****

#### 网络导入(推荐)：
打开「阅读」APP点击左上角的 **\[三横杠\] 按钮 - \[书源管理\]**(最下方第一张图)，这时候再点击右上角的 **\[三圆点\] 按钮 - \[网络导入\]**(最下方第二张图) - 输入下面的网络导入地址并点击 **\[确定\]** 按钮即可（最下方第三张图）。  
- **网络导入地址：** https://xiu2.github.io/yuedu/shuyuan

****

#### 本地导入：
打开 [书源分享地址](https://xiu2.github.io/yuedu/) 后点击 **\[下载文件\]** 即可下载 **shuyuan.json** 文件，存放到手机中任何你能找到的位置。  

打开「阅读」APP点击左上角的 **\[三横杠\] 按钮 - \[书源管理\]**(最下方第一张图)， 这时候再点击右上角的 **\[三圆点\] 按钮 - \[本地导入\]**(最下方第二张图) - 选择 **shuyuan.json** 文件导入即可（最下方第四张图）。  

![](https://github.com/XIU2/yuedu/raw/master/dist/img/img-02.png)

****

### 许可证
The GPL-3.0 License.  
The Anti-996 License.
