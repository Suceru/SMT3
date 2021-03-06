title: 发布范例
#发布范例

>本范例由百度贴吧-[销锋镝铸](http://tieba.baidu.com/home/main/?un=销锋镝铸){: target="\_blank" }编写

##前言

* 本篇章中范例不是标准，仅供参考
* 建议边制作Mod边撰写Mod介绍

##贴吧发布结构
>在贴吧发布的范例结构

###标题
【日期 Mod】 Mod名称 - 最简短介绍  
>**例** 【6-26Mod】狂拽酷炫吊炸天Mod - 高端大气上档次,低调奢华有内涵

###一楼
一段Mod简单介绍，制作心得等  
附镇楼图，包括工作室Logo、Mod图标、一到三张最吸引人和Mod相关的截图
###二楼
提供下载链接，并提醒不要挖坟，如果下载链接失效请私聊楼主更新链接  
建议将链接放在此楼的楼中楼中，方便链接失效后更新，同时分享的链接打开是一个文件夹而不是文件，这样当Mod更新后阅读者也能从老的发布贴获取文件夹中最新的Mod文件  
>**例** 下载链接在楼中楼，请不要在2018年7月26日之后回复此帖，如果链接失效请私聊楼主更新

###三楼
Mod详细介绍

##详细介绍
###小型功能Mod
####mod名称
除水、岩浆mod
####对应版本
1.27.4至1.28之前全平台所有版本
####发布日期
2015年9月13日
####作者
百度贴吧-销锋镝铸
####mod内容
引爆大炸弹将一定范围内水和岩浆全部炸掉，而不影响其他方块
大炸弹可以直接放置于水中并在水中爆炸
水透明，微弱发光
####修改项目

!!! hint ""
    帮助他人了解、学习mod

* 修改文件`Content.pak\Blocksdata`  
* 修改`WaterBlock(水)`和`MagmaBlock(岩浆方块)`的`ExplosionResilience`为0，`IsExplosionTransparent`为`TRUE(是)`  
* 修改`WaterBlock`的`IsPlacementTransparent(是否放置透明)`为`FALSE(否)`，`ShadowStrength(阴影强度)`为0，`LightAttenuation(光衰减)`为1，`EmittedLightAmount(发光强度)`为10  
* 修改`LargeGunpowderKegBlock(大炸弹方块)`的`IsFluidBlocker(是否阻挡流体)`为`TRUE`，`DefaultExplosionPressure(默认爆炸压力)`为99999  
* 修改除`WaterBlock`和`MagmaBlock`外所有方块的`ExplosionResilience(爆炸抗性)`为`Infinity(无限大)`  

###大型主题Mod
####mod名称
生存战争变态版7.0
####基于版本
Android原版survivalcraft 1.26.7
Windows Phone原版survivalcraft 1.26.6
IOS原版survivalcraft 1.26.9
####发布日期
2015年2月27日
####主要作者
百度贴吧-销锋镝铸
####详细介绍
1. 方块相关  
    * `一般增强` 所有方块可食用，直接在其上睡，不被水冲走（除火和空气），秒破坏，背包一格可容纳99999个  
    * `亮度增强` 南瓜灯、岩浆、矿物、树木、稻子、水、雪、冰、草地、所有人造方块亮度最大；所有透明方块完全透光半透明冰（IOS版无此功能）  
    * `产物增强` 树木、仙人掌、南瓜掉落40，无结晶矿的矿石掉落40矿产物（无需加热），有结晶矿的矿石掉落5结晶矿物，草地、耕地、玻璃、加固的玻璃和窗户掉落本身；破坏火掉宝物生成方块，破坏岩浆掉岩浆桶，破坏基岩掉落基岩；各种浅层矿会在地面生成；钻石矿与煤矿生成位置对调；撸树mod（树木只需要破坏最下面一格整棵树都可以被破坏）  
    * `爆炸增强` 雷管、手雷、小中大炸药桶威力增强，核弹电池（被爆炸间接引爆将产生极强威力的爆炸）；铁块炸不烂  
    * `其他增强` 冰面不打滑；岩浆不可穿过，小麦不可穿过，木牌磁铁彩砖可穿过；火把可堆叠放置  
    * `特别增强` 煤可放置在地面上，形成透视效果；铁锭可放置在地面上，形成透视效果，不可穿过（隐形障碍物）；高草和枯草在条件适宜的情况下可成长为橡树；箱子容积提升至5x6；无限距破坏放置方块（IOS版无此功能）  
2. 工具相关  
    * 工具无限耐久，秒杀除狼人外生物  
    * 可投掷物品超时空（除蛋，手雷,弓箭和弩箭）  
    * 巨型石器（第三人称视角时石制工具非常巨大）  
    * 船在水中不会晃动，更大碰撞箱，速度加大（需缓慢加速），无限耐久  
    * 衣物可叠穿，防御，耐久几乎无限，只需一件即可最大保暖，皮鞋速度+30%，铁鞋速度+80%，钻石鞋速度+120%，累计最大速度为原速度5倍，衣物可食用（饱食度不满时衣物将被吃掉，饱食度满时衣物将被穿上且物品栏仍保留该衣物）  
3. 合成相关  
    * 合成产物除工具类都99；去除燃烧需求（火炉将无法使用，请在手持合成台或合成台内直接按照合成表合成原需燃烧的物品）  
    * 整合“更多合成公式Mod”  
4. 主角相关  
    * `主角属性` 身高提高至1.9格，能跳两格高，空手秒杀除狼人外动物，走路速度小幅提升，可跳两格高，在水中不会摇晃，摔不死，烧不死，主角不会被火烧死,淹不死（会累，所以水下累倒后还是会淹死）;无限距攻击（IOS版无此功能）  
    * `背包增强` 背包升级至5x6(如果在你设备上显示不完全或覆盖在别的按钮上，请把UI SIZE手动调小)；手持合成台容积由2x2提升为3x3，不必另外制作合成台  
    * `出生复活` 主角出生和复活时直接穿着所有衣物(要减速请脱鞋)  
5. 动物相关  
    * `一般增强` 所有动物可无限砸蛋,被骑,加鞍后可驾驭（会因为主动攻击其他生物而失控）；所有动物（除狼人）攻击抗性为99；所有有攻击性动物将互相攻击，甚至自相残杀，所有动物不会主动攻击鸟类；所有食肉动物会吃蛋  
    * `狼人相关` 狼人碰撞箱3格高（防止进房间），攻击抗性999,攻击力33，速度提升，无限追击，可爬楼梯，白天不变回狼，死亡掉钻石块概率100%  
    * `加鞍升级` 野猪加鞍后可控制并进化为超快猪；斑马加鞍可控制并后可以水上漂；虎鲸加鞍后速度翻倍（骑时未知原因奇慢无比）；白海鸟加鞍后攻击一下后成为一直跟随主角的宠物鸟（最后一个蛋可直接砸出）  
    * `其他增强` 神兽全开；奶牛无限产奶；鸟不怕生，可直接靠近；马可飞行，跳得更高，未加鞍马不会自动把骑手抛下  
6. 界面相关  
    * `主要增强` 所有界面半透明化（主要由百度贴吧-_0超新星0_提供，看不清请提高屏幕亮度），字显示更加清楚  
    * `高清增强` 高清雪花，雨，月星，火，蓝火；小船变为黑珍珠，游戏一开始的大船使用高清贴图；采用最新版变态版材质  
    * `准确准星` 生存模式血条显示为5格；主界面logo和底部文字更改；存档加载界面美化；界面背景更改  
7. 其他相关  
    * IOS版应用名SCBT7.0，包名com.SMT.SCBT，与原版共存；WindowsPhone版应用名字生存战争变态版7.0，与原版共存；Android版应用名生存战争变态版7.0，与原版共存  
    * 新增debug视角（debug视角为开发者调试游戏的时候使用的视角，可以让视角脱离玩家，自由穿梭。IOS版无此功能）  

* 温馨提示  
    * 建议设备分辨率至少800x480，部件过大覆盖其他部件请调低UI SIZE  
    * 设备配置过低可能导致游戏无法正常运行，对设备造成损害本人概不负责  
    * 原版游戏存档可在该mod中使用，但该mod存档在原版游戏中可能无法载入  
    * WP版使用部署工具部署时，可能需要把安装包重命名成无中文和特殊符号；IOS共存版安装完成闪退时请尝试卸载后安装覆盖版  
* 特别鸣谢  
    * 由百度贴吧-电离的Tesla 提供的“MOD-无限距离” http://tieba.baidu.com/p/3587877646 以及WP版完善和测试  
    * 由百度贴吧-_0超新星0_ 提供的“更多合成公式Mod”http://tieba.baidu.com/p/3571185807 ，界面半透明化的主要工作，贴图转换，以及WP版完善  
    * 由百度贴吧-tyr2002提供的WP版最终安装包以及测试  
    * 由百度贴吧-lzm956902416提供的WP版完善和测试  
