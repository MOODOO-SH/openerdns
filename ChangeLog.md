# OpenerDNS 更新情况: #

<li>日期：2014.07.05<br>
OpenerDNS 更新。最近观察到BT客户端（迅雷等）在下载时会进行大量的无效域名查询，这会导致用户进入我们的临时黑名单中，从而暂时无法使用。为了应对，我们对于无效域名的A记录返回127.0.0.1。 普通用户应该可以正常使用类似客户端了。<br>
<br>
<li>日期：2014.06.24<br>
暂时去除 appspot.com  的支持，仍然返回google自己的地址。考虑到由于最近每日的流量都非常巨大，为了保障我们的服务稳定，我们需要暂时去掉没必要的中转域名（<a href='http://appspot.com'>http://appspot.com</a> 可能会产生大流量）。<br>
<br>
<br>
<li>日期：2014.06.22<br>
play.google.com解析到美国地址。默认就可以在play上买设备了。<br>
<a href='https://mobile.twitter.com设置三层代理。手机上可以用浏览器访问twitter.com了'>https://mobile.twitter.com设置三层代理。手机上可以用浏览器访问twitter.com了</a><br>
初步修复了安卓平台上的play商店，gmail客户端，以及账户同步功能。（完全顺畅使用还需我们进一步分析处理）<br>
wikipedia.org 可以用http访问，包括下属所有域名。https模式仍有问题。<br>
临时加入chromium.org的加速支持，方便国内的开发者吧！<br>
服务器分流工作初步完成, 现在比较少出现页面打不开的问题。如果还出现的话，请刷新页面即可。<br>

<li>日期：2014.06.20<br>
OpenerDNS 42.120.21.30 公告：从昨天开始由于流量巨大，我们解析到的地址可能会经常的访问断线。未来24小时，我们将加入分流服务器来解决这个问题。请大家及时刷新dns缓存。预计加入分流服务器后，大陆东部地区，联通、电信宽带的访问速度会非常好。<br>
<br>
<li>日期：2014.06.18<br>
针对google所有的服务（youtube暂时除外），提供访问支持。使用OPenerDNS google所有的web服务都可以继续访问，支持http模式，https模式（推荐使用）。<br>
在未来几天中，OPenerDNS: 42.120.21.30 预计可能出现不稳定情况。如果某个google服务无法访问，请告知地址（twitter:@Openervpn）我们将持续修复。<br>
鉴于我们的开发能力，我们现在希望寻找安卓与苹果手机平台app开发商的合作。 将我们的DNS服务通过App来快速设置到安卓与苹果手机上（类似DNS changer）。有意向的朋友mail：a@openervpn.in<br>
<br>