# 翻墙与科学上网，中国VPN推荐 - 2019

本文总结翻墙与科学上网工具，介绍VPN，蓝灯、SSR等翻墙软件。免费VPN，免费SSR我就不推荐了，付费VPN中国能用的越来越少，何况免费的。现在没有让你一劳永逸的翻墙工具，也没有完美的科学上网，即使是ExpressVPN也只能做到大概全年97%连通率，个人经验，其它工具更做不到100%。个人建议普通用户用VPN翻墙，本文也优先作中国VPN推荐，非果粉用蓝灯也行。懂技术的人可以考虑SSR，付费SSR节点长期更靠谱。

每年的春节、三月初、六月初、国庆期间、某些突发事件时期都是“**敏感时期**”，基本上在中国使用的所有科学上网工具都会出现频繁断线、连接超时，速度大幅下降等问题，每次持续1-2周左右，过后自动恢复。如果你的学习工作高度依赖国外网站或App，建议提早多准备几个工具，个人经验是VPN+蓝灯+SSR三者的组合基本上可以帮你度过敏感期。非重度翻墙用户如果不想折腾多款工具的，不妨等几天网络恢复，因为其它也没有什么更好的办法。

**这是本文推荐的中国能用的VPN速览：**

* 1 [ExpressVPN](https://indx.cc/exp)：什么都不需要说，我自己用了5年多，市场上最强跨设备通用翻墙软件
* 2 [PandaVPN](https://indx.cc/pandavpn)：新出的服务，目前工作良好，其实**不是VPN而是加密代理**
* 3 [AstrillVPN](https://indx.cc/astrillcn)：低调的厂商，但其实中国一直能用，在中国的老外很多都用这个
* 4 [VyprVPN](https://indx.cc/vyr)：兢兢业业为中国翻墙者服务，不是最强大的，但能用

**最后更新：2019年11月**

`列表可能随时变化，可以收藏本帖，保持关注。`

不要期望单个工具能保证100%连通率，至少每年敏感时期绝对是做不到的。如果你追求全年100%连通率，需要一个工具组合，我自己的组合是：
[ExpressVPN - 基于VPN协议](https://indx.cc/exp) + 蓝灯（或[PandaVPN - 第三方加密代理服务](https://indx.cc/pandavpn)） + [自建SSR - 较私密的加密代理](https://indx.cc/vtr)，基本上前两者就可做到99.5%+的连通率。


# 翻墙软件比较

主流翻墙软件目前就两大类：一是VPN（OpenVPN等多种协议），二是加密代理（HTTPS，SOCKS5），蓝灯和SSR技术上都属于代理类，VPN、蓝灯、SSR各自都有优缺点。

## VPN

### 优点

* **中国政府的政策上留有空间**，特别是OpenVPN协议在商业环境下的广泛使用，使得网络[防火墙](https://zh.wikipedia.org/zh-hans/%E9%98%B2%E7%81%AB%E9%95%BF%E5%9F%8E)无法在协议级别实现完全屏蔽
* 成熟、通用，设备支持更全面，特备是针对路由器等中间网络设备的支持较强，在某些使用场景下没有VPN无法替代
* 个人终端客户端使用友好，基本无需配置，装好就能用，升级全自动
* 节点选择多，商业VPN的服务器遍布全球，虽然绝大部分都不适合中国，但周边的香港、日本等地的服务器集群也足够用

### 缺点

* 传输开销相比代理类协议（如SOCKS5）大，一般认为VPN的连接与传输速度也相对慢一点
* 受打击力度大，国内的服务基本全军覆没，国外的服务能用已经不多，选择越来越少
* 供求关系失衡决定了VPN相对自助翻墙方法成本往往更高
* 达不到全年100%可用标准，至少我还没找到一年365天都能连上的VPN，特殊时期必挂，一般持续约一周

## 蓝灯

### 优点

* 基于SOCK5协议，建立连接快，传输开销比VPN小
* 是商业软件，相比SSR有更好的客服支持
* 有设计良好，好用的客户端

### 缺点

* **不支持iOS设备**
* 只支持自动连接，不适合需要手动控制连接IP的场景
* 隐私保护能力较一线VPN弱

## SSR

### 优点

* 可以选择用商业SSR节点，也可以自己架设，相比VPN更灵活
* 自建SSR服务器，能用的概率比自建VPN服务器能用的概率大很多
* 商业节点或自建服务器硬件要求不高，所以扩展容易、成本低
* 因为基于SOCKS5协议，连接快传输开销相比VPN小，效率高

### 缺点

* 协议开源，长期来说被GFW团队攻破是迟早的事，其实不完全攻破只需解析出流量特征，SSR的死期也就到了
* 缺乏成熟的一体化、友好的部署方案，服务器安装需要一定手动配置，客户端界面可用性比商用VPN软件也还有距离，所以目前SSR主要在电脑技术人员群体中流行

## 总的来说

传统VPN协议因为在商用中高度普及这个非技术原因，完全屏蔽的可能性更小，目前个人用VPN产品在中国能用的虽然已经很少，绝大多数国外VPN厂商也不再投资中国市场，但市场上仍有若干能有效翻墙的VPN，这些商用VPN的客户端的设备支持仍然是最全的，可用性也是最高的。

蓝灯的稳定性和速度都还行，但最大的缺点是没有iOS版客户端，蓝灯自带广告过滤功能，用处不算太大，但聊胜于无，蓝灯不能手选连接节点，只能自动连接，既方便也不方便，如果用户需要用可控的IP地址，建议用付费VPN吧。

SSR的最大优势是可选择的VPS不少，挪窝比较容易，缺点是对技术小白不友好，安装配置不算难，但也足以难道大多数普通翻墙用户，而且**SSR在价格上其实未必比VPN便宜多少**。这里不建议复用网站主机做SSR节点，IP被封后会导致网站本身也无法访问。

# 你该用哪种翻墙软件

**如果翻墙的体验对你很重要，你也不在乎稍微多花点钱**，可以优先考虑一线的付费VPN，**本文下文有好用的中国VPN推荐**。它们都有独立开发的加密混淆技术，穿墙能力很强。这是需要长期投入的技术，免费VPN和绝大多数小付费VPN厂商都没这个预算和技术实力，它们的产品缺乏独立的加密混淆算法，在防火墙的DPI（Deep Packet Inspection）强力侦测面前不堪一击。只有一线VPN厂商才能让你在中国长期稳定地翻墙。绝大多数情况下，买一个靠谱的VPN软件就够你绝大多数时候翻墙用了。

**如果是非iOS用户，也可以考虑蓝灯**，它分为免费版和付费版（Pro），免费版提供每月500Mb的数据流量，客户端大多数时候都可以从Github页面下载。付费版的价格比一线VPN稍便宜，可以从客户端内购升级，付款也不麻烦。不过个人使用的经验，2019年后，蓝灯在中国的翻墙能力有大幅下降，我无法保证在你所在的地区网络上它能有多好用，你可以先试试免费版。

**程序员群体，喜欢自己配置不怕折腾的，可以考虑SSR**，免费SSR节点我不推荐，可以考虑自架或者用购买SSR帐号，现在提供商业SSR节点的第三方越来越多。私有的SSR服务器（多为自架）在敏感时期的穿墙能力可能更强，虽然这也不是100%但私人服务器只要不被侦测到流量特征，更难进入防火墙IP黑名单。**友情提醒：不要散播自架SSR节点。** 除SSR以外，V2Ray，WireGuard，Brook，VMess等翻墙技术也在兴起中，目前来看还比较小众，笔者还没用过这类工具，所以也无从判断它们好不要用，不过这类工具的配置比SSR可能还要复杂，更不适合普通用户。


# 你应该规避的翻墙软件

## 国内VPN

大多数国内VPN都被强制关闭了，但也有的还在以“加速器”的名义在这个不确定的市场里运营着，据我所知，有少数几个还通过了政府审核。**这些国内VPN主要面向游戏玩家群体**，提供游戏加速服务的比较多，官网上也绝不会出现“翻墙”二字。笔者没有用过国内VPN，自从几年前Green VPN被强制关停导致很多用户“放弃退款”以后，我就不再考虑国内VPN服务了，不可抗力下服务终止的风险太大，个人用户容易蒙受损失。我现在只用国外VPN。

## 免费VPN

个人不推荐免费VPN。不是说它们没用，其实不少都能用，至少拿来查收个Gmail没问题。我担心的还是首先是隐私，其次是长期稳定性问题。事实上免费VPN很少披露隐私政策，即使披露也难以让人相信，天下没有免费的午餐，网络服务提供商贩卖用户隐私赚钱不是新闻。另外，我还从没用到过哪个免费翻墙工具很稳定速度很快的，最多也就是开始用的时候还行，但很快随着免费用户的快速增加，服务质量会直线下降。

如果你就是在找免费VPN，百度里基本是搜不到免费VPN的，谷歌可以搜到不少，只是搜到的绝大多数用不了，也有少数能用，此外，安卓官方市场里有很多免费VPN，可以试试，苹果官方（美国）市场也是，如果你的手机能访问这些App应用市场的话。国内大多数手机既没有装Google Play Store，也没有苹果美国市场帐号，所以会比较麻烦。有的APK是可以从第三方市场下载的，可以试试，这个方法能帮你省钱，但很费时间。


## 破解VPN

不要相信什么破解VPN，因为VPN软件都分客户端和服务器端，破解了客户端有什么用呢，服务端算法、服务地址等都会变，破解的客户端机会无法自动获得这些更新，能也往往无法和服务器端同步使用。破解版软件很容易被挂马，带病毒，给你的电脑手机系统带来风险。


# 好用的中国VPN推荐

## 1. [ExpressVPN](https://indx.cc/exp) - 现在买一年送3个月，30天无理由退款

**上次测试：2019年11月20日，确定可用。**

`缺点：一年约97%的连通率，不要期望100%，抱歉。但是，也不要期望哪个工具能做到100%，反正我还没找到`

这是最好用的中国VPN，笔者每次回国必备，用了5年，虽然特殊时期也碰到问题，但一年中97%的时间里使用都很流畅。**ExpressVPN已经为中国网民服务了11年。** 这是目前唯一一个任何人想都不用想就可以买的VPN，连通率应该是最高的，速度相比其他VPN软件也不慢，镜像网站更新最及时，隐私保护技术最好，还有最重要的，客户端最好用，设备支持它最全。


**为什么ExpressVPN是最好用的中国VPN翻墙软件？**

因为他重视中国市场。

世界上的VPN软件成千上万，愿意为中国用户提供镜像站的一只手数得过来，[ExpressVPN的镜像站](https://indx.cc/exp)对中国用户始终保持着可访问（已无法访问）。

客户端好用的VPN不少，但提供无需Google Play Store和苹果美国商店即可安装客户端的VPN厂商，恐怕ExpressVPN是仅有的几家之一。

推荐香港、日本、新加坡、美国节点，提供国内能打开的镜像站，[不翻墙即可购买](https://indx.cc/exp)，真正全终端覆盖，电脑（Windows，MacOS，Linux），手机（安卓，iOS：iPhone，iPad），路由器，游戏主机（PS2，XBox）等，安卓手机无需Google Play也可安装，iOS设备无需访问苹果商店也可安装，同时5台设备，单独配置哪些应用走VPN哪些不走（Split Tunneling） ，**买一年送3个月，30天无理由退款**，[买一年送3个月](https://indx.cc/exp)，支持支付宝付款，支持P2P下载，不限流量。

## 2. [熊猫VPN](https://indx.cc/pandavpn)

**上次测试：2019年11月20日，确认可用。**

`缺点：运营时间还比较短，只支持同时3个连接，且不支持路由器和Linux，缺乏自动重连等职能功能。`

VPN的后起之秀，正在促销，**买一年送一年**，服务器亲测可用，而且很快。产品运营时间还不长，处于推广阶段，价格优惠幅度很大。

支持Windows，Mac，iOS，Android客户端。连接VPN只需要一个开关即可。界面极其简洁，同时3台设备，这是一个让人惊喜的发现，支持智能分流。

**虽然熊猫VPN远没有[ExpressVPN](https://indx.cc/exp)强大，如客户端支持远没有ExpressVPN丰富，同时也只支持3个连接，官方也不披露日志政策**，但对不少人也应该日常够用。从客户端来看，熊猫VPN背后可能不是VPN翻墙技术，而是用了类似SSR的某种加密代理，这无法确定，但是能用最重要。


## 3. [Astrill](https://indx.cc/astrillcn) (该链接需翻墙打开)

**上次测试：2019年11月20日，可用**

`缺点：价格贵，国内须翻墙才可购买，过于低调。`

几年前Astrill是流行的中国VPN，后来墙高了以后，给大家的感觉是Astrill彻底退出中国市场了，从某种意义上来说却是如此，但其实Astrill一直都是中国能用的VPN之一，只不过官方已经停止了任何针对中国市场的营销，你在国外各中文网站上也极少看到对Astril VPN的推荐，而且目前从国内貌似无法直接买到它，所以上面的链接需要翻墙才能访问，不得不说这使得Astrill对绝大多数中国翻墙网民来说不友好了。

但也有例外。如果你此刻人在国外，打算回国探亲或者工作，可以提前在国外买好Astrill带回国使用；如果你在国内但已翻墙，也可以考虑购买Astrill。它其实一直都能用，只是特别低调而已。


## 4. [VyprVPN](https://indx.cc/vyr)

**上次测试：2019年11月20日，确定可用。**

`缺点：中国必须用变色龙版本，但这个版本不支持iOS。`

**记得一定要购买高配（较贵）的那个，低配的不包含变色龙协议，中国用不了。很可惜高配版不提供iOS客户端，如果你要iOS翻墙，建议还是买ExpressVPN吧。使用的时候，务必在配置里打开变色龙协议，否则是连不上的。**

推荐台湾、韩国，香港、日本、新加坡、美国等地节点，不用翻墙国内可以购买，独家变色龙混淆协议 ，同时5台设备，30天无条件退款，支持支付宝付款，支持P2P下载，不限流量。

VyprVPN是我确定中国能用的VPN软件，台湾、韩国的节点出奇地快。VyprVPN的价格低于ExpressVPN，对于觉得ExpressVPN太贵的用户，我推荐你用VyprVPN。

一分钱一分货，VyprVPN的设备支持，可用节点少（对中国用户）没有ExpressVPN强大。


# 在中国使用VPN的几个问题

## VPN购买

一线VPN如ExpressVPN都能直接从国内直接买到，不必先翻墙。

主流VPN厂商都至少支持支付宝，很多也支持银联，有人可能担心用国内支付方式会泄露个人信息。如果你从国内vpn厂商哪里购买，很有可能，但国外vpn厂商不受中国法律监管，而且国外vpn厂商对账单抬头都做了处理，即使不处理也不必担心，中国vpn用户至少几百万，只要你不提供分发下载，个人平时正常上网学习是没问题的。支付都是和个人信息绑定的，除非你用比特币支付，否则现行金融系统中的任何交易都可以被追踪，用支付宝和信用卡的可追溯性是相同的，既然如此，不必杞人忧天。

有些vpn厂商提供免费试用，有的要绑定信用卡，有的不需要，如果要绑定信用卡，也不用过分担心，通常你注册的账号里都会有“取消订阅”的功能，如果没有，也可以联系客服，让他们帮忙取消。更多的厂商提供的是无条件退款服务，vpn购买者对产品有任何不满意，都可以要求退款，通常这需要联系客服或使用官方提供的其他联系方式，退款一般需要几天到账。


## 服务器选择

香港到大陆的ping值是最低的（小于100ms），如果软件提供，应该是最优质的翻墙节点。日本（100ms至200ms之间），美国（200ms以上），新加坡（200ms以上），都是连接稳定速度较好的VPN节点。提供台湾节点和韩国节点的VPN不多，我自己的感觉，连上的时候很快，但经常连不上，不知道什么原因。

如果VPN有自动推荐最快服务器功能，多数情况只要用它推荐的就可以了。在特殊时期，近中国大陆的香港、日本节点连通率低，这时候美国、英国，甚至澳洲的连通率反而高，可以优先试试。


## 断线怎么办

没有100%稳定的VPN，每年特殊时间段（如六月初）的连接质量都不好，容易断线，这不是某个VPN的问题，所有的翻墙软件都会这样，一般到六月中就会完全恢复。

日常使用，偶尔断线，换服务器重连即可。

即使是同一个服务，在一天不同时段，或在不同地域访问，服务质量也会不同，如果你带着小飞机全国各地跑，也是一样，这是由当地网络状况决定的。

网上说的什么某个VPN软件看[油管](https://www.youtube.com)一年365天一天24小时都能1080P，是不可信的。但一线VPN让你连上能稳定流畅地观看720P的视频应该没问题。

## 敏感时期如何度过

个人经验。**这时候香港、日本等近中国大陆的节点连通率会很低，反而美国、英国，甚至澳大利亚的节点反而容易连上**。

可以提前准备多个工具，这是目前我能找到的最可靠的方法。关注VPN厂商的邮件列表，提前询问客服，确定对方是否会近期推出“特殊版本”的软件更新。

# 各设备翻墙最佳姿势

## 全设备翻墙

目前市场上还没有比[ExpressVPN](https://indx.cc/exp)支持设备更多的翻墙软件，VyprVPN（变色龙版）不支持iOS，蓝灯不支持iOS，熊猫不支持路由器，其它一线的VPN也都有遗漏，只有ExpressVPN，基本从头到脚支持所有市场上你能找得到的设备类型，所以它应该是全设备通用翻墙的首选工具。

## 电脑翻墙

电脑上VPN，蓝灯，SSR都是可行的方案。对小白来说，VPN和蓝灯的客户端省去配置的麻烦，花钱省时间。如果懂技术，SSR也不错。

## 安卓翻墙

安卓手机上，VPN和蓝灯翻墙都不错。看个人习惯，SSR也可以用，只是好用的客户端安装配置可能要花点时间。友情提醒一下，**尽量不要在第三方安卓市场上下载安装所谓“终身免费VPN”**，警惕这类软件钓鱼，在你的手机窃密。

## iOS翻墙

iPhone、iPad等iOS上翻墙，VyprVPN和蓝灯是用不了的，你的在几个一线VPN或者SSR方案里选，这些VPN中国苹果手机上都能用。如果选SSR，可以考虑买知名的ShadowRocket客户端。

## 路由器翻墙

我还没看到那款科学上网工具能支持所有制式的路由器的，我想未来也不会有。在你决定要用路由器做翻墙网关前，要看清楚你选择的翻墙软件支不支持你的路由器型号，我建议以[ExpressVPN](https://indx.cc/exp)支持的路由器列表为参考（如果它不支持，其它工具也大概率不会支持），如果不支持，你得考虑购买兼容的路由器型号。

## 智能电视翻墙

不管是Apple TV，还是各种安卓电视（小米盒子、天猫盒子、FireTV），本质上它们仍然是安装了iOS或Android操作系统类手机设备，看前面的安卓和iOS翻墙。

## 游戏主机翻墙

能支持游戏主机（PlayStagion，Xbox，Nintendo Switch）的翻墙工具本来就很少，能支持多种此类设备的就更是凤毛麟角，目前对游戏设备支持最好的科学上网工具，是[ExpressVPN](https://indx.cc/exp)。

# 蓝灯介绍

## 蓝灯不是VPN

蓝灯不是VPN，基于SOCKS5协议的加密代理，技术上和ShadowSocks接近。如果网上有人告诉你有蓝灯VPN可以下载，基本都是钓鱼的下载链接，蓝灯就是一个代理翻墙工具，只不过客户端自动化了代理设置的很多细节。

代理类科学上网工具的优缺点：建立连接的速度一般比传统VPN快，理论上SOCKS协议的传输开销比VPN小，速度比VPN快，缺点是没有VPN作为底层协议那么通用，而且隐私保护的强度没有用付费VPN翻墙那么强。

## 蓝灯优缺点

蓝灯相比传统VPN的优缺点：连接速度确实很快，ExpressVPN平均可能需要几十秒才能建立连接，但蓝灯基本是秒连，不过我用两者分别看Youtube并感觉不到速度差距。设备支持上，蓝灯提供Windows，MacOS，安卓客户端，下载安装方便，有中国可访问的[github](https://github.com/getlantern/lantern)页面，国内应该可以直接下载到蓝灯客户端，安装后可以使用免费版，用户可以在客户端里购买蓝灯专业版，支持支付宝付款，比较方便。

蓝灯内置了两个比较有用的功能，一个是自动检测被墙网站并配置智能连接，只对这些网站应用科学上网，另一个是广告拦截，自动过滤掉各类广告和追踪请求，也很实用。

**但是很可惜，蓝灯不支持iOS** :((

## 专业版

蓝灯有免费版和专业版，免费版每月500M流量，蓝灯专业版的的价格也不贵。免费版很有用，可以拿来临时翻墙以此为跳板下载各类付费科学上网工具。蓝灯专业版是从客户端内购的，可以支付宝付款。

不管是免费版还是专业版，**蓝灯都不提供手动连接**，连哪里是完全由客户端自动管理的，这对有的人来说是个优点，但对需要特定地区连接节点的人（比如需要特定IP的外服游戏玩家）来说，非常不好用。

## 破解版

提醒一下：网上如果流传所谓**蓝灯破解版**千万别下，小心挂马。蓝灯是需要客户端和服务器端协同才能正常翻墙的软件，下到一个所谓破解版是不可能可用的，一定是骗人的。把所谓破解版装到电脑上会对系统带来安全隐患。

## 优惠码

最后附上蓝灯优惠码：**NQGP7F**。想买的朋友可以用。再次提醒：**蓝灯不支持iOS设备**，有iOS设备的朋友，用VPN翻墙工具是最好的办法。


# SSR科学上网

SSR，又称“小飞机”，或“影梭”，是[ShadowSocks](https://shadowsocks.org/en/index.html)的后续版本，目前仍保持着更新（原项目黄了）。

这种方法也是完全可行的，国内很多人用，现在最常见的SSR，也有小众用户用V2Ray，WireGuard等技术，总的来说SSR够用。

用得最多的VPS是[Vultr](https://indx.cc/vtr)和[搬瓦工](https://indx.cc/bwg)，网上不少人反应IP被封，但也有很多人自己搭建的SSR稳定用很久的，所以这里有运气成分。

自己搭建SSR并不比买VPN便宜，即使便宜其实也很有限，主要还是VPS厂商经常送新注册用户试用金，所以感觉上一开始不用花钱，大家觉得便宜，最便宜的VPS如Vultr的2.5美金每月的，也和一些VPN的价格差不多，VPS普遍的低配机价格是5美金或以上的。

要有IP被封的心里准备，好在现在的VPS换IP都不麻烦，大不了做个镜像重新开一台机会拿到新IP。不过并不是所有的换IP都免费，如果考虑换IP的成本，**搭建SSR的成本未必比其它方法低**。


# 翻墙须知

## 墙并没有那么高

国内网名觉得墙很高，其实每年除了少数几个时段外，用VPN或SSR翻墙并不难，虽然也谈不上特别容易，毕竟购买VPN或者搭建SSR都要费时间费钱。很多人觉得科学上网难，大概就是几类原因。首先就是不想花钱，整天找免费的东西，免费VPN，免费SSR节点分享，免费的东西很多，也有一些确实能用的，但几乎所有免费服务最终都是很难或不可用的。绝大多数免费的VPN或者SSR节点，公网上随便一搜就搜得到，你能看到墙也能看到，多数都很短命。其次就是懂点技术的网民的那一点偏执，觉得自己架设的东西最好，不相信第三方更专业的付费服务。国内很多人用香港、日本等地的主机来搭SSR，有不少确实是稳定地用着，但也有不少IP被封，不得不折腾换IP、换主机的。所以它们觉得翻墙很难。

其实翻墙只需要准备一两个工具就行了，像我自己就常备[ExpressVPN](https://indx.cc/exp)和[蓝灯](https://indx.cc/lantern)，用了好几年了，除了少数敏感时期两个都挂掉以外，其余时间基本可以保证100%翻墙成功率，绝大多数时候我用ExpressVPN，虽然每天都会有几次断线重连，但极少碰到连不上的情况，最糟糕的情况也就是换个节点连一下，香港的如果连起来慢了，就换洛杉矶的，洛杉矶的慢了，就换日本、新加坡的等等。蓝灯用来作备份，因为价格便宜，但没有ExpressVPN强大，有了这两个软件，我从来没担心过无法科学上网的问题。剩下的，就是保持两个工具的更新，这是同时安装两个翻墙软件的好处，主要是为了当一个软件版本过期无法连接的时候，另一个还能连上让它更新。

## 为何翻墙？

翻墙是为了不影响学习与工作，不是去诋毁中国和中国人。

你要明白世界的媒体是受西方控制的，舆论战里众多西方媒体是进攻的一方，而非西方阵营的国家只能选择防守，我们不说墙的存在对你我个人是好或不好，方便与不方便，如果说这个，当大概是不好也不方便，但也得明白防火墙存在在政治与国家安全上的‘合理性’。比如Facebook被封的原因：

> 由于乌鲁木齐七·五骚乱部分新疆独立运动者使用Facebook为交流平台，引起中国大陆封锁Facebook至今。

绝大多数西方媒体都带有浓烈的意识形态企图，它们绝对不是“公正中立”的，明白这一点的中国人会越来越多。[选择性报道，恶意扭曲的例子并不少](https://user.guancha.cn/main/content?id=29826)，甚至一度还有“中国共产党镇压狗”的奇葩新闻，西方媒体说谎作恶，无所不用其极。翻墙绝对不是为了去做西方媒体的喉舌，你只要被绕进去，就很难看到全部的事实了。翻墙是首先是为了不影响个人学习与工作，其次是为了更好地学习和工作，还当然有娱乐：）Googe，Youtube，Facebook，Twitter上都有大量有益的信息可以看。况且前面说了，对个人来说，墙的门槛实际上并没有你想的那么高，墙的存在并不能阻止你获得这些信息。

不要假设“翻墙后”的必然选择是搞些猎奇反动的事情，翻墙后有很多有趣、有意义的东西可以看。有一些免费翻墙工具背后是美国国会支持的，典型代表是曾经流行的自由门，就有美国国会几百万美金的拨款，自由门绝对不是唯一一款，这种免费VPN会向用户不停推送反动信息，好在几年前被封了。

## 翻墙是否违法

如果翻墙违法，那中国政府就有几千万人要抓，经济上没有可行性。如果强制立法翻墙违法，中国政府也不会不知道其中的政治代价，除非它想让中国整个进入黑暗时代。所以基本上个人翻墙违不违法是个伪命题，日常翻个墙查个Gmail，看个Youtube没必要提心吊胆，不要被网络上所谓“翻墙罪”危言耸听蛊惑。

**绝不要分发分享自建VPN，SSR机场，脚本等**

国内有些小朋友看到搭建SSR这么容易，就去建机场，这是典型的作死，可以自行去搜机场主或者站长被请抓的新闻。个人VPN，SSR你自己用，请保持低调。不要到微信、微博这些地方去分发，除非你很想喝茶。分发分享自建VPN，SSR机场是犯法的。 看下面这些事件：

**2019年3月，翻墙技术网站“逗比根据地”站长被起诉：**

“逗比根据地”是一个提供翻墙技术的中文网站。2018年底，该网站创始人孙东洋（网名Toyo Sun）在国内被捕。在被关押5个多月后，孙东洋于2019年3月25日被以“提供侵入计算机系统工具罪”起诉。

**2019年1月，重庆网民因使用VPN受到指控：**

2019年1月，据网络流传的图片显示，重庆市荣昌区公安局对一名使用VPN的网民黄某的家属进行了传唤。

**2019年1月，广东网民因使用VPN被罚款：**

2019年1月，广东一位朱姓网民因为“擅自建立、使用非法定信道进行国际联网”被韶关市公安局警告并罚款1,000元人民币。文件显示：朱某从2018年8月到12月，在自己手机上多次使用翻墙软件蓝灯（Lantern Pro）。这是一次因个人使用VPN被罚的事件。

## 隐藏IP地址

连上VPN后，所有流量都走VPN软件提供的线路，相当于在本机与VPN远程服务器之间建立起一条秘密通道，入口是本机端口，出口是服务器某个端口，对被访问的网站等服务来说，直接访问者是远程服务器，从而达到隐藏本机IP地址的目的。

隐藏IP地址即是保护隐私的需要，在需要访问有IP限制的服务时（如Netflix只允许部分国家的IP访问）也非常有用。

## [DNS泄漏保护](https://en.wikipedia.org/wiki/DNS_leak)

上面说了VPN会在本机和远程服务器间开辟隧道，让流量同行，通常指的流量是数据流量，比如下载网页，DNS泄露保护，是将本机对网站域名的访问请求（转化为IP）也走VPN通道的保护机制，它最大限度地保护用户隐私，否则网络中间商就可以侦测到你的机器都访问了哪些域名，有了DNS泄露保护，网络中间商就无法嗅探到你的网站访问记录了。

## 混淆协议

单纯的VPN协议如OpenVPN虽然也有加密算法，但在GFW防火墙面前也不堪一击。所以好的VPN软件都会单独开发混淆协议。混淆的作用就是把VPN流量尽可能搞得不像VPN加密流量，骗过墙的侦测算法，更有效地帮助用户翻墙。

ExpressVPN，VyprVPN等软件都开发了商用混淆协议，这是这类软件比普通VPN更稳定的原因。

## 什么是智能连接（Split Tunneling）

当你连上VPN软件后，默认所有流量都走VPN连接，这会导致访问中国国内网站（如知乎、百度、微博、优酷等）变慢。Split Tunneling允许你指定那些应用程序不走VPN线路，如在[ExpressVPN](https://indx.cc/exp)内，你可以配置Firefox浏览器不走VPN，Chrome浏览器走VPN，这样访问国内站点时用Firefox，访问国外站点时用Chrome，国内外网站访问速度都能达到最优。
