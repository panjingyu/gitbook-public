---
description: 以下文章的著作权等各种权利归原作者所有，翻译 By SeventhTG。
---

# 第三章 攻守判断的基准

## **攻守判断是最重要的**

那么终于到了重头戏内容了。麻将中最难，也是最能够影响成绩的就是攻守判断了。攻守判断到底是什么，其实就是这个：

> 有人立直的情况下，自己听牌了。应不应该立直呢？  
> 有人立直的情况下，自己的手牌是比较好的一向听。应该切危险牌立直吗？

应该如何进行如上判断是战术中最重要的部分。“尽可能的和牌，和不了牌的时候就减少放铳。”是麻将中的至尚命题。那么搞清楚“和不了牌的时候”具体是什么时候就是本章的重点。

有关这个判断，首先我会对于有点难度的地方进行提示，之后再为大家讲解一些实际的判断。

## 打点比对手低也有可能有利

首先我要消除大家一个误解。这个误解就是“自己的打点只有对手的一半，要对攻自己的听牌宽度一定要是对手的2倍”。

自己和另外一家都立直的情况下，假如“自己摸到自己的荣牌”、“自己摸到对手的荣牌”、“对手摸到自己的荣牌”、“对手摸到他自己的荣牌”的概率相等。那么和牌的概率就应该是放铳概率的2倍。（两人的听牌宽度一样的情况下）

再加上“其他家打出自己或者另外一家的荣牌”、“其他家和牌”与“流局”等情况，这个倾向就更加的明显了。即使打点只有对手的一半，和对手一样宽度的听牌追立也是很通常的打法。

{% hint style="info" %}
**听牌决胜负，不一定非要和对手一样的打点与听牌宽度**
{% endhint %}

## 打点比对手高也有可能不利

“哈哈，现在我是一向听，而且打点也比对手高，所以这里要进攻”。不不、等一下。并不是说你的手牌比对手强就一定应该进攻。

实际上攻守判断中，自己是否听牌了是非常重要的。一向听的话，好的手牌其有利性会被削减。两向听的话情况就更严重了。大家要记住，除非自己的手牌非常非常的好，否则两向听千万不要和别人对攻。

因此，不要单纯得仅仅以自己的手牌打点比对手高来进行攻守判断。

{% hint style="info" %}
**在自己听牌以前是非常不利的**
{% endhint %}

## 到底应该如何判断有利还是不利呢？

他人立直的时候是否应该追立的判断，是需要一些繁琐计算的。在这里我就不说明了，我会在后面公式化。

打个比方的话就是小偷是否行窃之前也要计算一下。如果“自己干的这一票加上被抓的风险（换算成金额）”大于“自己什么都不干的生活费”的话，那么结果是就应该行窃。为了完成这些计算，那么保险箱中有多少钱、警察的搜查能力有多大等等都必须要有一定了解才行。

不管怎么样，实战中要用公式来计算是不现实的。仅仅只能是估算。后面大家就一边看图表，一边把大致的标准计入脑海。这对实战才是比较现实的方法。

**（在麻将中写数学公式的人实在是太烦了。**

### 攻守的判别式

收入期望值G（进攻）=（1-p）{wW-h（H+r）-t（T+r）}-pH

收入期望值G（弃和）=-oT

因此，判别式D=G（进攻）-G（弃和）

=（1-p）{wW-h（H+r）-t（T+r）}-pH+oT

如果D&gt;0则应该进攻。

如果D&lt;0则应该弃和。  


**其中：**

**o：弃和时的被自摸率 p：现在要切的牌的放铳率**

**W：和牌时的收入（包括立直棒等） w：切安全牌进攻的和牌率**

**r：自己要立直的话就是1000、否则为0 h：切安全牌进攻的放铳率**

**H：放铳的平均失点 t：切安全牌追立时的被自摸率**

**T：被自摸时的平均失点**  


是攻是守的判断，需要如上的算式。首先分别求出进攻的收入期望值与弃和的收入期望值，然后求两者的差，根据其差的正负来进行判断。

这个式子非常繁琐。为了求简便，被自摸时候的失点（T），大家都是子家的话就只有H的1/4左右、自己是亲的话就是H的2/4左右，对手是亲家的话就是H的1/3左右，这么想会让式子稍微简单一点。另外，考虑到弃和时候的放铳、未听罚符、场上立直棒的回收等因素的影响，或者再加上祝仪的话。G的式子可以有更加个别或者具体的算法。

但是，就好像数学教科书一样，众多的变量非常讨厌。因此，把他家的立直平均得点代入式子中，可以获得更加简单也更加实用的版本，式子如下。  


大家都是子家的情况

D=\(1-p\)\(wW-hH-tT\)-pH+oT

=\(1-p\){wW-\(6000+r\)h-\(1500+r\)t}-6000p+1500o

自己是亲家的情况

D=\(1-p\)\(wW-hH-tT\)-pH+oT

=\(1-p\){wW-\(6000+r\)h-\(3000+r\)t}-6000p+3000o

对手是亲家的情况

D=\(1-p\)\(wW-hH-tT\)-pH+oT

=\(1-p\){wW-\(8500+r\)h-\(2830+r\)t}-8500p+2830o

注：以上各字母代表的变量与上面的式子相同  


