# 📄脚本公告
---
- <font  color="#87CEFA"> 2021.11.02 </font>   1.3.2重制版发布,请删除原1.3.1版本并重新安装当前信息页的1.3.2重制版，以免失联
- <font  color="#87CEFA"> 2021.08.30 </font>    已支持Aria推送下载，可不需设置UA
- <font  color="#87CEFA"> 2021.08.18 </font>    百度网盘解析功能脚本演示下载
- <font  color="#87CEFA"> 2021.08.15 </font>    为了保证接口的稳定性请先设置IDM！<font  color="#DC143C">IDM>选项>选项>连接>
默认最大连接数选择为4>确定</font>

<div align=center><img src="https://www.helloimg.com/images/2021/08/18/CA1wbX.gif"></div>

# 📜脚本功能
---
- ✅支持识别选中内容中的百度网盘链接与提取码，并会在打开网盘页面后自动填充提取码/密码
- ✅支持免SVIP解析直链进行高速下载
- ✅支持淘宝/天猫搜索页列表优惠券查询，京东优惠券查询
- ✅支持淘宝/天猫商详页显示优惠券与历史价格查询
- ✅支持主流网站VIP视频解析观看，内嵌播放器页面无广告
- ✅支持主流软件下载站的高速下载器广告屏蔽
- ✅支持Aria、Motrix的一键发送下载【百度网盘直链解析功能】

# 💻脚本教程与建议反馈
---

### 🧩获得详细的教程指南:[在线教程](https://www.shuma.ink)<br>

### 💿脚本配套工具下载:[配套工具](https://www.shuma.ink/zh-cn/faq.html)<br>

### 🎯问题反馈交流群:[一键加入](https://jq.qq.com/?_wv=1027&k=FMfKKGY5)<br>

### 🎁支持数码:[获得福利](https://www.shuma.ink/zh-cn/ad.html)


# ✏️特别说明
---
- 使用网盘解析功能时，需要先关注公众号【小木盒】并通过公众号内小程序进行领取流量卡密（不限制次数）
- 脚本并不会保存你的帐号cookies，也不会保存你的提取码/解析链接
- 免SVIP会员/免保存解析网盘文件
- 但不支持批量文件及文件夹解析，不支持违规资源解析
- 插件不会存储视频及任何文件，所有解析内容均来源于互联网与用户个人，并不会进行任何共享或分享
- 有任何问题或因规则不适我会在接到反馈的第一时间进行修正，频繁举报导致脚本被下架也会使得其余用户不能正常地进行反馈与使用。
- 如果脚本内的功能对你的权益或版权造成了侵害，请第一时间进行反馈告知，我将在接到反馈后的第一时间进行功能修正。
- 脚本若更名之后出现旧版与新版共存的情况时，请删除旧版安装新版，以便于获得更多功能上的支持与体验。
- 希望各位高抬贵手有问题至反馈区进行反馈，为了使更多用户能够享受便捷也希望热爱greasyfork社区的人士不要频频举报。

# 🛠️更新日志<br>
---
- 2021.09.10&emsp; &emsp; v1.2.6 支持百度网盘分享页面下载，无需保存至自己网盘内即可解析
- 2021.08.30&emsp; &emsp; v1.2.0 支持Aria推送下载，优化其他功能已知问题
- 2021.08.15&emsp; &emsp; v1.1.9 修复百度网盘直链解析功能的某些Bug
- 2021.08.10&emsp; &emsp; v1.1.7 增加广告屏蔽清理功能
- 2021.06.28&emsp; &emsp; v1.0.9 修复已知问题
- 2021.06.28&emsp; &emsp; v1.0.8 增加历史价格查询，修复网盘解析添加卡密为空
- 2021.06.23&emsp; &emsp; v1.0.7 优化视频解析及其他功能
- 2021.06.23&emsp; &emsp; v1.0.6 增加京东商品页优惠券查询
- 2021.06.22&emsp; &emsp; v1.0.5 支持主流网站VIP视频解析观看
- 2021.06.18&emsp; &emsp; v1.0.4 优化直链解析流程
- 2021.06.16&emsp; &emsp; v1.0.3 支持淘宝/天猫搜索页列表优惠券查询
- 2021.06.02&emsp; &emsp; v1.0.1 支持百度网盘直链解析下载
- 2021.05.21&emsp; &emsp; v1.0.0 支持百度网盘链接识别与填充提取码

# 📌使用教程
---
在使用脚本之前，请先确认你是否已安装Tampermonkey<br>
如果没有安装Tampermonkey，脚本将无法正常提供服务
## ⌨️网盘提取码识别功能
---
<details>
<summary>展开获得详细教程</summary>
<pre><code>
1.鼠标选择百度网盘的链接及提取码，即可自动识别。<br>
<div align=center><img src="https://i.loli.net/2021/05/21/fLmOZya8G4YxrSd.png"></div>

<br>

2.在识别后按照提示框进行打开<br>2.1.顺利打开后将自动填充提取码。<br>

<div align=center><img src="https://i.loli.net/2021/05/21/PrwVZUi58XbL16e.png"></div>
<br>
</code></pre>
</details>


## 🔃网盘直链解析功能
---
<details>
<summary>展开获得详细教程</summary>
<pre><code>
1.将需要下载的文件（压缩包）保存至你的网盘内<br>1.1.并在网盘内选择要下载的文件<br>1.2然后点击名为网盘工具箱-直链的按钮进入解析页面<br>

<div align=center><img src="https://i.loli.net/2021/06/02/y83FQ7HMkaOldcT.png"></div>
<br>

