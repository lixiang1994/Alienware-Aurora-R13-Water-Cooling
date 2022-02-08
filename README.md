# Alienware-Aurora-R13-Water-Cooling

外星人R13主机外置压缩机水冷改装分享

![Cover](Resources/Cover.JPG)


## 起因

先说说由来吧, 我上一个主机是自己组装的 M8I + i7 6700K + GTX1080, 2016年8月份左右, 距今也差不多6年了, 正巧玩`永劫无间`, 游戏优化拉胯, 导致经常60帧到90帧之间跳来跳去, 野外溜达90帧, 附近有人的时候马上60帧 活活的"小雷达", 天人城有三队 那基本上就是60帧以下了, 体验非常糟糕, 一直忍着打到拾月.

恰逢双十一 12代刚刚发布 i9 12900K 看起来非常给力, 于是琢磨是时候该换一套了.

首发的主板和CPU着实难抢, 也恰巧这时候外星人R13发布了, 这一代的外观实在是长在我审美上了(加之我一直对ROG的杀马特灯不感冒), 最终还是没忍住下手了.

其实正常来说新上市的产品应该等等评测之类的, 免得成了小白鼠, 但是外星人的评测简直太少了, 加之我又等不及, 所以这个小白鼠我当定了.


## 问题

众所周知 外星人祖传120冷排已经传承了N代, 对于日常中度使用的用户来说吧, 也只是刚刚够用, 相传外星人的120有魔法, 咱也没用过其他120冷排, 没有数据来论证到底有多大差距.

日常各种3A和永劫无间等游戏, CPU温度大致在70度左右, 显卡满载在79度左右(显存96度上下).

其实这些温度对于一个顶级CPU和350W的显卡来说 还算压得住吧, 刚刚好压住了的感觉 (DELL的设计师真的精打细算啊).

但是大家可能忽略了一点, 70度的CPU, 对于一个120的水冷是需要一个差不多3000转的风扇满速运行才能保持住的水平, 满速!!! 那噪音, 我的天, 我家里仿佛有台喷气飞机...

为了验证这个噪音是如此之大 我特意买了一个测音器 (设置了C加权 较A加权大约高出8分贝左右 仅供参考):

日常待机分贝:

![待机分贝](Resources/待机分贝.JPG)

`永劫无间`时的噪音分贝:

![游戏分贝](Resources/游戏分贝.JPG)

`永劫无间`时近距离的噪音分贝:

![近距离游戏分贝](Resources/近距离游戏分贝.JPG)

`AWCC`风扇拉满的噪音分贝:

![满载分贝](Resources/满载分贝.JPG)

可以看到, 这噪音恐怖如斯, 严重影响日常使用, 那么有人会问了: "机箱放到桌子下面 会不会好一些呢?" 

摆脱~ 都买外星人了, 还放到看不到的地方, 那我为什么不买个普通的主机呢? 对吧.


## 尝试解决

### 解决方案一: 更换猫头鹰风扇

通过各种论坛的搜索和研究, 最终在小红书上发现了一位博主, 他写了几篇关于外星人R13的分享, 其中就有关于更换原厂风扇的文章, 仔细阅读并交流后, 我觉得可以尝试一下.