嗯，少了两个变量，果然就和教科书一样。现在即使不知道详细的意义，根据前面给出的图表，这个公式也可以简单地运用一下。w、h、t、o是可以根据图表找到的数字。r根据自己是否拿出立直棒可以确定，W则是自己的和牌点数+立直棒收入。

还有就是p了，面对对手的立直，如果不太清楚某一张牌的放铳概率的话，就取5%（即0.05）或者10%（0.1）即可。利用计算机的话可以正确的估计，但是如果你自己觉得这张牌非常有可能放铳，那么就取50%（0.5）。当然你也可以把连庄的收益（650点）考虑进去，对结果的影响不大就是了。

良形追立与愚形追立，以一向听开始进攻来看，判别式所需要的量都是可以实际测量得到的。另外，根据实际模拟，我们成功求出了其近似值。（参照前著《科学する麻雀》）

只有变量p是不借助计算机比较难以计算到的。如果是切安全牌进攻的话自然就是0%。但是切危险牌的情况下，面对序盘的立直，无筋的1~3、7~9的数牌的危险度大概在3%~4%左右，两侧无筋的4~6的数牌的危险度大概在6%~8%。面对中巡的立直，1~3,7~9的数牌会是p的值上升到7%~10%左右。（如果现物越多，那么危险牌中某张牌的危险度就会增加）

对手的立直的点数是未知的，根据实际的测量，基本上子家的平均得点是6000点，亲家的平均得点是8500点。如果DORA大部分都可见，或者有从场况能够判断出对手的打点的情报的话，根据这些方法可以大概的估计出对手的打点也是一样的。

需要的变量我们都得到了，那么来计算一下判别式吧。将结果用三元的图表来表示，我们可以清楚的把握追立的优势。这里举一个例子，