2.进入解析页面后<br>2.2.点击【配置卡密】填写在右侧公众号中获取的卡密<br>2.3.再点击解析按钮即可完成解析<br>

<div align=center><img src="https://www.helloimg.com/images/2021/08/16/C4Qwiv.png"></div><br>
3.打开IDM，并在下载>选项>下载>粘贴在脚本中复制的UA<br>
<div align=center><img src="https://z3.ax1x.com/2021/10/14/5l7ErQ.png"></div><br>


4.完成以上设置后，点击【新建任务】填入直链<br>
<div align=center><img src="https://i.loli.net/2021/05/23/A6r9RfapFMJETPK.png"></div><br>


5.等待下载完成<br>
<div align=center><img src="https://i.loli.net/2021/05/23/49qcBleYDTFAP8H.png"></div><br>
</code></pre>
</details>

## 📚Aria与Motrix的使用教程
---
<details>
<summary>展开获得详细教程</summary>
<pre><code>
1.在解析完成后，点击【脚本配置】进行配置<br>
1.1.或在解析前点击【脚本配置】<br>进行Aria的地址端口及下载保存目录进行配置<br>
<div align=center><img src="https://www.helloimg.com/images/2021/08/24/CSE9kQ.png"></div><br>
2.在【Aria配置】中将Aira RPC地址<br>设置为:http://localhost:6800/jsonrpc<br>
2.1.Aria RPC密钥可为空<br>默认的下载地址可进行自定义。<br>
<div align=center><img src="https://www.helloimg.com/images/2021/08/24/CSEdbu.png"></div><br>
3.在配置完成后，打开下载好的Aira软件包<br>找到【AriaNg启动器.exe】并双击启动。<br>
3.1.在启动完成后，会弹出AriaNg的web端页面<br>配置正确时左下方中部会出现【已连接】的提示。
<div align=center><img src="https://www.helloimg.com/images/2021/08/30/CiKE6Y.png"></div><br>
4.返回到脚本页面，点击【发送到Aria】
<div align=center><img src="https://www.helloimg.com/images/2021/08/24/CSEc1t.png"></div><br>
4.1.一切配置正确时，在发送后脚本会提示发送成功<br>此时在AriaNg的web页面可以看见已开始下载。
<div align=center><img src="https://www.helloimg.com/images/2021/08/24/CSE0RE.png"></div><br>
5.如果你想采用Motrix进行下载时<br>只需要点击【脚本配置】按钮<br>
5.1.在Aria配置中<br>将Aria RPC地址的端口6800更改为16800即可。<br>
<div align=center><img src="https://www.helloimg.com/images/2021/08/24/CSEvIv.png"></div><br>
5.2.在使用Motrix时需要注意的是<br>你的文件保存目录必须要和Aria配置中的相同。
<div align=center><img src="https://www.helloimg.com/images/2021/08/24/CSEQN9.png"></div><br>
如果你对于Aria的配置不是特别熟悉或是第一次使用<br>
建议不要对Aria RPC地址及密钥进行修改<br>
只需要对你的文件保存目录进行修改即可。
</code></pre>
</details>

## 🛒优惠券查询
---
<details>
<summary>展开获得详细教程</summary>
<pre><code>
1.进入淘宝/天猫/天猫超市<br>
2.搜索页搜索任意商品关键词，即可查询优惠券
<div align=center><img src="https://i.loli.net/2021/06/16/ULhZIT4R1S2Gkvc.jpg"></div><br>
3.打开任意商详页会显示该商品是否存在隐藏优惠券
<br>
<div align=center><img src="https://z3.ax1x.com/2021/06/25/Rlfh11.png"></div>
4.在淘宝、京东商详页中显示历史价格
<div align=center><img src="https://i.loli.net/2021/06/28/Uh2vq68Dtmc5kFY.png"></div>

</code></pre>
</details>

## 📽️VIP视频解析
---
<details>
<summary>展开获得详细教程</summary>
<pre><code>
1.进入任意主流视频网站，如腾讯视频、爱奇艺等<br>
1.1.搜索或浏览选择你想看的电视剧或电影<br>
1.2.在主页并不会出现【VIP按钮】<br>
<div align=center><img src="https://z3.ax1x.com/2021/06/22/RecEVK.png"></div>

2.在视频内容页才会出现【VIP按钮】<br>
2.1.只需要点击按钮就可以跳转播放<br>
2.3.其他网站也是如此，若无按钮则为未适配<br>
<div align=center><img src="https://z3.ax1x.com/2021/06/22/Reckb6.png"></div>
2.3.网页播放器空白的解决办法
<div align=center><img src="https://z3.ax1x.com/2021/06/22/RecFDx.png"></div>
2.4.更换视频解析线路的操作办法
<div align=center><img src="https://z3.ax1x.com/2021/06/22/RecVUO.png"></div>
</code></pre>
</details>

## 🚫下载卫士
---
<details>
<summary>展开获得详细教程</summary>
<pre><code>
针对软件下载站进行高速下载器按钮的屏蔽，减少误点带来的捆绑安装
目前已适配的下载站:
多特下载站
PC6下载站
华军软件园
太平洋下载中心
西西软件园
东坡下载
当下软件园

演示效果
<div align=center><img src="https://www.helloimg.com/images/2021/08/10/CtWxCP.png"></div>
</code></pre>
</details>

# 🔑更多黑科技
---

关注微信公众号，你可以获取到更多黑科技与互联网冲浪技巧<br>
<div align=center><img src="https://www.helloimg.com/images/2021/08/13/C4saVQ.jpg"></div><br>


# 更新记录

* 1.0.0 首次发布