[小红书文章链接](http://xhslink.com/IS6hNf)

于是乎, 打开了淘宝 放血🩸 直接一步到位 NOCTUA NF-A12X15 PWM * 3:

![猫头鹰风扇](Resources/猫头鹰风扇.JPG)

![猫头鹰风扇开箱](Resources/猫头鹰风扇开箱.JPG)

准备拆风扇! 先看一下原厂风扇

顶部一个

![原厂风扇(顶部)](Resources/原厂风扇(顶部).JPG)

前面两个

![原厂风扇(前置)](Resources/原厂风扇(前置).JPG)

顺便看一眼细节, 风扇是通过胶钉固定在支架上的, 直接可以免工具安装在机箱内, 这个设计真是方便👍🏻

![原厂风扇(正面)](Resources/原厂风扇(正面).JPG)

![原厂风扇和风扇框架](Resources/原厂风扇和风扇框架.JPG)

更换完成!

![猫头鹰风扇和风扇框架](Resources/猫头鹰风扇和风扇框架.JPG)

![猫头鹰风扇特写](Resources/猫头鹰风扇特写.JPG)

安装上去!

![顶部风扇(猫头鹰)](Resources/顶部风扇(猫头鹰).JPG)

![前置风扇(猫头鹰)](Resources/前置风扇(猫头鹰).JPG)

大功告成, 迫不及待的试试结果吧!

emmmm...... 有效果, 但不完全有. 

`永劫无间`时的分贝 (猫头鹰):
![游戏分贝(猫头鹰)](Resources/游戏分贝(猫头鹰).JPG)

`AWCC`拉满时的分贝 (猫头鹰):
![满载分贝(猫头鹰)](Resources/满载分贝(猫头鹰).JPG)

血亏!!!! 

### 解决方案二: 更换硅脂导热垫

经过上面的低性价比尝试后, 我依旧不死心, 于是便有了Plan B.

因为现在都是PWM调速的, 所以如果能将温度降低一些, 是不是就变相的减小了风扇的转速, 从而降低了噪音呢?

哈哈哈哈, 我TM真是个天才!

于是我又开启了降温散热的研究... 终于, 又在小红书的那个博主文章里看到了 [DELL原厂显卡加硅脂](http://xhslink.com/ItbiNf)后, 我决定将我的3080Ti的硅脂和导热垫全部换掉.

又是熟悉的一步到位, 导热垫买的是莱尔德90000, 硅脂是陶熙5888, 懂得都懂 算是顶配了.


![原厂显卡(正面)](Resources/原厂显卡(正面).JPG)

![原厂显卡(背面)](Resources/原厂显卡(背面).JPG)

喜闻乐见 拆拆拆!

![原厂显卡拆下背板](Resources/原厂显卡拆下背板.JPG)

![原厂显卡拆下散热](Resources/原厂显卡拆下散热.JPG)

![原厂显卡拆下匀热板](Resources/原厂显卡拆下匀热板.JPG)

如果你看了文章会发现, 我的显卡匀热板上已经有硅脂了, 和文章中的描述不同, 我猜DELL也意识到了DDR6X的显存散热问题做了优化调整.

不重要, 一点也不耽误我换导热垫.

更换完后 依次装回去, 没啥好拍的, 注意原有的硅脂要清理干净.

![原厂显卡清理硅脂](Resources/原厂显卡清理硅脂.JPG)

直接说结果吧, 当时没截图, (甜甜圈拷机)显存温度下降4度左右, 核心上升3度左右, 是的, 你没看错, 显存和散热器的导热性能变好以后, 核心温度也被带高了, 不过没什么影响, 因为DDR6X的显存温度肯定高于核心温度.

又是血亏的一天, 一顿忙活 降4度... 

总结一下把, 原厂显卡的风冷散热器散热规模不够, 即使用液态金属导热, 温度依旧不会降低太多, 没办法的事儿~ 

同理, CPU也是一样的问题, 再好的导热硅脂也无法有效降低温度.

### 解决方案三: 外置水冷散热 (本文重点)

咳咳~ 上面通过一顿折腾 得到了一个重要结论! __散热规模不足__

于是乎, 某天夜晚, 由于我之前在淘宝中搜索了非常多的散热相关的商品, 首页的推荐突然出现了一个电脑水冷压缩机~, 没错 压缩机! 外置冷排都是弟弟, 好家伙 直接压缩机!

这又打开了我的大门, 既然现在的散热规模不够, 那我直接一步到位???

这一折腾.. 折腾了我半个多月.. 好在结果是令人满意的.

#### 分体水冷

其实我身为一个程序员 对于外置水冷的感觉非常好, 就好像解耦一样, 哈哈 你懂得.

外置也可以接压缩机, 可以接冷排, 可以接各种散热组件, 只要接口一致就OK, 怎么样? 优秀的编程思想来了 哈哈.

现在分体水冷其实并不难搞, 各个商家都有现成的方案, 对着方案把配件买齐了, 到家一步一步组装好就OK了.

但是 我是外星人啊, 他并不是标准的机箱, 主板 电源 机箱 风扇 各种孔位都是定制化的, 这无疑让分体水冷变得非常困难.

同时最关键的是 我还想保留原有的水冷头, 因为这个水冷头才是整个机箱内颜值的灵魂, 是独一无二的.

难上加难, 但并不能阻挡我的折腾决心!

需求:
- 一个PCI挡板 包含进水口和出水口
- 保留原厂水冷头
- 管路美观和简单, 方便维护
- 优先使用金属硬管 (B格高)
- 尽量保留原有的东西 (比如前置第二个风扇导流框)

办法总是有的, 经过一周的苦思冥想, 终于想出了一个看似可行的方案.

- 去掉原有的120冷排, RGB风扇固定到后面的支架上
- 增加一个水箱, 作为原厂水冷头的水源 (原厂水冷头中有水泵, 不能直接将外置的水路连接上, 两个流速不同的泵会冲突, 所以需要有一个水箱来作为缓冲)
- 通过底部PCI穿板进入机箱内部
- PCI进水口连接显卡进水口, 出水口连接水箱
- 水箱的出水口再回到PCI穿板出水口

大体就是这么的思路, 我印象里总共设计了10多套方案, 并行 串行都有, 方案总归是方案, 很多方案在实际测试的时候又被干掉了, 空间太局促, 理想太美好.

最终在不断尝试 推翻 重新尝试的反复挣扎中, 得到了现在的方案 (还有优化空间, 以后再慢慢改进)

下面是具体细节:

##### 水箱

先说说水箱, 找了好久 才找到这么个宝藏, 这水箱的底座简直不要太完美.

![水箱1](Resources/水箱1.JPG)

![水箱2](Resources/水箱2.JPG)

![水箱3](Resources/水箱3.JPG)

来个特写, 看到了没, 底部孔位和前面的孔位是通的, 同时左右的孔位还是被隔开的, 我的天, 完美符合需求.

试想一下, 冷水从底部进水孔流入, 原厂水冷头连接到前面的孔位抽水, 由于流速不同且外置的流速大于原厂水冷头的流速, 所以多余的水会进入水箱内部, 从另一侧的出水孔排除, 而原厂水冷头排出的热水也会从出水孔一起排出, 进出水互不干扰, 水箱相当于缓冲.

对应到编程中, 妥妥一个缓存池好吧, 生产者(进水口)添加冷水, 消费者(水冷头)消耗冷水, 多余的冷水存放到缓存(水箱)中, 出水口(过期清理)不断清理多余的冷水, 这样就保证了消费者永远有最新的冷水可以用, 又不会因为生产者的过剩产量而爆掉, 绝绝子.

![水箱底座特写1](Resources/水箱底座特写1.JPG)

![水箱底座特写2](Resources/水箱底座特写2.JPG)

这个水箱是玻璃的, 不是亚克力的, 很有分量:

![水箱拆解特写1](Resources/水箱拆解特写1.JPG)

![水箱拆解特写2](Resources/水箱拆解特写2.JPG)

![水箱拆解特写3](Resources/水箱拆解特写3.JPG)

![水箱拆解特写4](Resources/水箱拆解特写4.JPG)

这是之前尝试的后置水箱的方案(距离CPU太近 无法走管):

![水箱+后置风扇组合](Resources/水箱+后置风扇组合.JPG)

![水箱+后置风扇组合2](Resources/水箱+后置风扇组合2.JPG)

![水箱+后置风扇组合3](Resources/水箱+后置风扇组合3.JPG)

![水箱+后置风扇组合4](Resources/水箱+后置风扇组合4.JPG)

![水箱+后置风扇组合5](Resources/水箱+后置风扇组合5.JPG)

![水箱+后置风扇组合6](Resources/水箱+后置风扇组合6.JPG)

最终改为了前置水箱:

![水箱+前置风扇组合](Resources/水箱+前置风扇组合.JPG)

![水箱+前置风扇组合2](Resources/水箱+前置风扇组合2.JPG)

这里又有一个问题, 水箱和风扇太近了, 导致原有的第二个风扇的导流框没法安装上了, 为了解决这个问题, 在水箱和风扇直接增了一个14MM高度的支架来调整水箱的位置.

![水箱支架增加14MM间距](Resources/水箱支架增加14MM间距.JPG)

![水箱支架增加14MM间距2](Resources/水箱支架增加14MM间距2.JPG)

这样一来 水箱可以直接放在导流框的上面 又起到了支撑的作用, 两全其美.

再说说原厂水冷头:

##### 水冷头

各种细节照片走一波 不多做介绍了

![CPU一体水冷散热器1](Resources/CPU一体水冷散热器1.JPG)

![CPU一体水冷散热器2](Resources/CPU一体水冷散热器2.JPG)

![CPU一体水冷散热器3](Resources/CPU一体水冷散热器3.JPG)

![CPU一体水冷散热器4](Resources/CPU一体水冷散热器4.JPG)

![CPU一体水冷散热器5](Resources/CPU一体水冷散热器5.JPG)

![CPU一体水冷散热器6](Resources/CPU一体水冷散热器6.JPG)

![CPU一体水冷散热器7](Resources/CPU一体水冷散热器7.JPG)

![CPU一体水冷散热器拆下](Resources/CPU一体水冷散热器拆下.JPG)

吐槽一下外星人的主板, 真TM丐, 我问了技术支持, 他告诉我是9相供电.. 超频? 不存在的.

![CPU卡槽](Resources/CPU卡槽.JPG)

![CPU卡槽特写](Resources/CPU卡槽特写.JPG)

![CPU特写1](Resources/CPU特写1.JPG)

![CPU特写2](Resources/CPU特写2.JPG)

这里有个重要的点, 其实可以无伤拆下水管的, 但是我也是第一次搞, 没有经验, 最终把原本的水管干碎了.
如果你也需要拆水冷 可以问我, 具体细节这里不啰嗦了.

__注意左侧为进水口, 右侧为出水口__

![CPU一体水冷头拆解1](Resources/CPU一体水冷头拆解1.JPG)

![CPU一体水冷头拆解2](Resources/CPU一体水冷头拆解2.JPG)

![CPU一体水冷头拆解3](Resources/CPU一体水冷头拆解3.JPG)

![CPU一体水冷头拆解4](Resources/CPU一体水冷头拆解4.JPG)

![CPU一体水冷头拆解5](Resources/CPU一体水冷头拆解5.JPG)

![CPU一体水冷头拆解6](Resources/CPU一体水冷头拆解6.JPG)

![CPU一体水冷头移除水管1](Resources/CPU一体水冷头移除水管1.JPG)

![CPU一体水冷头移除水管2](Resources/CPU一体水冷头移除水管2.JPG)

![CPU一体水冷头移除水管3](Resources/CPU一体水冷头移除水管3.JPG)

由于水箱架在导流框上, 前孔位对于水冷头来说高了一节, 所以我这里用14MM的偏移接头来解决:

![水箱安装14MM偏移接头](Resources/水箱安装14MM偏移接头.JPG)

将水冷头和水箱连接, 这里用的是内径5mm 外径10mm的水管, 原厂的水管让我干碎了, 太硬了 不好用, 特别提示这水管可不太好淘, 也许可以从海盗船的某个水冷上找找.

![CPU一体水冷头水箱连接](Resources/CPU一体水冷头水箱连接.JPG)

![CPU一体水冷头水箱连接](Resources/CPU一体水冷头水箱连接2.JPG)

需要注意两根水管的长度, 因为90度的相对位置 所以不宜过长, 我这个就有点长了, 稍稍有点折的意思, 以后再调整吧.

大概就是这个样子:

![初步确定水箱+前置风扇组合](Resources/初步确定水箱+前置风扇组合.JPG)


##### 显卡

先看一眼冷头:

![显卡水冷散热器效果图1](Resources/显卡水冷散热器效果图1.JPG)

![显卡水冷散热器效果图2](Resources/显卡水冷散热器效果图2.JPG)

![显卡水冷散热器外包装1](Resources/显卡水冷散热器外包装1.JPG)

![显卡水冷散热器外包装2](Resources/显卡水冷散热器外包装2.JPG)

![显卡水冷散热器拆箱](Resources/显卡水冷散热器拆箱.JPG)

拆下显卡:

![显卡拆下](Resources/显卡拆下.JPG)

一顿拆拆装装:

![显卡水冷散热器安装1](Resources/显卡水冷散热器安装1.JPG)

![显卡水冷散热器安装2](Resources/显卡水冷散热器安装2.JPG)

![显卡水冷散热器安装3](Resources/显卡水冷散热器安装3.JPG)

![显卡水冷散热器安装4](Resources/显卡水冷散热器安装4.JPG)

![显卡水冷散热器安装5](Resources/显卡水冷散热器安装5.JPG)

![显卡水冷散热器安装6](Resources/显卡水冷散热器安装6.JPG)

![显卡水冷散热器安装7](Resources/显卡水冷散热器安装7.JPG)

吐槽一下, DELL的绿色PCB真丑爆了!

另外有个蛋疼的问题, 这个背板比较厚, 导致显卡插上后卸不下来了... 我够不到主板插槽的那个按钮, 谁有解决办法请分享一下 不胜感激.

##### 外置接口

用的是 Watercool PCI Slot Pass-Through

优点: 质量非常好, 看起来也帅
缺点: 真贵


![PCI穿板接口1](Resources/PCI穿板接口1.JPG)

![PCI穿板接口2](Resources/PCI穿板接口2.JPG)

![PCI穿板接口3](Resources/PCI穿板接口3.JPG)

![PCI穿板接口4](Resources/PCI穿板接口4.JPG)

机箱内部用的软管, 空间太小了, 整不了硬管.

![PCI穿板接口安装三分厚软管接头](Resources/PCI穿板接口安装三分厚软管接头.JPG)

![机箱背面接口特写](Resources/机箱背面接口特写.JPG)

提前看一下外置接口的连接吧, 目前这样是没法安上机箱的后磁吸挡板的, 加一个45度的接口应该可以解决, 后面改好后我会更新的.

![机箱背面止水接口连接特写](Resources/机箱背面止水接口连接特写.JPG)

![机箱背面止水接头特写](Resources/机箱背面止水接头特写.JPG)


#### 水冷压缩机

北海冰神的BH08DS

![压缩机散热器正面](Resources/压缩机散热器正面.JPG)

![压缩机散热器背面](Resources/压缩机散热器背面.JPG)

疯狂加水, 水箱还真是大.

![压缩机水箱加水](Resources/压缩机水箱加水.JPG)

加满了就这样了.

![压缩机水箱加满水](Resources/压缩机水箱加满水.JPG)

具体的使用说明有文档, 看看就会了.

------

最终定稿了, 上一个计划是并行水路, 太麻烦了, 还是用的串行.

完成管路安装:

![最终确定串行水路方案](Resources/最终确定串行水路方案.JPG)

![完成管路安装](Resources/完成管路安装.JPG)

严谨的气压测漏一晚上, 指针几乎没动:

![测试气压泄漏1](Resources/测试气压泄漏1.JPG)

![测试气压泄漏2](Resources/测试气压泄漏2.JPG)

压缩机准备完毕, 开始通水测漏:

![通水测漏环节](Resources/通水测漏环节.JPG)

![通水测漏环节2](Resources/通水测漏环节2.JPG)

![通水测漏环节3](Resources/通水测漏环节3.JPG)

非常重要的一点! __排气泡__

- 压缩机水泵运行起来, 将主机左侧朝下, 这样可以让水箱进入更多的水, 保证水箱的水位高于水冷头.
- 断开外置水路连接, 插上主机电源, 将主机背面朝下, 按开机键, 运行冷头水泵, 让水进入水冷头.
- 首次运行时水冷头中存在气泡, 会发出异响, 保持一段时间后异响会逐渐减小, 期间可重复晃动主机帮助排泡.
- 差不多了就可以摆正主机了, 运行几个小时后异响就完全消失了.

完成点亮:

![完成点亮](Resources/完成点亮.JPG)

安装好侧板:

![安装好侧板](Resources/安装好侧板.JPG)

合影:

![完结撒花](Resources/完结撒花.JPG)

## 总结

折腾! 太折腾! 
费钱! 太费钱!

不要碰外星人, 除非你是小白, 小白也不会看到我这个文章, 我又说了句废话.

如果你有R13, 如果你也受不了噪音和散热, 如果你有小一万的闲钱, 如果你愿意花一周时间折腾 (坑我都趟好了, 你只需要一周就够了), 那么欢迎照搬吧, 有问题随时可以交流.


## 结果

附上一些改装前后的跑分和测试结果对比.

改装前, 只能单烤CPU, FPU 1秒降频, 真的秒降, 温度瞬间撞墙.

![OLD-单烤CPU](Resources/OLD-单烤CPU.jpg)

改装后, 注意: 这是单烤FPU, 不是单烤CPU. (因为原厂水冷头管径只有5mm, 流量有限, 所以散热性能上比正经的分体水冷头差, 不过不重要)

![NEW-单烤FPU](Resources/NEW-单烤FPU.jpg)

改装前, 待机:

![OLD-GAMEPP-待机](Resources/OLD-GAMEPP-待机.jpg)

改装后, 待机:

![NEW-GAMEPP-待机](Resources/NEW-GAMEPP-待机.jpg)

改装前, 跑分:

![OLD-GAMEPP-跑分](Resources/OLD-GAMEPP-跑分.jpg)

改装后, 跑分:

![NEW-GAMEPP-跑分](Resources/NEW-GAMEPP-跑分.jpg)

改装前, 压测:

![OLD-GAMEPP-压测](Resources/OLD-GAMEPP-压测.jpg)

改装后, 压测:

![NEW-GAMEPP-压测](Resources/NEW-GAMEPP-压测.jpg)