![&#x56FE;1 &#x5B50;&#x5BB6;&#x5207;&#x4E00;&#x5F20;10%&#x5DE6;&#x53F3;&#x5371;&#x9669;&#x5EA6;&#x7684;&#x724C;&#x611A;&#x5F62;](../../.gitbook/assets/image%20%2811%29.png)

![&#x56FE;2 &#x4EB2;&#x5BB6;&#x5207;&#x4E00;&#x5F20;10&#x5DE6;&#x53F3;&#x5371;&#x9669;&#x5EA6;&#x7684;&#x724C;&#x826F;&#x5F62;&#x8FFD;&#x7ACB;](../../.gitbook/assets/image%20%2816%29.png)

自己的和牌点数（X轴）、巡目（y轴）、以及判别式的计算结果（z轴）都如图所示了。接近白色的部分即期望是正值，攻击更有利。接近黑色期望值是负值，就应该弃和。正与负之间的部分就是“是应该进攻还是防守的变化点”。

根据打牌的地点、规则的性质以及场况，对手的打点等等的不同，这个式子大家可以进行各种变形与扩展。如果你会点编程，能写个程序什么的，要运用这个式子就不会太难了。

## 弃和的情况下有多大概率被自摸？

弃和的时候被自摸的概率有多大？要回答这个问题，我先给出弃和时被自摸率的图表。

![&#x56FE;3 &#x5F03;&#x548C;&#x65F6;&#x7684;&#x88AB;&#x81EA;&#x6478;&#x7387;](../../.gitbook/assets/image%20%285%29.png)

这个图表表示的是在某一巡有人立直的情况下，自己完美地弃和防守，其他的玩家也进行与平均值相近的弃和防守时的被自摸的概率。根据目测，第1巡的立直有45%的概率被自摸，第10巡的立直有30%的概率会被自摸。

如果有人两立直的话，即使自己完美的弃和也有将近一半的概率会被自摸。但是要进攻的话，放铳又会支付大量的点棒，这个情况很令人蛋疼。

另外，如果巡目越晚，那么弃和被自摸的概率就会降低。也就是说这个时候弃和对于回避失点的作用更加有效。相对的，进攻的优势也会有所下降。攻守判断就会往“守”这边倾斜了。

如此，对手的立直是第几巡，根据这个然后查表就可以大概知道有多少的概率会被自摸。“不，麻将并不是这么单纯的游戏，舍牌、他家的习惯等都会导致被自摸率变化”，如果你这么想的话，那么你就把这个数字单纯的理解为被自摸的概率t代入判别式计算就可以了。很简单吧。

{% hint style="info" %}
**如果你被两立直的话，赶快去扶老奶奶过马路吧**
{% endhint %}

## 进攻与防守的标准的判断？

切安全牌追立的情况，和牌率与放铳率的基本图表有两面（良形）、嵌张（恶形）两种。

![&#x56FE;4 &#x4E24;&#x9762;&#xFF08;&#x826F;&#x5F62;&#xFF09;&#x8FFD;&#x7ACB;&#x7684;&#x671F;&#x5F85;&#x5EA6;](../../.gitbook/assets/image%20%286%29.png)

![&#x56FE;5 &#x5D4C;&#x5F20;&#xFF08;&#x611A;&#x5F62;&#xFF09;&#x8FFD;&#x7ACB;&#x7684;&#x671F;&#x5F85;&#x5EA6;](../../.gitbook/assets/image%20%282%29.png)

看两面追立的图4，在第9巡之前数据显示和牌率有50%左右的高概率。这个“基本图表”表示的是切安全牌追立所表示的数值。如果是切危险牌进攻的话，比如切一张10%左右放铳率的牌追立，那么实际的和牌率就只有从图表中读取的数值的90%。被自摸的概率也是同样的只有90%。放铳率也是90%，剩下的10%的概率就是你切这张牌的概率。

用非常单纯的想法考虑的话，比如在第二巡的两面追立的话，和牌率是53%、放铳率是16%，和牌率是放铳率的3倍，所以自己和牌时的收入（包括立直棒）有对手的1/3即可以进攻。

即使自己是 [![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s2.sinaimg.cn/middle/7f78b76fxc4007e3dc141&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s2.sinaimg.cn/orignal/7f78b76fxc4007e3dc141) NOMI的手牌（两面听牌），加上对手的立直棒，和牌的收入是2000点。如果估计的立直得点在6000点左右，那么进攻也是可以的。（这个结论经过正确的计算，可以说是正确的结论）

接下来，我们来看看切10%放铳率的牌追立的两种图表。两面追立、嵌张追

![&#x56FE;6 &#x5207;&#x653E;&#x94F3;&#x7387;10%&#x7684;&#x724C;&#x8FDB;&#x884C;&#x80DC;&#x8D1F;&#x65F6;&#xFF0C;&#x4E24;&#x9762;&#x8FFD;&#x7ACB;&#x7684;&#x671F;&#x5F85;&#x5EA6;](../../.gitbook/assets/image%20%2814%29.png)

![&#x56FE;7&#xFF1A;&#x5207;&#x653E;&#x94F3;&#x7387;10%&#x7684;&#x724C;&#x8FDB;&#x884C;&#x80DC;&#x8D1F;&#x65F6;&#xFF0C;&#x5D4C;&#x5F20;&#x8FFD;&#x7ACB;&#x7684;&#x671F;&#x5F85;&#x5EA6;](../../.gitbook/assets/image%20%2815%29.png)

用同样的方法来考虑，嵌张追立的情况下，在第12巡和牌率放铳率基本是一样的，因此能够进攻的判断标准就是要有与对手一样的打点。

当然，以上说的“判断标准”在数学上是不严密的。因为我们牵强地把进攻与弃和时的被自摸率忽略不计了，也没有考虑自己拿出的立直棒。因此这要作为一个目标还是根据实际情况来使用。比如嵌张听牌的NOMI手牌在第12巡面对子家的立直也不能切危险牌了。这个大家可以先记住。

{% hint style="info" %}
**大家首先从标准的判断下手吧**
{% endhint %}

### 来练习一下吧

那么，我们就来以这个判断方法来练习一下吧。能够学会这个的话，那么你的攻守判断就会非常正确了。

在第10巡，面对亲家的立直，如果要切掉安全牌两面追立需要多少打点？大家结合前面的图表想想。亲家的立直平均打点为8500点左右。

根据图4，在第10巡的和牌率为47%，放铳率为16%左右。和牌率是放铳率的3倍。因此攻守判断的标准即是否至少有对手1/3的打点，大家可以把它想象成是否进攻的分歧点。亲家立直的平均打点是8500点（这个只有背下来），1/3的打点即2800点左右。算上亲家拿出的立直棒，自己的手牌至少要有1800点以上。这与正确的计算结果相一致。（正确的计算结果为需要2859点，算上立直棒需要1859点）有点麻烦是吧，那么大家再来练习一次吧。

这次的场况是第12巡面对子家的立直，切危险度为10%的牌良形追立。大家看图6就可以了。和牌率为39%、放铳率为22%。子家立直的平均打点为6000点，6000点的22/39，即大约需要3385点。算上对手的立直棒，即2400点左右。正确的计算结果是2785点，还差得不多。不要说2400点，就是门断平的手牌（还可以期待一发和里宝牌）判断也是很绝对的。门断平的和牌点数在第12巡两人进攻的情况下有6000点的收入（大家可以参照第二章“中后盘先制立直有多有利”章节），结果是压倒性的进攻有利。

有些细小的比如100、200点左右的误差其实并没有什么特别重要的影响。

麻将中自己的点数是随着役增加而“翻倍计算”的，所以攻守的判断很多时候分的非常清楚，细小的差距是很少见的。这就是这个判断标准可以确实使用的理由。“这个点大概就是攻守判断的分歧点，高于这个点就该攻击、低于这个点就该弃和”，一眼能够下这种判断的能力是很重要的。

{% hint style="info" %}
**如果学会了标准的判断你就变强了不少**
{% endhint %}

## 良形听牌时面对对手的立直可以进攻的打点

这一节，我们不再以打点为目标，我们根据计算的结果来判断一下面对对手的立直能够进攻需要在什么样的巡目。

虽然各种条件可以进行组合计算，但是每多一个条件其组合就会成倍的增加。因此面对一般打点的立直，我给出了6个以良形、愚形；立直与否；牌的危险度；亲子关系为条件的图示。

![&#x56FE;8 &#x540C;&#x5B50;&#x5BB6;&#xFF0C;&#x81EA;&#x5DF1;&#x826F;&#x5F62;&#x8FFD;&#x7ACB;&#x6240;&#x9700;&#x6253;&#x70B9;&#x56FE;&#x8868;](../../.gitbook/assets/image%20%2825%29.png)

![&#x56FE;9 &#x540C;&#x5B50;&#x5BB6;&#xFF0C;&#x81EA;&#x5DF1;&#x611A;&#x5F62;&#x8FFD;&#x7ACB;&#x6240;&#x9700;&#x6253;&#x70B9;&#x56FE;&#x8868;](../../.gitbook/assets/image%20%2822%29.png)

![&#x56FE;10 &#x5BF9;&#x624B;&#x4EB2;&#x5BB6;&#xFF0C;&#x81EA;&#x5DF1;&#x826F;&#x5F62;&#x8FFD;&#x7ACB;&#x6240;&#x5FC5;&#x987B;&#x7684;&#x70B9;&#x6570;&#x56FE;&#x8868;](../../.gitbook/assets/image%20%2827%29.png)

![&#x56FE;11 &#x5BF9;&#x624B;&#x4EB2;&#x5BB6;&#xFF0C;&#x81EA;&#x5DF1;&#x611A;&#x5F62;&#x8FFD;&#x7ACB;&#x6240;&#x9700;&#x70B9;&#x6570;&#x56FE;&#x8868;](../../.gitbook/assets/image%20%287%29.png)

![&#x56FE;12 &#x81EA;&#x4EB2;&#xFF0C;&#x826F;&#x5F62;&#x8FFD;&#x7ACB;&#x6240;&#x9700;&#x6253;&#x70B9;&#x56FE;&#x8868;](../../.gitbook/assets/image%20%2826%29.png)

![&#x56FE;13 &#x81EA;&#x4EB2;&#xFF0C;&#x611A;&#x5F62;&#x8FFD;&#x7ACB;&#x6240;&#x9700;&#x6253;&#x70B9;&#x56FE;&#x8868;](../../.gitbook/assets/image%20%288%29.png)

在这里我就提出几个结论化的东西。

在序盘的第4巡，基本上不管什么样的条件下，有对手的立直棒的收入，两面听牌的话都是可以进攻的。

在第10巡左右，切10%左右的危险牌，拿立直NOMI的手牌与亲家的立直对攻是不利的。除此之外，两面听牌基本上是可以追立的。如果你是一个NOMI手牌，切危险的456进攻是很苦的。

第14巡的话情况就更糟了，如果是切安全牌追立基本没问题，如果是切10%的危险牌且自己是NOMI手牌，面对亲家的立直我建议还是不要对攻。

从这6个图示大家可以看的出来，立直宣言牌的危险程度左右着我们的攻守判断。

{% hint style="info" %}
**序盘的良形听牌，只要对手的牌不是非常大都可以进攻**

**第10巡的良形听牌，是否有对手1/3左右的打点是判断的分歧点**

**第13巡的良形听牌，是否有对手一半的打点是判断的分歧点**
{% endhint %}

## 愚形听牌时，面对对手的立直可以进攻的打点

愚形确实是要比通常情况下难受一点。特别是和牌率本来就不高，还要拿出1000点立直棒去追立的时候。很多时候你的损失可不仅仅只是那1000点立直棒。

同样的，愚形听牌的时候可不像良形听牌那样“一口气决胜负吧！”那样有利的。

{% hint style="info" %}
**愚形要对攻，即使是在第6巡，没有对手打点的2/3都是很不利的**

**在第12巡要愚形追立，自己是亲家是包括立直要2翻，自己是子家则包括立直要3翻**

**如果打点有满贯，即使是第15巡也还是能够进攻的**
{% endhint %}

## **从一向听开始进攻可以吗？**

在此之前的判断都是建立在自己已经听牌的情况下进行分析的。那么现在我们来考虑一下，如果有人立直的时候，自己还是一向听的话怎么办？在这样的情况下，收支会随着每一巡听牌概率的变化而变化。

**手牌A：**[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec2faa5984&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec2faa5984)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s6.sinaimg.cn/mw690/7f78b76fxd3ec2fc2c635&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s6.sinaimg.cn/orignal/7f78b76fxd3ec2fc2c635)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s3.sinaimg.cn/mw690/7f78b76fxd3ec2fadcee2&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s3.sinaimg.cn/orignal/7f78b76fxd3ec2fadcee2)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s3.sinaimg.cn/mw690/7f78b76fxd3ec2fadcee2&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s3.sinaimg.cn/orignal/7f78b76fxd3ec2fadcee2)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s3.sinaimg.cn/mw690/7f78b76fxd3ec2fadcee2&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s3.sinaimg.cn/orignal/7f78b76fxd3ec2fadcee2)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s1.sinaimg.cn/mw690/7f78b76fxd3ec331cc520&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s1.sinaimg.cn/orignal/7f78b76fxd3ec331cc520)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s1.sinaimg.cn/mw690/7f78b76fxd3ec331f25a0&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s1.sinaimg.cn/orignal/7f78b76fxd3ec331f25a0)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s4.sinaimg.cn/mw690/7f78b76fx7b979eb7eac3&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s4.sinaimg.cn/orignal/7f78b76fx7b979eb7eac3)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s9.sinaimg.cn/mw690/7f78b76fxd3ec3340d1a8&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s9.sinaimg.cn/orignal/7f78b76fxd3ec3340d1a8)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec333b8e14&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec333b8e14)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s16.sinaimg.cn/mw690/7f78b76fxd3ec3355c77f&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s16.sinaimg.cn/orignal/7f78b76fxd3ec3355c77f)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s1.sinaimg.cn/mw690/7f78b76fxd3ec3312eb50&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s1.sinaimg.cn/orignal/7f78b76fxd3ec3312eb50)

手牌A的听牌进张为[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s8.sinaimg.cn/mw690/7f78b76fxd3ec43f433d7&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s8.sinaimg.cn/orignal/7f78b76fxd3ec43f433d7)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec43fb53e4&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec43fb53e4)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s11.sinaimg.cn/mw690/7f78b76fxd3ec4401164a&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s11.sinaimg.cn/orignal/7f78b76fxd3ec4401164a)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s7.sinaimg.cn/mw690/7f78b76fxd3ec43dc6a76&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s7.sinaimg.cn/orignal/7f78b76fxd3ec43dc6a76)这4种牌，一巡能够听牌的概率大约是10%。这种情况的收支就如图14所示。与之前的图示都不同的是，和牌率比放铳率还要低。

