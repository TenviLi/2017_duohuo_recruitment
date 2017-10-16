# 这是 啊哈呵嗨 的自我介绍

## 基本信息

My Name is **李典**

**17** 岁（But 身份证上填的日期是199908）

来自 貌似很穷的 **江苏连云港**

1. 是一个 **逗比**
2. 有点儿 **怕生、腼腆**（我在努力克服= 。=） ，但是和熟人在一起 **异常活泼**
3. **好奇心爆棚** 喜欢学习新的知识♂ 喜欢尝试各种有趣♂的事物
4. **幽默** 喜欢从学到的、日常接触到的各种事物中**找梗**
5. **乐观** 心情沮丧时一般2h之内恢复
6. emmmmm 我很 **纯洁** 的
7. **努力学习 争分夺秒ing**

## What's I have experienced

### 小学时参加好多科技竞赛，有4个专利
![](http://ww4.sinaimg.cn/large/0060lm7Tly1fkjscx9fgjj30qo0zkgoi.jpg)
**徐正文徐老师** 是我对 科技产生兴趣的 启蒙老师，
小学的后三年，（我在一个 一不听话或者莫名其妙 被挨打的封建家庭中），**徐老师是我小学时的精神源泉**，
他一直鼓励着我。我甚至旷课，整天跑到他那里去。
我参加了许许多多的科技活动，还绞尽脑汁搞发明。
因此**成就感是我的第二个精神源泉**


### Discuz!小小开发者一枚
![](http://ww2.sinaimg.cn/large/0060lm7Tly1fkjscvomqtj303l01ua9w.jpg)

*//就当是写自传了,好久都没有回忆起这些了，好怀念QAQ*

**6年级（2011年）** 的时候我便萌发出了建立论坛的想法

百般网站之中 我找到了 **5d6d免费论坛**（PS:**尽管** 免费论坛这个字很羞耻）

起初 为了使论坛更加美观 我找到了 **菜鸟基地**、**Dzcode**、**弘树** 等网站

（PS:由于免费论坛 无法通过ftp上传插件 只能用前端的代码替代 事实上 会搞得客户端卡得不得了 但是当初前端就是那样模模糊糊 不像现在那样那么多变态的玩意儿）

这些代码一般放在后台的`头部`、`第三方`等设置项中

在不到一年的使用中 我早已熟悉了DZ后台的**各种操作** 

直到有一天 我终于观察到 **菜鸟基地** 的`每日签到第一版`的这个代码（PS:以现在的眼光来看 当初的这些代码lowB的不得了）
```html
<script>
    if (location.href == "你的论坛签到板块发帖地址") {
        $("nav").innerHTML = "签到页面";
        var uname = $("umenu").getElementsByTagName("a")[0].innerHTML;

        function $post_a() {
            setcookie("sign_你的论坛域名前缀", "already", 86400, cookiepath, cookiedomain);
            $("subject").value += uname;
            $("subject").value += "的签到记录贴";
            $("e_textarea").value += "[quote]    本贴是论坛每日签到系统在签到者签到时所自动生成的[/quote]";
            $("e_textarea").value += "[quote][b][color=DarkOrange][size=3][font=微软雅黑]";
            $("e_textarea").value += uname;
            $("e_textarea").value += "于";
            $("e_textarea").value += new Date();
            $("e_textarea").value += "完成了签到[/font][/size][/color][/b][/quote]";
            $("e_textarea").value +=
                "[quote]TA选择了[size=5][b][color=SeaGreen][开心][img]http://amenu.tk/biaoqing/kx.gif[/img][/color][/b][/size][/quote]"
            $("e_textarea").value += "[quote]同时TA想说:"
            var otxt = prompt("填入你想说的话", "") $("e_textarea").value += otxt;
            $("e_textarea").value += "[/quote]"
            $('postsubmit').click();
        }

        function $post_b() {
            setcookie("sign_你的论坛域名前缀", "already", 86400, cookiepath, cookiedomain);
            $("subject").value += uname;
            $("subject").value += "的签到记录贴";
            $("e_textarea").value += "[quote][b][color=DarkOrange][size=3][font=微软雅黑]";
            $("e_textarea").value += uname;
            $("e_textarea").value += "于";
            $("e_textarea").value += new Date();
            $("e_textarea").value += "完成了签到[/font][/size][/color][/b][/quote]";
            $("e_textarea").value +=
                "[quote]TA选择了[size=5][b][color=SeaGreen][难过][img]http://amenu.tk/biaoqing/ng.gif[/img][/color][/b][/size][/quote]"
            $("e_textarea").value += "[quote]同时TA想说:"
            var otxt = prompt("填入你想说的话", "") $("e_textarea").value += otxt;
            $("e_textarea").value += "[/quote]"
            $('postsubmit').click();
        }

        function $post_c() {
            setcookie("sign_你的论坛域名前缀", "already", 86400, cookiepath, cookiedomain);
            $("subject").value += uname;
            $("subject").value += "的签到记录贴";
            $("e_textarea").value += "[quote][b][color=DarkOrange][size=3][font=微软雅黑]";
            $("e_textarea").value += uname;
            $("e_textarea").value += "于";
            $("e_textarea").value += new Date();
            $("e_textarea").value += "完成了签到[/font][/size][/color][/b][/quote]";
            $("e_textarea").value +=
                "[quote]TA选择了[size=5][b][color=SeaGreen][郁闷][img]http://amenu.tk/biaoqing/ym.gif[/img][/color][/b][/size][/quote]"
            $("e_textarea").value += "[quote]同时TA想说:"
            var otxt = prompt("填入你想说的话", "") $("e_textarea").value += otxt;
            $("e_textarea").value += "[/quote]"
            $('postsubmit').click();
        }

        function $post_d() {
            setcookie("sign_你的论坛域名前缀", "already", 86400, cookiepath, cookiedomain);
            $("subject").value += uname;
            $("subject").value += "的签到记录贴";
            $("e_textarea").value += "[quote][b][color=DarkOrange][size=3][font=微软雅黑]";
            $("e_textarea").value += uname;
            $("e_textarea").value += "于";
            $("e_textarea").value += new Date();
            $("e_textarea").value += "完成了签到[/font][/size][/color][/b][/quote]";
            $("e_textarea").value +=
                "[quote]TA选择了[size=5][b][color=SeaGreen][无聊][img]http://amenu.tk/biaoqing/wl.gif[/img][/color][/b][/size][/quote]"
            $("e_textarea").value += "[quote]同时TA想说:"
            var otxt = prompt("填入你想说的话", "") $("e_textarea").value += otxt;
            $("e_textarea").value += "[/quote]"
            $('postsubmit').click();
        }

        function $post_e() {
            setcookie("sign_你的论坛域名前缀", "already", 86400, cookiepath, cookiedomain);
            $("subject").value += uname;
            $("subject").value += "的签到记录贴";
            $("e_textarea").value += "[quote][b][color=DarkOrange][size=3][font=微软雅黑]";
            $("e_textarea").value += uname;
            $("e_textarea").value += "于";
            $("e_textarea").value += new Date();
            $("e_textarea").value += "[quote]完成了签到[/font][/size][/color][/b][/quote]";
            $("e_textarea").value +=
                "TA选择了[size=5][b][color=SeaGreen][怒][img]http://amenu.tk/biaoqing/nu.gif[/img][/color][/b][/size][/quote]"
            $("e_textarea").value += "[quote]同时TA想说:"
            var otxt = prompt("填入你想说的话", "") $("e_textarea").value += otxt;
            $("e_textarea").value += "[/quote]"
            $('postsubmit').click();
        }

        function $post_f() {
            setcookie("sign_你的论坛域名前缀", "already", 86400, cookiepath, cookiedomain);
            $("subject").value += uname;
            $("subject").value += "的签到记录贴";
            $("e_textarea").value += "[quote]这是由每日签到者签到自动生成的帖子[/quote]";
            $("e_textarea").value += "[quote][b][color=DarkOrange][size=3][font=微软雅黑]";
            $("e_textarea").value += uname;
            $("e_textarea").value += "于";
            $("e_textarea").value += new Date();
            $("e_textarea").value += "完成了签到[/font][/size][/color][/b][/quote]";
            $("e_textarea").value +=
                "[quote]TA选择了[size=5][b][color=SeaGreen][擦汗][img]http://amenu.tk/biaoqing/ch.gif[/img][/color][/b][/size][/quote]"
            $("e_textarea").value += "[quote]同时TA想说:"
            var otxt = prompt("填入你想说的话", "") $("e_textarea").value += otxt;
            $("e_textarea").value += "[/quote]"
            $('postsubmit').click();
        }

        function $post_g() {
            setcookie("sign_你的论坛域名前缀", "already", 86400, cookiepath, cookiedomain);
            $("subject").value += uname;
            $("subject").value += "的签到记录贴";
            $("e_textarea").value += "[quote][b][color=DarkOrange][size=3][font=微软雅黑]";
            $("e_textarea").value += uname;
            $("e_textarea").value += "于";
            $("e_textarea").value += new Date();
            $("e_textarea").value += "完成了签到[/font][/size][/color][/b][/quote]";
            $("e_textarea").value +=
                "[quote]TA选择了[size=5][b][color=SeaGreen][奋斗][img]http://amenu.tk/biaoqing/fd.gif[/img][/color][/b][/size][/quote]"
            $("e_textarea").value += "[quote]同时TA想说:"
            var otxt = prompt("填入你想说的话", "") $("e_textarea").value += otxt;
            $("e_textarea").value += "[/quote]"
            $('postsubmit').click();
        }

        function $post_h() {
            setcookie("sign_你的论坛域名前缀", "already", 86400, cookiepath, cookiedomain);
            $("subject").value += uname;
            $("subject").value += "的签到记录贴";
            $("e_textarea").value += "[quote][b][color=DarkOrange][size=2][font=微软雅黑]";
            $("e_textarea").value += uname;
            $("e_textarea").value += "于";
            $("e_textarea").value += new Date();
            $("e_textarea").value += "完成了签到[/font][/size][/color][/b][/quote]";
            $("e_textarea").value +=
                "[quote]TA选择了[size=5][b][color=SeaGreen][慵懒][img]http://amenu.tk/biaoqing/yl.gif[/img][/color][/b][/size][/quote]"
            $("e_textarea").value += "[quote]同时TA想说:"
            var otxt = prompt("填入你想说的话", "") $("e_textarea").value += otxt;
            $("e_textarea").vakle += "[/quote]";
            $('postsubmit').click();
        }
        $("wrap").innerHTML += "<center>";
        $("wrap").innerHTML +=
            "<div class='showbq' onclick='$post_a()'><img src='http://amenu.tk/biaoqing/kx.gif'/><br>开心</div>";
        $("wrap").innerHTML +=
            "<div class='showbq' onclick='$post_b()'><img src='http://amenu.tk/biaoqing/ng.gif'/><br>难过</div>";
        $("wrap").innerHTML +=
            "<div class='showbq' onclick='$post_c()'><img src='http://amenu.tk/biaoqing/ym.gif'/><br>郁闷</div>";
        $("wrap").innerHTML +=
            "<div class='showbq' onclick='$post_d()'><img src='http://amenu.tk/biaoqing/wl.gif'/><br>无聊</div>";
        $("wrap").innerHTML +=
            "<div class='showbq' onclick='$post_e()'><img src='http://amenu.tk/biaoqing/nu.gif'/><br>怒</div>";
        $("wrap").innerHTML +=
            "<div class='showbq' onclick='$post_f()'><img src='http://amenu.tk/biaoqing/ch.gif'/><br>出汗</div>";
        $("wrap").innerHTML +=
            "<div class='showbq' onclick='$post_g()'><img src='http://amenu.tk/biaoqing/yl.gif'/><br>慵懒</div>";
        $("wrap").innerHTML += "</center>"
        document.writeln("<style>");
        document.writeln(".main{display:none}");
        document.writeln("</style>");
        if (getcookie("sign_你的论坛域名前缀") == "already") {
            $("wrap").innerHTML = "<center><b>您已经签到了,无需再次签到</b></center>";
        };
    }
</script>
<style>
    .showbq {
        float: left;
        margin: 30px;
    }

    .showbq:hover {
        border: #ffca41 dotted 2px;
        background: #efefef
    }
</style>
```
改改代码文字 发现居然显示的文字会变化

于是从此**便一发不可收拾**

[w3school](http://www.w3school.com.cn/)是我的代码启蒙网站，学习了上面极其入门的`html`、`css`、`JavaScript`，当初超有成就感的。。。

（PS:用到什么就学什么，当初甚至连`jQuery`都用上

**到了2012年**，我终于成为**菜鸟基地**的一枚**斑竹**了，年幼之时，对这种虚幻的名号也特有成就感，或许成为斑竹便是我 快速提高编程技能的开始。从**版主**到**管理员**,我解答了许许多多用户的问题

认识了**许许多多许许多多**的小开发者们（PS:当初有大学生，也有像我这样的初中生），其中**叶晨**（6年）、**廖晗**（5年）、**弘树**（4年）、**章鱼**（4年）等人，成为了我的挚友。

这一年是激动人心的一年，那个**Dzcode**创造了**云插件的概念**，就是使用**Dzcode**的产品前需要在`头部`中引用他们的`Core.js`（PS:原理其实就是里面定义了一堆5d6d常用的一些代码，然后封装了方便小开发者们开发的函数，然后最重要的是调用 用户在他们平台上生成的js、css文件，其实这种东西的出现是非常方便的，就不再需要小白用户去复制粘贴一大堆冗长的代码了）

**Dzcode**是一堆高中生开发者组成的**团队**，在当初我的眼里他们都是大佬，我想加入他们。

我找到以前我回答问题过的站长 模仿Dzcode建立了团队**Dzavly** 但其实还是单打独斗

网站每日在线量也就最多3 4个而已

直到遇到了**叶晨**，当初他建的那个站 专门制作Discuz!的模板和风格，做得都非常非常漂亮。他还有个论坛叫**Serves**，他转让给了我。于是 我的新团队就叫**Serves**了（最棒了），自此 又是一个 更加快速提高编程技能 开始。
**廖晗**（其实也是**Dzcode**的成员）邀请我加入**Dzclub**这个团队，发布了十多个代码吧，半年过去了他也快中考了，于是**Dzclub**让给了我，十多个团队成员也分道扬镳解散了，于是**Dzclub**就没了）

编了许许多多的代码 也仿制过许许多多的网站（变成**Disucz!7.2**可以使用的风格或模板），我也学习到了好多好多。

什么`json`、`Ajax`之类的，代码越来越熟练。（PS:但是我记不全那些语法、自带函数，一般做代码就疯狂百度）

`Serves`的用户也多了起来，日在线用户20多了，成就感MAX，初中中午一回家就是敲电脑。

（2013年了 `Dzcode`那所谓的云平台也到第四版了，但是**Dzcode**的创始人**Qwin**等成员 即将高考，**Dzcode**倒闭）

还好我一直保存了各种小团队们发布的代码，连`Core.js`，都给全部存在了360云盘上。（2017年寒假 **360云盘** 倒闭，还好我把当初的东西都给下载好了）

2012年~2013年的同时我还发现哦，**5d6d**用的论坛程序是**Disucz!** 于是乎我就入了`拍簧片【误】`的大坑...

顺理成章的成为了应用商店的一个开发者（只发过一个插件23333）

2014年（初三毕业后的暑假）我赚到了人生第一桶金，给仿制Discuz!的风格。

高中三年，前端发生了巨大的变化。各种框架、技术层出不穷...

但是高中紧的不得了，于是没法碰了。

高三的时候，在**弘树**的说教下，我把`《深入PHP 面向对象、模式与实践》`这本书带着看。

三年前，**5d6d**倒闭，被**haotui**收了。**Disucz**所在的**康盛** 也被**腾讯**收购了。

一年前**haotui**也倒闭了，那个[serves.haotui.com](http://serves.haotui.com)站也消失了。还好现在**Discuz!** 还在，貌似还是很吊的样子。但现在好像都没什么人想用这种笨重不堪的大型论坛程序了。

现在学`Vue.js`、`Webpack`（刚开始学这个）之类的时候的感觉，就像当初绞尽脑汁、看文档 的兴奋一样。但我已经长大了。

时间快的不得了。
- - -
不说了，乱七八糟说了一堆还好想哭，现在是 **2017.10.13 星期五 22:58**，该睡觉了。
因为我喜欢`前端`和`PHP`，所以才废话一堆。
事实上我说的时候都是
>大脑在颤抖！！！！！

### 做过游戏修改器
童年接触电脑非常早，玩过许许多多的游戏，便也接触到了作弊码、mod、修改器这样的东西。

百度一搜 马上搞到。

小学的时候，除了论坛

我还遇到了一个叫[我爱秘籍](http://bbs.52miji.com/forum.php)的网站，

和我学前后端的套路一样。

我学习了如何使用 `CheatEngine` 做修改器，百度搜`gylidian 修改器`，就能在**百度搜索结果第一页**中找到不少结果

以前我在**我爱秘籍**是个**实习斑竹**

其实我还玩过红警mod...

下载过很多变态补丁

于是尝试自己做mod

各种`ini` 搞得眼花缭乱...

浅尝辄止。。。。

### 高中参加两次过NOIP（省二 省三）
这玩意儿不多说了.....培训贯穿了高一到高二两年

每星期 去那么1~3次，每次2小时。

我又想起了被C++支配的恐惧.......

什么乱七八糟的狗屁 `背包算法` `哈夫曼树` `链表`

从高二暑假到现在，也忘了很多了。

我又想起了`当初去NOIP右边坐的那个市里面中学的人使用了26重循环做出答案`对我眼睛的杀伤力...

### 上了大学...
![](http://ww4.sinaimg.cn/large/0060lm7Tly1fkjscvpjmqj303d03dq30.jpg)

**喜欢**这个词，总是那么玄幻的。
就像`PHP`一样，现在`Python`那么火，我还是没提起对这个py开头的语言的太多的兴趣。
我现在也没知乎大佬装逼那水平，给你列举个一大堆`我为毛喜欢/使用PHP`的原因，术语一大堆，看着还很装逼hhh
喜欢就是喜欢...这个感情很难说清楚
喜欢一个东西 这模糊的感情催促着自己去追逐、争取、得到它。

高考数学炸了。。后悔的不得了。

通过**综合素质招生**，我来到这个学校。
怎么说呢，高三某天无意中翻册子就翻到了，6月10号那天滂沱大雨我也来面试了，就喜欢上**南信大**这玩意儿了。
暑假7月份跪在床上祈祷自己能够被录取，果真，录取了。

暑假我加了很多群，也遇到了许多学长。

我了解到了这里有个叫**多火**的社团，**前后端**大佬云集，我拼了命想加入。

很想加入。

我7月份认识了**周易**、认识了**方启腾**、认识了**常俊飞**、又认识了**马玉珍学姐**，8月份认识了**陈曦**，9月份又认识了**杨青霖**。
这份喜欢催促着我不断去了解他们。
包括部分信息 例如：**作息**、**班级**、**还加入了什么组织**...

暑假的话向周易dalao要了一些干货 (#^.^#)
好像是
1. How-To-Ask-Questions
2. Udacity
3. 百度前端学院

这些。然后还有学习的方向之类的=。=

和对待其他人的聊天记录一样，我存下了暑假聊下的所有聊天记录。

**周易** 给我的感觉和**徐老师**、**弘树** 是一样滴，我问啥弱智问题都详细解答。还自带萌萌哒表情包233333333333然后....他还有好多小迷妹....

托他的福，我直到现在的话
* **了解**了点`Hexo`（因为他博客是这玩意儿搭的）
* **学着用了**那个超简洁的Markdown编辑器`Typora`
* **知道**了`vue-cli`是啥子（脚手架）
* **翻了翻**那个新的[多火官网](https://www.duohuo.org) 
  * **搜了**`mainifest.js` `vendor.js` `app.js`是啥子
  * 搜了[大公司里怎样开发和部署前端代码？](https://zhihu.com/question/20790576/answer/32602154)
  * 学习了一些“奇技淫巧”


上个月军训期间 我还跟 **方启腾** 去明德楼4楼“搞破坏”来着233333，我发现了他有个业余消遣就是 `扒学校的所有IP和网站` 

（PS:不过我还是要吐槽一下学校的服务器地址之类的 真是烂到爆）

祝方大佬考研成功啊！ヾ(◍°∇°◍)ﾉﾞ加油

平时多火群里冷清得不得了（我知道大家都在好好学习）。然后突然热闹的时候也是乐的不行23333

对了...上次微信被 **常某** [○･｀Д´･ ○] 的一句`19。。。。。。。。。。。。。。。`搞卡机了....上了V站才知道啥毛病...(•́へ•́╬)

他也是校科协的...我面试校科协之前QQ上还找他来着...

**马玉珍学姐** 的话，军训期间我问她哪个组织好玩，她说社联好玩。于是咧...军训的时候我就去了看了看...嗯..就是去看看 没有认真准备， 大清早起来 第一个去面试。然后我那**怕生、腼腆**的毛病又犯了，脑子里一片空白...表现也超级烂吧...然后面试题有个是ps去水印那个唉= - =不说了QAQ 然后理所应当被刷了哇
然后一晚上没睡着觉 于是呢 反思了一下犯了许多罪过 ...我会改正的 (*^▽^*) ！！！

然后**陈曦**的话，暑假并没有聊多少，所以emmmmmmmmm。我认识了他的三个同学（一个叫**黄珂涵**学长、一个叫**曹梦琪**学长还有**于如**学姐），他们3儿除了互相谦虚外 都一致认定陈曦是大佬= 。 =

**杨青霖**学长为什么9月份我才认识呢...因为之前暑假没敢聊天...因为不知道聊什么啊啊喂...也不知道凶不凶 ，其实我好想聊的...因为头像是索尼克（Nintendo大法好！！！）

其实面试我是有点儿怂的...我好害怕过不了多火QAQ...


## 如何在一个 1h内 熟练使用 Markdown
**2017.10.14 星期六 0:08**
既然题目要求除了会用`Gayhub`、`Git`以外，还要用`Markdown`写自我介绍,我就好好写一下我的自学步骤吧。。
1. Vscode自带Markdown编辑器支持，我又下了几个插件
2. 到处查文档 查到了超棒的东东 塞到 Chrome书签里面
>* [Markdown 语法手册 （完整整理版）](http://blog.leanote.com/post/freewalk/Markdown-%E8%AF%AD%E6%B3%95%E6%89%8B%E5%86%8C#title-27)
>* [Markdown——入门指南](http://www.jianshu.com/p/1e402922ee32/)
>* [用 Markdown 写作用什么文本编辑器？](https://zhihu.com/question/19637157/answer/17395758)
3. 先建个md然后敲着玩 然后发现 **Vscode** 根本不支持`LaTeX公式`、`流程图`、`- [ ]`和`- [x]`，然后发现了一个好用的编辑器 `Cmd Markdown`（PS:`Typora`颜值超高，但是太简洁了，...还是用不习惯的...）
4. 开始狂敲，遇到不会的语法就查。其实**Vscode**上我装了一个`Markdown Lint`的拓展，可以提示语法错误
我还发现一个好用的插件叫`Markdown All in One`，好用的炸上天，有快捷键很爽。。。
5. “趴在木板上不断地摸索与练习”，基本的语法我已经熟练了，流程图、公式神马的。。。以后再说吧，，，

![](http://ww1.sinaimg.cn/large/0060lm7Tly1fkjscwzufnj30jp0f6mzb.jpg)

**题外话**

其实一开始我是抗拒`Markdown`的，去年我才知道有这个东西，不知道怎么火了起来，知乎上面一堆人鼓吹  怎么怎么牛了,作家必备之类 的话。给我感觉是恶心的...然后我也没尝试过...

`写个文章还用代码，这么装逼。` 、`GUI编辑才是王道，Md是邪教。` 这样的念头在我脑子里出现。

结果今天晚上用了之后发现好用的不得了。瞬间打脸= 。 =

配上Vscode爽炸天。

好处是：
- 不需要关注排版，可以专心写作
- 如果掌握了语法，加上骚操作：加粗 加斜 高亮 等等，异常的快速
- 生成大纲，点击可以直达标题所在处（#id）
- 可以写 流程图、公式。可以像编代码一样写，很快。
- 自带装逼特效 让写文章上升到装逼(▼へ▼メ)的高度23333333

坏处是：
- - 我经常忘记标题的`##`后面要空格，
  - 经常忘记`链接`和`插入图片`的语法中的括号顺序是`[]()`而不是`()[]`，
  - 经常忘记 要换行的话 在md代码里还要再换行一次
- 每次打开md文件 编辑器都要渲染一次，要是行数超大的话，会很卡的
- 不能在复制粘贴时 保存原有css样式
- 弄表格很慢、语法复杂的很
- 以后再说....

平时我笔记都是记在`为知笔记`里面的。

GUI编辑器有它的巨大好处。

我觉得最大的好处是：能 复制粘贴 Html 自带的样式而毫不改变。

写作的话以后我肯定会力推`Markdown`哒

废话不多说上图：![](http://ww4.sinaimg.cn/large/0060lm7Tly1fkjsd36ersj31hc0sm7av.jpg)
![](http://ww4.sinaimg.cn/large/0060lm7Tly1fkjsd0myg0j31hc0smaoh.jpg)