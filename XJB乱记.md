<h1><center>迷迷糊糊的乱纪</center></h1>
## **27/8/21**
$\color{#FF0000}{dex这个单位= log\frac{M}{M_{\bigodot}}}$
M81这个星系相邻M82和NGC3077，从二者中潮汐拉扯出两条HⅠ流气体，乍一看以为是牵线搭桥的媒婆，实则是星宿老怪。RGB特点包括其贫金属，M/H>>-0.5,mag-g~28-29.对于M81而言，观测mag-g极限是27等，所以其实很大一部分还是看不见的。CSST也不得行.有意思的关于M81的研究在其minor 轴（垂直于长轴方向）效果要好，因为这个方向受到伴邻星系的潮汐作用要小很多。 <font color=#4682B8> M81的数密度分布：</font>
	$$log_{10}\sum(R)=log_{10}\sum(0)-\alpha*log_{10}\sum(\frac{R}{R_0})$$
$\sum(0)=-0.53,R_0=4.19kpc,\alpha=-2.59$
上面密度单位是每平方角
## 28/8/21
M81在 $<20kpc$  内的一个明显颜色梯度（该梯度接近M31 $< 25kpc$区域了）。81和MW二者都是体瘦贫血患者，但是MW里面就没有这么厉害的conversion
	通过数密度分布，还可以转换到面亮度分布，具体操作相关论文没看，Harmsen et al. (2017),的文章，$\rho\rightarrow\mu_{v-mag}$.
##  30/8/21
gala巡天有V-LOS（来在师兄师姐间的日常）。文献领读：
	MW内的白矮星数量w起步，background的白矮星信号太弱了。gw的目标。[link](https://arxiv.org/abs/2108.11971)标准AGN几何结构所认为的尘埃还可能不只是赤道范围。算法或者方法的简写很重要。blazars耀变体，episodic accretion间断性吸积
	
healpix的排序方式，nest模式与ring模式，nest是类似于蜂巢形式的几何结构那种可以无限细分的排序，nest是排序效率最高的，最简单是球面12等分，这12份按从北到南三个环排序（0-11），然后是$nside=2^2$,这时候有48个像素，是原来4倍。原来的每个格子分为了4小份。这时候，原来的0，其中包含了新序号0-3，原来的1包含了新序号4-7，依此类推...就可以得到所有的排序。而且确认新序号只需要乘以4就可以得到我老排序格子下面的4个儿子的序号分布，比如老序号76，再细分一级就是304(下)，305(右)，306(左)，307(上)，所以只要一级的地图排序有了，下一级的很快就可以有了也。排序效率极高。
所以呢，我给了一个分辨率情况下，比如$2^4=16$,这时候给我一个一个天球座标，我可以找到他的pix值是多少，那他附近的pix怎么找呢？
```
hp.ipix_disc = hp.query_disc(nside=512,vec=vec, radius=np.radians(8),nest=True,lonlat=True)
#表示512像素（分辨率下）,指定nest排序，返回的经度坐标而不是弧度
```
确认银经与银维度方向在函数变换后的值，vec尤其是。应该是变错了

## 1/9/21
转自：[希望论文一作发Nature后去当公务员的那名学生能看到我的这篇文章](https://mp.weixin.qq.com/s/4sRL9-ZqtkGTVyAl9o6ZIw)第一作者（一作）一般是论文的主要实现者和写作者，虽然有可能主要想法是通讯作者的，但是说的容易做的难，一个好想法到实现，是要克服很多难关的。我们老师有时有很多好想法，叫来学生讨论，能理解的不到一半，理解了到做出来又不到一半，做的出来能写得好，又不到一半，能完善老师想法的又不到一半。尤其是能和老师讨论出能上Nature论文的好想法并实现的研究生，确实是凤毛麟角。如此看来，郝治伟的科研天赋至少已经达到了研究生的前1%，实在出类拔萃，没有能继续从事科研工作实在令人扼腕叹息.

我到了哪一半呢？哎，有点点伤感，努力吧，从普通进阶先！加油
如何说明MW中的黑洞是rest(静止)呢？文章提了一句说利用$Sgr A^*$的PM（垂直盘的自行）发现与太阳的一样，就说明了。
## **2/9/21**
Bulge 的研究还是有点少的，尤其是inner part，尘埃遮挡太严重，需要更加厉害的消光计数
RNN
## 3/9/21
ASTRO咖啡领读：Transient Point Source（啥天体了）；天格（GRID）X-ray探测器
## 17/9/21
Hubble常数疑难至今仍在努力，距离阶梯法告诉我们是73.4， CMB方法是	67.4.而观测发现超新星的绝对星等有个突变，这个突变可能是

查准率和查全率这两个概念，一方高时另一方往往就比较低。表达式分别是$$P=\frac{TP真好}{TP真好+FP假好}；$$$$R=\frac{TP真好}{TP真好+FN假坏}$$，一般我们的需求是尽可能将好瓜给选出来（引用自西瓜书），那么为了衡量二者就引入了平衡点这一概念(Break-Even Poine)P=R的位置也就是，但一般不用这个度量，用如下方式：
$$\frac{1}{F_1}=\frac 1 2 \left(\frac 1 P +\frac 1 R \right)$$
如果想偏向其中一个的化，则需要加权。
新词汇：AUC，area under ROCcurve，曲线覆盖面积来作为一个模型好坏标准。
COCO需要自己下载训练数据才能跑，我大意了只要是算法，肯定需要训练集。不能靠人家自己带链接下载
## 21/9/21
md，不知道谁把我服务器的包给删了，让我莫名其妙，导入包都不得行，有点无语
 <font color=#4682B8> 查看pixel值的区域位置，healpy的坐标帮助->检验是否有前景星分布假设球状分布下，色指数分布。然后是HST的数据我能干啥？  +   机器视觉学习-挑选RGB通过编号选取</font>

- 能否去找找认证褐矮星，看看光谱找找大气结构，探索行星和恒星之间的缝隙秘密<br/>- 估算红移信息分布？用多色测光的信息机器学习去判断红移大小，这个感觉有点不太靠谱哎？天体的光谱啥样的都有，如果把训练样本的特征作为红移判据，误判其中天体的概率（其中被误伤的天天类别）有多大呢？样本的构建感觉也蛮难的。

## 24/9/21
兴隆培训 1st day
$\frac{d\theta}{d\lambda}$
$m \lambda =d (sin\alpha +-sin\beta),m=0,1,2,3\ldot$
$d = a+b,\alpha 入射角 \beta 衍射角？？？？$
平场量子效率各处不一致结果，热点或者死点（太灵敏或者不灵敏的地方，后期处理），宇宙线
$真实强度 = \frac{天体CCD像强度-天光-}{}$
信噪比SN：
$$\frac{S}{N}=$$
简化1：亮源时候，噪声由目标源主导，此时正比于$\sqrt t$
简化2：暗源时，噪声由天光背景，星象元数（视宁度seeing反比）

色散方向与空间方向？

宇宙线去除:3副图像叠加去除或者多福，因为同一个宇宙线同一位置概率很低。或者编辑像元
追迹与抽取：沿着x色散方向去找y（空间）的峰值在哪，峰值坐标y不一样原因是大气色散，不同波长的光被色散后的位置不一样，电源会被拉长。可以避免？放外太空？

灯谱？
流量定标
大气吸收线扣除（We don't care）
星际消光,本征消光改正

## <font color=#4682B8>观测申请该如何写(兴隆为例，申请到数据)</font>
非得这台设备的原因，或者历史延续性（以往研究用的就是这个，不建议换）
一定要科学针对，镜子能不能做测光，极限星等范围，信噪比之类的。高分辨率光谱仪
申请时间佛系选择无法预测天气
观测对象找个黑洞双星？
设备分配要求：快要毕业了，希望12月或者过年观测，

交了pdf也要在网页额外填表。2.16m每年一次，网页提交。85cm或更小的一般两年一次。邮件申请可以

## 25/9/21
: ls bias_*.fit > lst_bias
: ls flat_*.fit > lst_flat  分波段列表文件
: ls V398*.fit  > lst_398_V
以上是将需要的文件放在一起方便处理
进入iraf ：

: ds9 bias*.fit   用ds9来检查文件
查看scale？
	
CCD图像的本底合并：

平场的本底扣减
	epar ccdproc：
	
默认假定：一个小视场内的FWHM值是差不多的（同一天拍的），因为受到的干扰可以认为是一样的

V v对应波段不同，一个表示visible，一个是紫外，大小写不是同一个波段（受制于window系统的区分）

5倍的半高全宽
宽度为2*
bf不加的话测得是原来的图，**必须加**
less命令可以滚动查看参数
```
1、错误代码：
ERROR: No 'instrument' translation file specified
2、解决办法：
进入noao.imred.ccdred，进入设置，setinst，设置instrument项为coude即可。(有时coude不行，设成camera也可）
```
display的使用必须要是tv，可以退出iraf之后 export IMTDEV=inet:5137 ，再次进入iraf之后即可display
测光程序开始：
<font color=#4682B8 > epar centerpars </font>
cbox: 3* 2.3
<font color=#4682B8 > epar fitskypars </font>
annulus = 5*2.3
dannulu = 2*2.3
<font color=#4682B8 > epar datapars </font>
fwhmpsf = 2.3
readnoi = 6.5
gain = 1.1
<font color=#4682B8 > epar datapars </font>
apertur = 5.29,6.25=2.3\*2.3
zmag = 25
总的提取时间星等信息，需要先后进入几个包ptools，astutil，再操作

B波段FWHM：2.37取值
baoextinct.dat文件写绝对路径 /home/yyb/iraf/iraf/baoextince.dat
feige15小写是对的，caldir关键参数字母细心点
epar standard 下修改

<font color=#4682B8 >纵坐标单位，$10^{-13}$是啥？</font>
 <font color=#4682B8 >airmass的计算？</font>
**指天顶距等于z的方向上大气光学厚度和天顶方向大气光学厚度之比**一般用X表示，$$X=\frac{BC}{AC}$$。
![[Pasted image 20210926211325.png]]

兴隆的Dec：40°23'36'',也就是：

## 27/9/21
getdata
open优先使用
fits写入命令：
自动auto_download= False可以节约时间
NAN值可以用inter~插值解决，防止画图报错
wcs包的使用，xy与天球坐标的转换

目标：距离 parallax：1.4838mas
phot_g_mean_mag = 20.4703 mag 
phot_g_mean_mag_error = 0.009613 mag 
pm = 21.472 mas/yr
	
## 27/9/21
 Lithium in the lower red giant branch of 5 Galactic globular clusters
 Spite plateau：平台，Li丰度，li 质量和红团cu 星质量的关系，大质量星Li容易超丰，低质量不容易，
extended main-sequence turnoff (eMSTO).

分形维度反映形状复杂度，研究卷云的性质 
First Evidence of Intrinsic Alignments
 宇宙学 的东西，星系间的相关函数之类的？
## 10/10/21
jd 建议：数据预处理的图像浮点数64或32内存占用略大，而cv中处理一般是10位或者更少，节省显存，如何改进当下的处理流程？

## 23-10-23
Dr. Frank,
15 years ago, RV of SN Ⅰa--> universe is expanding

CMB: some typical chaos --> 扰动 --> BAO