![&#x56FE;14 &#x4E24;&#x4E2A;&#x4E24;&#x9762;&#x8FDB;&#x5F20;&#x7684;&#x4E00;&#x5411;&#x542C;&#x624B;&#x724C;&#x4E0E;&#x522B;&#x4EBA;&#x80DC;&#x8D1F;&#x7684;&#x671F;&#x5F85;&#x5EA6;](../../.gitbook/assets/image%20%2810%29.png)

![&#x56FE;15 &#x4E24;&#x4E2A;&#x4E24;&#x9762;&#x8FDB;&#x5F20;&#x7684;&#x4E00;&#x5411;&#x542C;&#x624B;&#x724C;&#xFF08;&#x8FDB;&#x5F20;&#x975E;&#x5E38;&#x591A;&#xFF09;&#xFF0C;&#x4E0E;&#x4EBA;&#x80DC;&#x8D1F;&#x7684;&#x671F;&#x5F85;&#x5EA6;](../../.gitbook/assets/image%20%2817%29.png)

如果现在是第12巡，自己的手牌只是一巡能够有10%听牌概率的一向听。有一个子家已经立直。我们来算算能这个时候切掉一张7%左右放铳率的危险牌维持一向听能够划得来所需要的打点吧。

即使这张牌通过了，从图示上面来看，自己的和牌率只有11%，放铳率是20，被自摸率是22%，弃和被自摸率是26%。根据判别式，所计算出的结果显示没有18000点的收入都是不可以进攻的。即使不考虑“7%的危险度”，也至少需要16000点左右的收入才行。

2个两面的门清一向听与子家的立直对攻是不划算的。这也就说明了先制立直的有利性。

**手牌B：**[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s9.sinaimg.cn/mw690/7f78b76fxd3ec3e4265d8&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s9.sinaimg.cn/orignal/7f78b76fxd3ec3e4265d8)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s13.sinaimg.cn/mw690/7f78b76fxd3ec3e53e70c&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s13.sinaimg.cn/orignal/7f78b76fxd3ec3e53e70c)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s4.sinaimg.cn/mw690/7f78b76fxd3ec3e6bedf3&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s4.sinaimg.cn/orignal/7f78b76fxd3ec3e6bedf3)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s16.sinaimg.cn/mw690/7f78b76fxd3ec3e67ab9f&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s16.sinaimg.cn/orignal/7f78b76fxd3ec3e67ab9f)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s13.sinaimg.cn/mw690/7f78b76fxd3ec3e78592c&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s13.sinaimg.cn/orignal/7f78b76fxd3ec3e78592c)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s16.sinaimg.cn/mw690/7f78b76fxd3ec3e40748f&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s16.sinaimg.cn/orignal/7f78b76fxd3ec3e40748f)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s16.sinaimg.cn/mw690/7f78b76fxd3ec3e40748f&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s16.sinaimg.cn/orignal/7f78b76fxd3ec3e40748f)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec3e47c6e4&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec3e47c6e4)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec3e7b7e84&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec3e7b7e84)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s8.sinaimg.cn/mw690/7f78b76fx7b979fdad4e7&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s8.sinaimg.cn/orignal/7f78b76fx7b979fdad4e7)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s13.sinaimg.cn/mw690/7f78b76fxd3ec3e32d8cc&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s13.sinaimg.cn/orignal/7f78b76fxd3ec3e32d8cc)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s13.sinaimg.cn/mw690/7f78b76fxd3ec3e32d8cc&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s13.sinaimg.cn/orignal/7f78b76fxd3ec3e32d8cc)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s13.sinaimg.cn/mw690/7f78b76fxd3ec3e32d8cc&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s13.sinaimg.cn/orignal/7f78b76fxd3ec3e32d8cc)

我们再来考虑一些条件更好的情况吧。手牌B的听牌进张为[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s3.sinaimg.cn/mw690/7f78b76fx7b97a0db23a2&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s3.sinaimg.cn/orignal/7f78b76fx7b97a0db23a2)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s2.sinaimg.cn/mw690/7f78b76fxd3ec4896d2d1&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s2.sinaimg.cn/orignal/7f78b76fxd3ec4896d2d1)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s7.sinaimg.cn/mw690/7f78b76fx7b97a0d8b7d6&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s7.sinaimg.cn/orignal/7f78b76fx7b97a0d8b7d6)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s4.sinaimg.cn/mw690/7f78b76fxd3ec488edd63&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s4.sinaimg.cn/orignal/7f78b76fxd3ec488edd63)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s16.sinaimg.cn/mw690/7f78b76fxd3ec3e40748f&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s16.sinaimg.cn/orignal/7f78b76fxd3ec3e40748f)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s14.sinaimg.cn/mw690/7f78b76fxd3ec489e627d&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s14.sinaimg.cn/orignal/7f78b76fxd3ec489e627d)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s2.sinaimg.cn/mw690/7f78b76fxd3ec486a5a21&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s2.sinaimg.cn/orignal/7f78b76fxd3ec486a5a21)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s13.sinaimg.cn/mw690/7f78b76fxd3ec3e32d8cc&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s13.sinaimg.cn/orignal/7f78b76fxd3ec3e32d8cc)这8种牌，一巡能够听牌的概率有大约是20%。顺便说一句，这里所说的20%的听牌概率，同样符合进张搭子能够吃的情况。

像这样的牌，切一张7%的危险牌维持一向听能够划得来的打点经过计算是7000点左右。

进张如此多的手牌，而且还是在第7巡这种离流局还有很远的巡目。没有7000打点的手牌都是弃和比较好。这确实有太不合理了。

这个例子就告诉了我们，日麻中一旦被人先制听牌，大多数情况都是弃和会更有利。而且自己的对手还有3个人，所以有将近一半的对局我们都在弃和。能够成功“兜牌”自然好，但是如果你切危险牌而把一向听变成两向听就是很悲剧的事情了。想要进攻就进攻到底；想要弃和的话也要弃和到底。

本书所采用的是没有加入赤5包牌的规则。如果加入了赤牌，则平均打点会有所上升。所以更加要求自己要有一定打点的手牌才可以和对手对攻。

嘛，这也是没有办法的。麻将就是这样的游戏，如果觉得老是弃和不爽的话，那么只能自己速速听牌了。

{% hint style="info" %}
**一向听的手牌，如果自己的手牌不是非常好，对攻是有损失的**

**两向听的手牌要对攻，除非是能够自由自在吃碰的清一色或者没有安牌、ALL LAST等特殊的情况**
{% endhint %}

## 副露手牌如何估计？

到此为止，有关估计对手的打点。我们已经说了，亲家立直一律当做8500点，子家立直一律当做6000点。

除了立直之外，还有副露或者默听的情况。尤其成问题的是副露的手牌。由于难以判断副露的手牌是否听牌，因此如何估计其打点是非常重要的。

在副露的情况下，我们需要考虑的因素有对手听牌的概率、放铳的点数以及现在要切的那张牌的危险度。

具体来说，比如他家听牌的概率是50%，如果真的听牌了，切某张牌放铳的概率是20%，打点为子家满贯8000点的话，那么就相当于8000\*0.5\*0.2=800点消费。

那怕有时候估计出来的数值很高，不过自己的手牌是一个满贯的一向听，像这种本来其期待值就比较高的情况，切一张危险牌也没什么问题。

那么同样的，对手如果是2600点的手牌则就是相当于260点的消费。260点的期待值能够改变攻守判断的情况几乎是没有的（比起这260点，是否立直的1000点点棒要更加重要一些），这260几乎可以无视掉。需要警戒的有亲家的双东碰、混一色、对对、DORA3等情况。

对于副露的判断影响较大的因素就是“高打点是否已经确定”以及“是否听牌”。

场上1张DORA都没有出现的情况下，对手的手中有多少DORA也还弄不清楚。如果情报不确定，那么就把看不到的DORA当做平均分配到对手以及山牌中了。像混一色、对对、DORA3等高打点确定的方向去考虑还是比较保险的。因为DORA2或者高打点的役是大家都想做的，所以麻将果然最强大就是先制攻击，像役牌速攻，对对等是非常常见的。如果太过在意他家的动向，自己的速度就会慢下来。

再来说说听牌概率吧，即使是混一色，2次、3次副露也都不一定就听牌了。在这里，我给出一些统计的数据。

![&#x8868;1 &#x5BF9;&#x624B;&#x526F;&#x9732;&#x65F6;&#x7684;&#x5DE1;&#x76EE;&#x4E0E;&#x526F;&#x9732;&#x542C;&#x724C;&#x7387;](../../.gitbook/assets/image%20%289%29.png)

表1是听牌概率与巡目以及副露次数的关系表。副露数越多，听牌概率也就越大；巡目越深，听牌概率也就越大，这是理所当然的。大家要记住表中重要的部分。比如第12巡染手的对手碰了发、碰了中的情况下，他的听牌概率大概有54左右，大概一半的概率呢。

序盘3副露、中盘2副露、终盘1副露都是大约50%的听牌概率，大家可以把这个记住。面对混一色，假设危险牌有10种左右，那么你要切的那张牌是在序盘3副露、中盘2副露、终盘1副露的情况下的话，即8000\*0.5\*0.1=400点。这就相当于400点的支出期望。（这只是假设对手只听10种牌中的一种，如果是2种的话就会是2倍了）

如果自己的手牌是2000点的打点，那么面对400点的支出期望还是可以对攻的。但是，这400点支出期望指的是当前状况下的支出期望，毕竟自己还并不能100%的和牌，因此要小心不要总是用同一个标准来进行判断。

另外，这个表还应该注意的地方就是最后鸣牌的瞬间听牌的概率。由于后面的自摸进张的可能性很大，所以这个数值大家高估一点才是比较保险的。

接下来再说一下默听，无视这个东西是最好的。首先默听是否听牌时不确定的；另外打点有没有立直那么高也不确定。默听，尤其是高打点的默听的概率，在任意的一个第12巡的情况下连10%都不到。假设某张牌的危险度为20%，经过计算其期待支出值也不过160点而已。这和形式听牌的优点相比要少太多了。要推测默听的听牌概率实在是太困难了，要使用有效的应对战术也很难，所以最好的应对方法就是无视。当然，如果是“不放铳就是TOP”或者“形式听牌很困难”等情况还是果断弃和比较好。

{% hint style="info" %}
**序盘3副露、中盘2副露、终盘1副露都有大概50%的听牌概率**

**默听基本无视**
{% endhint %}

## 应该扣住DORA字牌吗？

当有人很明显地在做混一色（或者清一色）的时候，我们应该扣住字牌吗？

从结论上来说，扣牌是错误的。

包括自己在内，如果谁把这张字牌打了出来，对自己手牌速度的影响只有那么一点点。然而，随着巡目的深入，这张字牌可能摸到一对，也很有可能成为炮牌。特别是在序盘，扣牌几乎是没有好处的。

要活用扣牌的技术其实只有“扣切”了，也就是自己基本已经放弃和牌的时候（而且他家同时也要扣牌）扣牌才可能有效果。

另外，他家距离听牌越近，对自己并不一定就是一件坏事。有人立直的时候，自己已经弃和。这个时候其他家在进攻与弃和的选择中，他家继续进攻对自己是有利的。

将这些情况包含进来，扣牌会导致自己与被扣牌的一家速度下降，对剩下的2家就会有利。这可不是一个好的战略。有不幸的事情，大家3人一起分担才是正确的。

![&#x8868;2 &#x5207;&#x201C;&#x6771;&#x201D;&#xFF0C;&#x5DE1;&#x76EE;&#xFF0C;&#x5BF9;&#x624B;&#x7684;&#x4E3E;&#x52A8;&#x4E0E;&#x81EA;&#x5DF1;&#x5931;&#x70B9;&#x7684;&#x6307;&#x6807;](../../.gitbook/assets/image%20%2823%29.png)

为了便于大家参考，我给出一个有关扣牌的统计数据。表2是以东场的子家在某一巡切掉一张生牌的东为条件，被亲家鸣牌的概率、亲家的和牌率的统计数据。其中的失点指标指的是与自己失点的关系程度。

从表中可以清楚地看到，失点指标随着巡目深入在不断的增加。所以要选择一个时机切字牌（这个数据是统计的东，其他字牌是一个道理）的话，第一打是最好的。这在统计学与理论上也是不用多说的。第一打打出DORA字牌，如果被碰了那是没有办法的。如果扣到第5巡再切，被鸣牌概率就会变为2倍。因此切的时机不同，其差别也是很大的。

如果一开始就弃和的话，那就是另一回事情了。尽早切掉自己用不上的牌是让对手也没法用上这张牌的一个诀窍。

{% hint style="info" %}
**不要扣住字牌**

**如果害怕对手碰某一张牌，那么就在第一打把它切掉吧**
{% endhint %}

## 难以和牌的安全策略还是容易和牌的危险策略？

**手牌C：**[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec83ac6154&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec83ac6154)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec83ac6154&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec83ac6154)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s1.sinaimg.cn/mw690/7f78b76fxd3ec83a44d80&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s1.sinaimg.cn/orignal/7f78b76fxd3ec83a44d80)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s1.sinaimg.cn/mw690/7f78b76fxd3ec83a44d80&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s1.sinaimg.cn/orignal/7f78b76fxd3ec83a44d80)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s11.sinaimg.cn/mw690/7f78b76fxd3ec8379900a&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s11.sinaimg.cn/orignal/7f78b76fxd3ec8379900a)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s11.sinaimg.cn/mw690/7f78b76fxd3ec8379900a&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s11.sinaimg.cn/orignal/7f78b76fxd3ec8379900a)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec838760e4&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec838760e4)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec838760e4&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec838760e4)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec839b2934&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec839b2934)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec839b2934&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec839b2934)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec83bdf1f4&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec83bdf1f4)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec83bdf1f4&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec83bdf1f4)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s14.sinaimg.cn/mw690/7f78b76fxd3ec83876eed&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s14.sinaimg.cn/orignal/7f78b76fxd3ec83876eed)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s9.sinaimg.cn/mw690/7f78b76fxd3ec837b3248&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s9.sinaimg.cn/orignal/7f78b76fxd3ec837b3248) **DORA：**[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec83bdf1f4&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec83bdf1f4)

**手牌D：**[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec8ef3c984&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec8ef3c984)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s8.sinaimg.cn/mw690/7f78b76fxd3ec8f0a8087&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s8.sinaimg.cn/orignal/7f78b76fxd3ec8f0a8087)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s8.sinaimg.cn/mw690/7f78b76fxd3ec8f0a8087&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s8.sinaimg.cn/orignal/7f78b76fxd3ec8f0a8087)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s2.sinaimg.cn/mw690/7f78b76fxd3ec94b41901&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s2.sinaimg.cn/orignal/7f78b76fxd3ec94b41901)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s2.sinaimg.cn/mw690/7f78b76fxd3ec94b41901&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s2.sinaimg.cn/orignal/7f78b76fxd3ec94b41901)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s2.sinaimg.cn/mw690/7f78b76fxd3ec8ebe8651&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s2.sinaimg.cn/orignal/7f78b76fxd3ec8ebe8651)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s14.sinaimg.cn/mw690/7f78b76fxd3ec8eccbfcd&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s14.sinaimg.cn/orignal/7f78b76fxd3ec8eccbfcd)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s7.sinaimg.cn/mw690/7f78b76fxd3ec8ee348f6&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s7.sinaimg.cn/orignal/7f78b76fxd3ec8ee348f6)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s7.sinaimg.cn/mw690/7f78b76fxd3ec8ee348f6&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s7.sinaimg.cn/orignal/7f78b76fxd3ec8ee348f6)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s9.sinaimg.cn/mw690/7f78b76fxd3ec8ee06008&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s9.sinaimg.cn/orignal/7f78b76fxd3ec8ee06008)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s4.sinaimg.cn/mw690/7f78b76fx7b97a7e46803&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s4.sinaimg.cn/orignal/7f78b76fx7b97a7e46803)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec8efde2c4&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec8efde2c4)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s11.sinaimg.cn/mw690/7f78b76fxd3ec8f0d389a&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s11.sinaimg.cn/orignal/7f78b76fxd3ec8f0d389a)[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s6.sinaimg.cn/mw690/7f78b76fxd3ec8eb1d8c5&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s6.sinaimg.cn/orignal/7f78b76fxd3ec8eb1d8c5) **DORA:**[![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s7.sinaimg.cn/mw690/7f78b76fxd3ec8ee348f6&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s7.sinaimg.cn/orignal/7f78b76fxd3ec8ee348f6)

序盘~中盘的时候，亲家立直了。自己的手牌如手牌C听牌了。 [![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s14.sinaimg.cn/mw690/7f78b76fxd3ec83876eed&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s14.sinaimg.cn/orignal/7f78b76fxd3ec83876eed) 是无筋的危险牌，而 [![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s9.sinaimg.cn/mw690/7f78b76fxd3ec837b3248&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s9.sinaimg.cn/orignal/7f78b76fxd3ec837b3248) 是安全牌。这个时候应该切掉什么牌呢？

答案是应该切掉 [![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s14.sinaimg.cn/mw690/7f78b76fxd3ec83876eed&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s14.sinaimg.cn/orignal/7f78b76fxd3ec83876eed) 。

那么再来看一个问题，同样是亲家立直的情况下，自己如手牌D听牌了。 [![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec8ef3c984&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec8ef3c984) 是安全牌，而 [![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s8.sinaimg.cn/mw690/7f78b76fxd3ec8f0a8087&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s8.sinaimg.cn/orignal/7f78b76fxd3ec8f0a8087) 是无筋的危险牌。这个时候应该切什么呢？

答案是应该切掉 [![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s8.sinaimg.cn/mw690/7f78b76fxd3ec8f0a8087&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s8.sinaimg.cn/orignal/7f78b76fxd3ec8f0a8087) 。两个问题的答案都是切掉危险牌，从而提高了自己的和牌概率。

如果切掉安全牌的话，只能保证这一巡是安全的，但是到终局还要花上数巡的时间。在这数巡中，有可能还会切掉几次危险牌。一开始不切危险牌，不仅降低了自己的和牌率，从结果上也增加了自己的放铳率。但是切一次危险牌能够形成更容易和牌的听牌形。从结果上来看攻击和防守都兼顾到了。

但是，如果是真心想弃和的话就是另外一回事了。先切 [![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s9.sinaimg.cn/mw690/7f78b76fxd3ec837b3248&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s9.sinaimg.cn/orignal/7f78b76fxd3ec837b3248) 或者 [![&#x3010;&#x304A;&#x3057;&#x3048;&#x3066;&#xFF01;&#x79D1;&#x5B66;&#x3059;&#x308B;&#x9EBB;&#x96C0;&#x3011;&#x8BD1;&#x6587;&#x2014;&#x7B2C;&#x4E09;&#x7AE0;&#xFF08;&#x653B;&#x5B88;&#x5224;&#x65AD;&#x7684;&#x57FA;&#x51C6;&#xFF09;](http://s5.sinaimg.cn/mw690/7f78b76fxd3ec8ef3c984&690)](http://photo.blog.sina.com.cn/showpic.html#blogid=7f78b76f010167wg&url=http://s5.sinaimg.cn/orignal/7f78b76fxd3ec8ef3c984) 默听，摸到危险牌的话就缩卵，这在战术上是可行的。如果手牌C和手牌D一张DORA都没有的话，那么这个选择又是正确的了。

{% hint style="info" %}
**切危险牌选择更加容易和牌的形才是攻守兼备的**
{% endhint %}

（待续）  


