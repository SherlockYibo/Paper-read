

## **27/11/21 开题报告**
 $\color{blue}{Part Ⅰ }$： 我要研究的Halo profile 指的是stellar halo， 其中银河系的stellar halo 以及 Nearby galaxy stellar halo的研究现状调研，包含 age 、metallicity 分布，大小 和 interaction etc。目的是为了研究 M81和M82的 halo 是否有相互作用，如果没有作用，那么就是各自的数密度叠加形状，like 这样：
	{无作用叠加图}
	如果有相互作用，那么就不是一个简单的叠加，其各自的数密度分布会有一个明显的凸分布。
 $\color{blue}{Part Ⅱ}$：Halo之外是 out-disk ，其长期演化(secular evolution) 的特征，再次对比MW 和 Nearby gal ，其 age, metallicity, size, distuibution. 
 $\color{blue}{Part Ⅲ :}$好，上面两个科学问题都是建立在我有相对较准的测光能力之上，以及deblending 能力，后者可以帮我在 star counting 提供帮助，尤其是crowding field， 至于测光能力，与之相应的测量量还有 radius, temprature, gravity, luminosity, 有了这些就可以去找 metallicity \& age relation.



无法给出完美的回答科学问题-->好问题的提出，兼具外延（一系列现象的解释）和内涵（详细机制）-->  恰当的科学问题
- 文献阅读，结论一句话，方法一句话，数据一句话，疑问一句话，用英语记录。不超过200字，最好100以内。不要抄原话。
- 主要内容集中在研究内容

## **25/11/21 文献的中文笔记**
- 25/11
	TP-AGB比TRGB要亮，但是其演化机制在年龄金属分度的分布边缘部分有很大不确定性，一方面是因为之前的研究是基于大小麦的搜寻和前景星进行的，所有样本很少，后来开始将星团中的恒星也加入到age-metallicity中来找，但是发现这样做得到的模型和观测不匹配，为了解决这个计数少问题，提出用扩大到星系的AGB星计数，而dSph矮椭球星系正适合这样的任务，
	
	$[\alpha|Fe]、[Fe|H]$ 含义代表了
	## **02/12/21 开题背景准备**
	
	
	其中数密度直接反映了MW或者星系的总的吸积历史，当前用RR Lyrae， blue horizontal branch(BHB)，red giant branch(RGB)，以及near-main sequence turnoff star(nMSTO)这些好的标准烛光来作为工具去统计这些特殊晕星的数密度分布。BHB和RR Lyrae 相比于另外俩更老更贫金属，但是他俩分布很广，可以外延到离中心100kpc，RGB大约可以外延到50kpc，nMSTO在内晕里大多，约20kpc，这些距离都是相对MW而言。
	
	这些星的空间分布上，目前一般是当球对称、轴对称的幂律分布或者用 Sersic 径向分布，发现有的星系SPL就很好，有的比如MW就需要DPL更好的吻合观测，而其中涉及到的半径拐点是个有意思的地方，这里不仅数密度会变化，相应的金属丰度也会变，Deason (2013)通过模拟发现数密度会在远心点形成堆积，暗示着存在比宿主星系相比拟的作用。那假如知道了这些数密度理论上是可以去估算星晕质量（可以用isochronous来做，给定温度和亮度后，那么按照恒星模型其半径大概就确定了，然后可以测出$log~ g$这样测出一个等效的质量吧算是）。无论是BHB或者RGB有了丰度和光度还有颜色，就可以找到其对应的质量，然后对数密度累计求和，$\color{blue}至于如何用一个星族来推算整个星族的质量呢？$	还有的用子结构质量占比来推算的，至于如何实现找Belokurov et.al 2013。
	
	质量之后是动力学内容，速度弥散和其非对称性，其速度椭球主轴和椭球坐标的轴平行，能测到速度分量这些还是MW的研究多一点，河外的恒星自行很难，暂时跳过。
	
	然后是Hot halo，成分主要是热等离子体，最早由Spitzer 最早观测到HⅠ 由外部介质来限制边界，Anderson(2011)提出了强有力的证据热气体来自附近的大质量盘星系。热气体在AGN星系更容易探测，软 X-ray背景普遍存在。一般认为MW的热气体晕由两部分组成，1是随标高指数衰减的高金属成分，2是延展到数百kpc外的低金属成分，至于温度分布就有些不是很好估计了。虽然很多模型在模拟，存在的问题比如倾向于流体静力学平衡的热气体模型与晕的常数熵相矛盾。不过现在从X-ray的观测基本确定了halo温度基本是均匀的，虽然这并没有要求halo必须是严格等温的。至于计算热气体的质量，方法是Miller\& 和Bregman做的，估计出来时$10^{10}M_{sun}$,将重子质量加完之后与总质量比较（维里半径之内），比例为6%,与前任Hinshaw(2003)的16%相差甚远。
	
	调研Ⅱ关于outdisk的：
	

## 开题准备
基于CSST的
团组，博士开题标注
包裹星系的恒星组成的晕状的结构

title：基于CSST的星系晕中恒星组分分析

当下普遍接受的宇宙学模型是$\Lambda-CDM~$暗物质模型，这样的情境下早先重子物质被冷暗物质晕所包裹。整个Halo还包括Stellar、gaseous 成分，dark matter 我先不考虑。我们可以认为恒星和暗物质所遵循的3维空间结构相同，但二者的形成过程却不是那种linked关系，gaseous是星系重子质量重要组成部分，和其他星系相互作用或者是星系内的小范围子结构都会反映在气体上。这样演化图景下的小的子晕之间或大小晕之间引力潮汐或者并合，吸积大约100个卫星星系才能形成星晕，在这些模拟里面大多数晕星是来自被瓦解的大质量星系，越靠外越年轻，随机无规的自相残杀便留下了各种各样的星流(concept of stellar stream, [(Duc et al. 2015)](https://ui.adsabs.harvard.edu/abs/2015MNRAS.446..120D/abstract)). 	
	
	貌似这个宇宙学模型很不错，而且越来越多的观测都和它对的上，然而科学总是会有一些奇怪的异常出现。像MW这么大伴有卫星星系很正常，但是预言的卫星星系数量我们实际观测到并没有那么多，也就是著名的'Missing satellites' problem ,这个问题还可以用我们观测能力有限暂时遮盖住，随之而来的 ”Too big to fail“则是将这一问题锐化，按模型预言低旋转速度星系的质量比测量到的 H Ⅰ 速度对应质量要大很多，所以按道理低速HⅠ对应的大质量星系应该很多才对，但是我们并没有观测到那么多也。
	
所以我的目标便是希望通过几十上百个星系得到一个统计性的结论说明星系的缺失质量故事
	
	首先是通过$\Lambda-CDM~$模型模拟星系形成和演化可以预言出了许许多多的可观测特征，这些特征比如矮星系的吸积形成的stellar strean 直接可以为星系逐层演化提供证据；潮汐尾（tidal tails）和包层（shells）也是星系相互作用的遗迹证明，包括MW，大小麦Andromeda（M31）以及本星系群中有很多都有这样的结构。
	
![](https://www.preposterousuniverse.com/blog/wp-content/uploads/2014/07/toobigtofail.jpeg)
<font size=2> Figure1: The horizontal axis is the maximum circular velocity, basically telling us the mass of the halo; the vertical axis is the observed velocity of hydrogen in the galaxy. The blue line is the prediction from ΛCDM, while the dots are observed galaxies. Now, you might think that the blue line is just a very crappy fit to the data overall. But that’s okay; the points represent upper limits in the horizontal direction, so points that lie below/to the right of the curve are fine. It’s a statistical prediction: ΛCDM is predicting how many galaxies we have at each mass, even if we don’t think we can confidently measure the mass of each individual galaxy. What we see, however, is that there are a bunch of points in the bottom left corner that are above the line. ΛCDM predicts that even the smallest galaxies in this sample should still be relatively massive (have a lot of dark matter), but that’s not what we see. </font size=2>
	
而往往这些矮星系吸积结构都会特别的暗不容易观测，第一个人们在这种小结构中发现矮星系还是在MW中的 Sagittarius stream 中发现了矮星系([Ibata 1994](https://ui.adsabs.harvard.edu/abs/1994Natur.370..194I/abstract)	[Majewski, S.R. 2003](https://iopscience.iop.org/article/10.1086/379504) )	，这些星流子结构同样值得注意，[Newber et al. 2002](https://ui.adsabs.harvard.edu/abs/2002ApJ...569..245N/abstract)从其子结构中找到了新矮星系。随后SDSS数据（DR5）发布后发现了更多的的星流	[Beloburov,V  2006](https://ui.adsabs.harvard.edu/abs/2006ApJ...642L.137B/abstract)，故事还没有结束，[Grillmair, C. J. 2006](https://ui.adsabs.harvard.edu/abs/2006ApJ...651L..29G/abstract)也从同一数据中找到了被瓦解的矮星系流遗迹(冷的星流)。到如今已经发现的星流数大约60-70（作者出处）。
	
![](http://english.nao.cas.cn/ne2015/rn2015/202101/W020210127586552690776.png)
Figure2: The orbit of the Sagittarius stream. (Credit: David R. Law）
	
于是从星流中寻找矮星系作为 ‘Missing satellites'的解决路径之一受到关注，近年来新一代数字巡天比如SDSS Ⅱ，Pan-STARRS, Dark Energy Survey 在MW找到了各种各样的星流去寻找矮星系(e.g., 	[Beloburov,V  2006](https://ui.adsabs.harvard.edu/abs/2006ApJ...642L.137B/abstract)),。SDSS之前找到的矮星系只有数十个，之后矮星系MW卫星矮星系数量遗迹达到50+。理论上[koposov ,20009](https://ui.adsabs.harvard.edu/abs/2009ApJ...696.2179K/abstract)在CDM框架内起的自然物理机制可以定量地解释目前已知的MW卫星星系的性质，提供了一个可信的解决方案。
	
那么留下的问题是我们是否还能找到MW的卫星星系，星流的形成机制是什么呢？小(同量级)质量星系并合留下的遗迹，星系内气体自己成团塌缩本地形成，还是恒星被散射作用，亦或者落入球状星团瓦解?已知的Dwarf galaxy 都几乎在一个平面上，他们的空间分布为什么会这样？
	
好，让我们把视野放远一点到河外，近距离里面最大的M31,PAndAs 巡天([Ibata et al. 2014](https://iopscience.iop.org/article/10.1088/0004-637X/780/2/128); [McConnachie et al. 2009](https://ui.adsabs.harvard.edu/abs/2009Natur.461...66M/abstract))从全景的2d Stellar halo中发现新的星流和矮星系可以远到150kpc外，金属丰度也确定了，其半径标长（~55kpc）比理论预期的大四倍。伴随大量的新的卫星星系，同时还发现其3/4都大于-6等的卫星星系正在瓦解(M33最明显)。遗憾的是图像缺了一大块。
![figure1](https://media.springernature.com/lw685/springer-static/image/art%3A10.1038%2Fnature08327/MediaObjects/41586_2009_BFnature08327_Fig1_HTML.jpg)
	
![figure2](https://media.springernature.com/lw685/springer-static/image/art%3A10.1038%2Fnature08327/MediaObjects/41586_2009_BFnature08327_Fig2_HTML.jpg)
	Figure 2:Top:Stellar density map of Andromeda-riangulum. Middle and bottom:Distribution of M31 dwarf galaxies.(Credit: McConnachie et al）
	
那么他们依然是没有去关注Halo的轮廓，M31的halo 轮廓与其他宿主星系的Halo 轮廓是否有一致性呢？是否还有更暗的矮星系没有发现呢？
	
继续眼光放远到几个Mpc尺度上，到了Sculptor，M81等这些大家伙附近，HST的GHOST([Radburn-Smith et al, 2011](http://dx.doi.org/10.1088/0067-0049/195/2/18) )和ANGST([Julianne J. D et al. 2009](https://iopscience.iop.org/article/10.1088/0067-0049/183/1/67))项目，	分别做了14个$< 14Mpc~$和69个$<4Mpc~$近邻星系细节成像。
	[Daniel R. W et al.](https://arxiv.org/abs/1101.1093v1)系统性的研究了这些样本的恒星形成历史(SFH),发现星系的大部分（$>50%$）恒星形成于红移$z~\sim1$时期，近期1Gyr内的剧烈活动表面可能的卫星星系瓦解.[Benjamin et al. 2018](http://arxiv.org/abs/1004.5135v1)[Stephanie et al. 2018](http://arxiv.org/abs/1002.1743v1)[](http://arxiv.org/abs/0810.2557v1)研究了NGC404，M81以及NGC300的恒星活动历史,明显的金属丰度梯度暗示了其星族合成经历过干扰。
	
	![](https://cfn-live-content-bucket-iop-org.s3.amazonaws.com/journals/0067-0049/183/1/67/1/apjs300730f5_lr.gif?AWSAccessKeyId=AKIAYDKQL6LTV7YY2HIK&Expires=1640230691&Signature=%2FilYAkoh%2F0VV2aKjEkWxT8yXV0c%3D)
Figure 4:Field positions of images included in 16 galaxies.(credit by Dalcanton et al.)
	
受制于HST的视野限制，想要得到近邻星系的全貌需要大量的时间代价。之后大口径光学望远镜出世，让我们得以对这些近邻星系的全貌得以一窥全貌。[Sakurako et al. 2015](https://iopscience.iop.org/article/10.1088/2041-8205/809/1/L1) 最先对M81进行一个全局研究，HⅠ 以及RGB、AGB作为Halo示踪物，展示出其与M82、NGC3077的相互作用，后来([Adam et al. 2020](https://iopscience.iop.org/article/10.3847/1538-4357/abc485))结合HST的深场优势和HSC的宽场优势，在Sakurako基础上又得到了halo 的质量轮廓，金属丰度分布。
	
![](https://cfn-live-content-bucket-iop-org.s3.amazonaws.com/journals/0004-637X/905/1/60/1/apjabc485f14_lr.jpg?AWSAccessKeyId=AKIAYDKQL6LTV7YY2HIK&Expires=1640237554&Signature=T2pLB0x0G7lKynYPgw5MM3crdjs%3D)Figure 4. Density image of RGB stars(credit by Adam.)
	
	我们依然是同样的问题M82的Halo以及其卫星星系halo的轮廓，不只是数密度轮廓，其金属丰度轮廓和年龄都需要。这些HSC的深度不够所以完备性低，而HSC的则视野太小。另一个是M82中出现的极低金属丰度是否来自额外的卫星星系作用？
	
	更远的星系比如只能是面源里面恒星无法分离出来的星系，比如远到80Mpc处，这些星系我们很难去识别其中的恒星，但是他们表现出来的五花八门的形态对应的星流让我们很感兴趣，这些有的像是MW的射手座星流，有的像漂浮在星系内的碎片云，还有类似于盘方向喷流的结构，这些子结构无不说明着其过去瓦解矮卫星星系的历史，更惊人的是这些观测形态都能和数值模拟中找见(e.g., [Johnston et al. 2008](https://ned.ipac.caltech.edu/level5/March16/Carlin/Carlin_refs.html#johnston08), [Cooper et al. 2010](https://ned.ipac.caltech.edu/level5/March16/Carlin/Carlin_refs.html#cooper2010)).，除了已经被完全瓦解掉的星系我们只能看到遗迹，那些正在瓦解或者瓦解中存活下来的星系便是我们最理想的研究星系演化和恒星形成历史的最佳实验对象。形态标本的多样性为支持宇宙学模型预测的分层星系形成场景提供了强有力的证据(e.g., [Cooper et al. 2010](https://ned.ipac.caltech.edu/level5/March16/Carlin/Carlin_refs.html#cooper2010)).。
    ![](https://ned.ipac.caltech.edu/level5/March16/Carlin/Figures/figure2.jpg)
	Figure 5:Luminance filter images of nearby galaxies from the pilot survey of Martínez-Delgado et al.([2008](https://ned.ipac.caltech.edu/level5/March16/Carlin/Carlin_refs.html#MD2008), [2010](https://ned.ipac.caltech.edu/level5/March16/Carlin/Carlin_refs.html#MD2010)) showing large, diffuse light structures in their outskirts.
	
	![](https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/mnras/406/2/10.1111_j.1365-2966.2010.16740.x/1/m_mnras0406-0744-f7.jpeg?Expires=1642606252&Signature=aEWPSs7MiolS1kMxgKOK8mgxhS6Zq6Z7ovY6UHJElROR6EnUFtlD9BFLnGa8U58311St1NrMFkODwjzrjc1GhoYMGgjcFkLE1oFJ-LtPbVyxIiUOJopjQ7qQ7L5lu9lvZz8TFwl1k~w2oB50sCMC0QMvSDQeKDO9LLwowehJ-UMp3e9XyLmeuQZGZSrs5BOvMqsmp3JabWhyk3mL6oBv0eqKWorIdywbBeU~YOQAioljN5SDh9V0KFWshIyAfnyeacr7deWXNYZcnyFnimTwbk4Q6YYrZluQEIMIxlLGHS9PEDoVCUpw5~Qgcw98zicl4b-a0FTBaWw~Yhw48a1HUA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA)
	Figure 6:showing only those stars stripped from satellites that survive at $z= 0$.(credit by Cooper)
	
GHOST因为时间成本问题就没有完成所有目标，这些近邻的unresolved 星系，比如MW analog 一类的（N891,M101），还有一些极低面亮度的halo这些目前没有分离恒星的星系。[D. Crnojević et al. 2016](https://iopscience.iop.org/article/10.3847/0004-637X/823/1/19)研究了Cen A($D \sim 3.8Mpc$)，外延到离中心150kpc外，发现了许多未知的星流和卫星星系。其实往前追述SDSS巡天之后，[M. Pohlen and I. Trujillo 2006](https://www.aanda.org/articles/aa/abs/2006/30/aa4883-06/aa4883-06.html)便研究了低到$27 mag/sqre''$的矮星系盘的面亮度径向分布。到现在新的手段可以帮助我们对这些unresolved 星系了解，[Martínez-Delgado et al 2021](https://arxiv.org/abs/2104.06071)要开展的星流巡天项目，[Trujillo et al. 2021](https://www.aanda.org/articles/aa/abs/2021/10/aa41603-21/aa41603-21.html)利用LIGHTS( LBT Imaging of Galaxy Haloes and Tidal Structures)项目对极限可以到$\mu_{V}\sim 31~mag~arcsec^{−2}$的源，展示了对NGC1042 周围非对称的halo分布，未来在本星系群之外会看到更多这样的星系；[Jiaxuan Li et al. 2021](https://arxiv.org/abs/2111.03557)则比较了HSC，DECaLS, SDSS ,Dragonfly这四个对halo巡天的测光鲁棒性，方便我们可以根据不同对象选择不同的数据。
	
好，我们问题依然是这些unresolved 的矮星系halo长啥样，他们的tidal stream 子结构特征里面是否蕴含着其卫星星系或其过去的并合吸积历史。这时候由于我们无法在获得解析的恒星运动学，因此对星系外系统中个别星流的建模受到阻碍，尽管许多星流内有的发光运动学示踪剂分子，例如球状星团或行星状星云，但依然困难。不过好在恒星都是resolved的，我们能分离出恒星星族的星晕子结构把他们作为研究样本。需要Subaru这种大口径或者空间望远镜才可做到。
	
### 然后是我们的研究内容以及创新
stellar halo的质量虽然仅仅占了所有恒星质量约1%，最早人们把这些晕星当作old, metal poor 类似于球状星团的星。MW的晕星特点是高自行，自转较小，空间分布是球面分布。巡天数据表明晕星又复杂的结构和多种成分以及还没有达到弛豫状态的子结构，在连续不断的从附近星系中潮汐吸积气体物质，与之前所预言的层次并合模型吻合。我们感兴趣的问题是这些stellar halo结构形成的细节到底是什么？他们的年龄分布、金属丰度分布、各自质量密度等信息，这些信息将会告诉我们他们到底是：小(同量级)质量星系并合留下的遗迹，星系内气体自己成团塌缩本地形成，还是恒星被散射作用，亦或者落入球状星团瓦解。
	
<font color=#4682B8>研究目标： 我们目标预期建立近邻可分解星系的Halo 轮廓库，金属丰度分布，以及星流子结构等特征，限制halo的起源机制，期望发现更多的矮星系和潮汐流</font> 
-  好玩的问题是，这些特征是有可数多的类么，或者说看到什么特征我们就知道其发生过什么(小星团落入被瓦解之类的)
- local group 中大量的星流是特殊情况 别的group没有这么多，还是说正如宇宙学模型预测的那样这是一种很普遍的结构
- 这些结构有没有形成速率呢？
- 这些结构的性质（亮度，金属丰度，年龄）是否和模型预言的一致呢？
- 从这些子结构中，可以外推得到暗物质中重子过程什么信息呢？ ^a7c14c
- 星流的质谱中，可否得到前身星系的质谱。
- 晕星中这些特殊结构中星占比多少？
- 并不一定所有星系都会有这种遗迹，那些大星系中星流的原始机制是什么？
- 这些星流和盘之间会有关系么
 
- < halo 的profile，形成机制可能机制，强弱交互，短暂或长时间交互，交互后的残留，星流与气体的分布关系，重合说明了什么，不重合又说明了什么？晕星的信息还可以说明什么，除了过去的遗迹的作用时间，其年龄金属和气体金属的关系>	
<font color=#4682B8>创新：1. 在HST/HSC基础上做了更细致量化的分析 2. 密集星场测光的新手段</font>
对应的工具：CMD+SED 多波段的，SFH，Metallicity(后面这俩靠恒星计数)
计数和路线：密集星场处理，恒星技术（层次化贝叶斯模型，低信噪比将晕约束）
### 计划和发展方法
对HST的数据进行再分析（ANGST，GHOST）
	做M81的Halo 轮廓和金属丰度
	M82 Halo中奇怪的地方也值得探索
	四年计划
s
最重要的是，我对这个课题思想，stellar halo 的认知思想，不是拾人牙慧这么粗浅的工作而已，知识不是知道

## Cosmic Star Formation History
摘要: 
新一代各种星系巡天项目革新了我们对于星系的形成和演化认知.那么天文学家是如何来通过技术和理论来认知其历史和恒星形成? 虽然一致认为3.5Gyr 时候有一个恒星形成峰值,大约z~2, 有意思的是恒星形成的共动变化和星系中心大质量黑洞的吸积涨落貌似有一种协同演化的意思,颜色选择条件 对于活跃的高红移星系(2.5<z<9)的中性H的吸收特征很敏感, IR红外颜色对于区分z~2附近的活跃与否的星系很有效果,NIR近红外 部分则是用来研究恒星质量密度分布的手段, 除此外还要FIR远红外. 近邻星系的SDSS数据告诉我们 活跃的星系更加偏蓝且暗弱, 而更亮偏红的星系则是更宁静一些.  早先的远处扰动在冷暗物质引力不稳定下增长,出现了"bottom-up"的物质形成历史. 用N体模拟可以高精度的早期辐射主导前期的宇宙情况, 可依然有一些过程比如**重子弥散, 冷气体形成恒星,星系盘和核球的形成, 星系中或星系间的气体化学元素丰度,以及扮演恒星反馈作用的SNe, 超大质量黑洞在恒星形成和其巨大的星系际喷流有何关系**,  

我们期望更深的数据可以揭示第一代恒星形成年龄, 其大小,质量,颜色,光度,金属丰度,聚集程度等星系的stellar部分信息. 过去20年集中精力在星系光谱各种奇怪的发射线,用FUV和FIR数据来揭示经验性的SFH和金属分布.比如:
- UV连续辐射线在年轻星系中主要由大质量年轻恒星主导.
- rest-freame NIR光则是由类太阳恒星组成了恒星大部分的质量
- 星际间尘埃极其容易吸收UV后再辐射到IR部分,所以星爆星系的FIR辐射会更明显, 利用此特征来追迹年轻恒星~.

一个有意思的问题: 我们今天所有的元素都是宇宙大爆炸产生的么?

### 宇宙化学演化过程
如果我们想量化宇宙整体的恒星形成和金属丰度,最好从建立标准方程开始:
$$\begin{align}
\frac{d\rho_*}{dt}&=(1-R)\psi \\
\frac{d\rho_g}{dt} &= -\frac{d\rho_*}{dt}\\
\rho_g \frac{dZ}{dt} &= y(1-R)\psi
\end{align}$$
其中$\rho_*$ 代表为年老恒星的遗迹的质量密度, $\rho_g$为气体质量密度,$R$代表每一代恒星返回到星际中的质量比例, Z为气体和新诞生恒星中的金属丰度, $y$为每一代恒星产生后抛射到星际中的净金属丰度.

就可以去做时间积分,得到各个参量在对应积分红移处的值,对于给定一个$IMF$ 可以用来计算$R,y$ 的大小, 当然用Salpeter和Chabrier得到的结果相差蛮大的,不同的返回比例和净值,也和恒星模型有关(比如是否旋转).  

### 利用光度测质量
知道星系的SFH过程需要利用质光关系推算质量, 并不是所有波段都适合用来测量SFH, 其中NIR到MIR范围的测量非常重要. 有意思的是宁静星系的质光-红移关系和活跃星系的并不相同, 回忆起大质量星系基本都是偏红且亮,小质量的星系偏蓝更暗弱,所以原则上来讲大质量星系探测到的更多一点,因此完备性更高. 由于恒星的光通过尘埃会衰减,尘埃再辐射红外,造成我们看到的偏红,

对于近邻可分辨星系, 年龄-金属丰度-尘埃 之间的简并,需要通过光谱来限制恒星的金属Z,年龄, 但即使如此也需要做一些假设来解释光度?这些假设包含IMF,金属丰度分布,消光,或者特殊的SFH. 

对于IMF其包含了质量-年龄和光度的内在联系, 比如亮星主导光度,暗星主导质量部分, **大质量恒星都在亮端, 小质量恒星在暗端(年老).** 而从星系整体的测光是无法限制IMF的, 而光谱也不行. 最好的办法就是数数, 恒星质量和数量的关系, 但这只在近邻星系中才办得到.次一点的办法就是测量星团的质光比(动力学速度弥散旋转曲线whatever), 缺点是对于高红移星系就失效了.

因此缺乏更多信息的条件下通常假设认为IMF是一个不随红移变化的均匀关系. 低质量端和高质量的恒星演化轨迹不同,因此IMF中其角色也不同, 低质量恒星贡献了大部分星系的质量但对光度几乎没有贡献,因此修改小质量端仅仅是对质光关系做微调, 只有中高质量端的改变,才能影响星系的光度,演化质量,金属丰度,也就死显著改变IMF的轮廓. 

得到SFH或者恒星质量,通常用星族合成模型, 单星族用的最多, SED主要由亮星主导(但亮的都是年轻的),并不会对质量部分造成约束.

#### 恒星形成率测质量
测量SFR主要是测量的都是大质量端的形成率,因为他们贡献了大部分的光度,然而不同的失踪物敏感于不同的质量范围,比如$H\alpha$ 倾向于$O$型星,而$UV$线则是对应质量范围较广且年龄较大区域.先说UV,新形成的恒星辐射光谱范围很广也很强(针对于我们观测而言), 无论大质量还是小质量, 都经历过辐射UV阶段,但是大质量的UV阶段占比要更短一些,假如同一时期产生不同质量范围的恒星,演化10 Gyr中所有的能量辐射的一半,是来自于早期的100Myr且主要是UV部分. **所以UV是大质量恒星的形成tracer** 前提是SFR大幅变动时标要大于$10^7$y年,也就是UV辐射主导的时标内? 不过小心$UV$辐射也和金属丰度有关系, 越贫其辐射越强. 差100倍的Z可以在$L_{UV}$差0.24 dex, 再简单的建立了一个$SFR= \kappa *L_{\nu}(FUV)$  ,然后发现测得右边第一项系数可以认为是一个常量,那么就可以用来反过来算光度,再用质光比算质量.

IR部分辐射(一般指的是8-1000um)一般认为来自于尘埃的辐射,其强度会正比于从恒星的UV部分吸收到的强度,也可能是年老恒星加热后产生的辐射,或者AGN造成的. 那我们就需要把尘埃的辐射建模,拟合模型和观测这种方式选取波段在尘埃的吸收峰附近,或者是用SED,该方法改进在于波长不在峰值附近, 至于FIR和MIR部分辐射成分更为复杂,FIR主要来自于很冷的气体(15-60K),而MIR则可以是有机分子和硅酸盐矿物成分,更何况其波长范围还更宽($3-20\mu m$).对于MIR的观测Spitzer Space telescope是第一个先例, 不过也正是由于其波带很宽,MIR的光度转换为IR部分的光度还需要建立更适合的模型模板.*Herschel Space Observatory* 能力更强,3.5m镜子在$70-250\mu m$对于目标分辨能力强一些. 但对于高红移的星系搜寻, 二者都依然存在短板. 

经验来讲,两个设备对于星系在MIR和FIR的比值和SED模板的预测值在24um处的吻合不错但仅限于红移$1.3<z<2.5$ 要是红移再高一点则SFR值在SED模板下估计会偏高. 一般来讲星爆星系有更致密更高的质量面密度的SF区,而一般的盘星系的主要恒星形成区有一个大范围且密度较低的区域. 目前看到大部分IR超亮星系亮度可达$L_{IR}>10^{11}L_\odot$    多属于并合驱动的星爆星系,而在红移2附近那些更亮的Gal, 我们政治为正常的 主序星系,其SED和近邻的恒星形成的盘星系很像. Elbaz et al. (2011) 利用Spitzer 和 Herschel的高红移样本($0.3 < z < 2.5$)数据建立一个普适的主序SED模型,貌似这个红移区间内星系大家的IR光度都差不多.所以可以考虑SFRD的变化, 比如Rodighiero et al. (2011) 就发现starbursts的贡献只有不到$10\%$ ($z\sim 2$) 

关于MIR和FIR部分需要用太空望远镜才行,(麦克斯韦望远镜，JCMT,装备了大视场成像SCUBA-2)对于高红移目标探测在地面应该是实力高于ALMA, 有意思的是亚毫米波段测量波段正好超出尘埃辐射峰值位置,所以该辐射会被尘埃吸收很多,造成一个在$1<z<10$的目标其IR光度可能看起来没什么区别.类比UV部分,IR也可以写一个SFR公式,那么总的可以写为: $$SFR_{tot} = K_{FUV}L_{FUV} + K_{IR}L_{IR}$$
分别看FUV和IR部分计算的SFR/L, 发现FUV部分到了$300Myr$ 就趋于水平(大质量星离开了UV主导阶段),IR的光度则还在增大(由于小质量恒星依然在不停的诞生),总的来说不同的恒星质量分布和尘埃可以导致不同的净吸收特征, 来自恒星形成区的星风可以吹散尘埃其他区域中的年轻恒星依然在星系介质中被遮挡.发出UV部分进而被转成IR.

对于高红移只有少数的关系可以测试UV红化和消光.用不同的追迹物发现对于高SFR的星系UV消光差别很大,说明基于若是用UV消光红化去估算SFR会严重低估SFR. 或许说明不同的星系其尘埃衰减和UV关系会不太一样.因此对于UV数据得到的SFR要很小心.即使UV红化很可靠.

其他的追迹物入星云线,射电,X-ray辐射.  星云线主要是H线($H\alpha$and $Ly\alpha$)多一些,依赖于OB型星的UV辐射,因此用来追迹大质量恒星是一个不错选择,其他的比如$Paschen~ \alpha$ 线也可以用来测SFR, 但只适用于低红移.射电辐射来自于SN加速的电子非热辐射部分,其于FIR辐射有一些强相关性.抛开AGN不谈,设点辐射在早期宇宙由于逆康普顿散射会被抑制,因此很难用射电去得到高红移(具体是多高我不太清楚)的恒星形成星系.

X射线一般来自于AGN,也可是年轻恒星或者x-ray双星,然而x-ray光度和SFR关系会随着恒星年龄等参数影响x-ray双星比例进而造成关系不是很稳定.这一部分限制最多,不建议用这个办法.

### 为恒星称重
我们熟知年轻恒星主要贡献UV波段,而冷的低质量恒星贡献星系的质量部分(其波段在NIR或者IR),因此质光比和时间关系中,UV或者蓝端的变化随时间变化敏感性很强.年轻恒星会很快离开主序之后辐射主要以IR或者NIR为主,所以NIR用来追迹星系的总的恒星质量是一个不错选择, 但也不能忽视0.1Gyr的恒星和10Gyr的恒星辐射同样1um的流量区别还是很大的.

一般用颜色图或者SED来推测质光比, 再利用观测的光度来计算质量. 这套过程先从光谱模板拟合开始,模板参数包含SFH,年龄,金属丰度和尘埃消光. IMF则是经过修正适用于这个星系的, 然后模型套用一个波段来产生该波段的流量调节上述参数使得$\chi^2$ 最小就行.  

原则来讲这方法也能用来限制星系年龄SFH或者消光程度什么的,实际上这些参数存在简并性,如age-metallicity 对颜色的简并, 只能是测量尽可能多的波段来对年龄限制更多一些.而质量貌似是最好限制的,因为其他参数的简并对质光比的影响趋势都是一致的,所以对最后质光比的轮廓不会有很大影响.也就说年龄不确定虽然,但是质量我们差不多可以确定多一些.

再就是利用IMF, 这里影响质量的不确定因素就是SFH,观测到的光度由相对年轻恒星主导,于是如果一个星系最近发生恒星形成活动的话,那么其光度增加,质量但是并不会发生很大变化, 这就会让我们低估了该星系中年老恒星的质量,这种由于SFH导致的误估称之为"outshining", 因此对于高红移星系缺乏SFH限制的话,几乎得不到其恒星质量的限制.所以反而越活跃的星系其质量越难限制,反而越平静的星系更是我们所喜欢的.  使用SFH会假设其光滑变化的趋势(尽管现实不是),Papovich et al. (2001) 用SFH去估算$z\sim 2.5$ 星系的质量,发现误差小于0.5 dex,而经典的不确定度为0.25 dex,差了两倍. 如果他们考虑质光比因素中年老恒星的比重, 就会得到比原来大3-8倍的质量. 到如今虽然JWST可以在NIR很厉害,但是outshining问题会一直限制我们对质量的估计,除非对SFH有好的限制.

对于那些$z>6$的星系,其SFH要更简单一些, 对于其质量估计的不确定是否会更小?Curtis-Lake et al. (2013)做了统计.

## 巡天追迹星系辐射历史
需要留意虽然很多人研究了星系的SFRD,SMD, 大部分数据来自于HDF-N, the Hubble Ultradeep Field (HUDF), GOODS, and COSMOS, 虽然相同数据,但是测量方法可能并不同的, 真实的宇宙中SFR变化并不会因为他们方法变而变.

### UV巡天
SFRD的分析主要还是依赖于UV连续辐射, 静止坐标系下FUV的SFRs利用HST或者地基望远镜可以看到$1.4<z<6$ 部分,尤其是测光红移的迫切需要,z<1 部分UV辐射需要太空望远镜. Lilly et al. (1996)是第一个开始结合光谱红移和多波段测光来获得光度函数LFs和光度密度LDs. The Canada-France Redshift Survey (CFRS) 用的4m Canada-France-Hawaii镜子,能够到$z<1$的星系,Lilly et al. 发现z~1到现在的LD衰减了一半,归结为SFRD的骤减.Madau et al. (1996) 继续深入更高红移样本($<z> = 2.75,4$),  奇怪的是并没有扩展LF的暗端,就是单纯套用人家方法重新做了新数据.后来陆续有人扩充红移样本完备性,发现在$z<1$有一个"rise and fall"的趋势, 推断在$z\approx 1 ~and~ 2$ 有一个峰值 

早先的工作Treyer et al. (1998) and Sullivan et al. (2000) 用 FOCA balloon-born UV telescope 测得$z\approx0.15$ 部分,后来GALEX, 2dFGRS($56 deg^2$),SDSS有了更多数据,Wyder et al. (2005) 测量了$z\approx0.055$部分,Budav ́ ari et al. (2005) 测得$z<0.25$ ,Robotham & Driver 提出了推导UV光度函数的办法,Salim et al.则是用GALEX测光信息当作手段去获得SFRs和SFRD. Arnouts et al. (2005)用VIMOS VLT Deep Survey (VVDS) 得到$0.2<z<1.2$处的LFs, Schiminovich et al. (2005)用LFs测量LFD,发现$\rho_{FUV} \propto (1+z)^{2.5}$ ,这个关系被广泛引用,虽然他们只用了约1,000个星系其红移分布范围只有$\Delta z=1$ ,空间分布只有$0.5 deg^2$ 这么大,因此可能存在宇宙学方差问题, 太空望远镜方面HST唯一配备了UV波段,Alavi et al. (2014) 用 Abell 1689星团背后的透镜星系拓展了光度函数暗端, 发现没有拐点.  之后很多年里值得注意的Reddy et al. (2008) and Reddy & Steidel (2009) 他们用Keck 望远镜的光谱,用深场颜色选择后的样本研究LF的暗端, 为如今提供了大部分光度函数的研究方法.更高的红移处$4<z<7$ HST主导了LBGs的巡天, The Subaru telescope(地面)也提供了很重要的数据.  HST的ACS有两个主要巡天为SFRD测量提供了支持, GOODS (Giavalisco et al. 2004b),这些样本中包含数千都在 $z\approx 4$也有约1,000个在红移5处,The HUDF (Beckwith et al. 2006)的燕娥本要更加暗弱. 这些IR观测的 Lyman break 星系分布在$z\approx 6~and~8$,还有一些未认证的红移到12的星系.

有了观测样本数据,然后开始了分析LF演化的研究,一致的结论是至少在 $4<z<7$范围它是动态的,随着时间变得越来越亮(Bouwens et al. 2007, Grazian et al. 2011), 也就是说LBGs的数密度随着见越来越多,而更高红移认证的样本少限制了研究,但一致认为UV波段光谱在$z>4$要更蓝一些 (Bouwens et al. 2012a, Finkelstein et al. 2012a, Dunlop et al. 2013), 且在暗端的$LF$的斜率要更抖一些. 不过值得一提是作者认为这些研究虽然对星系演化提供了重要的帮助,但对宇宙整体的恒星形成没有什么影响, 因为根据估计, 大约$\sim1\%$ 的如今宇宙SMD形成于$z>6$时期.

### IR巡天
对于$L_{IR}$是从$8-1,000\mu m$ 范围内的光,其中包含了大部分尘埃热辐射,The Infrared Astronomical Satellite(IRAS) 使得探测远红外端光度函数成为可能. 借助于它,最长波长到100μm, AKARI 则可以到160μm, Herschel (250–500 μm),  ground-based (sub)-millimeter observations (1.2 mm ,850 μm). 使用这些数据发现IRLF 的亮端截断后不像指数形式那么陡 ,有人就认为是2个power low组合(e.g., Lawrence et al. 1986, Sanders et al. 2003), 或者说是 log-normal 加 power law(e.g., Saunders et al. 1990). 而在暗端则有人测量到较陡的趋势$\alpha = −1.8$ (Goto et al. 2011a),但也有人测的是较平的趋势, 因此在暗端的争议要比在亮端更大一些.

本星系群中宁静星系的FIR辐射测量的IRLF的增幅拐点值(the knee )大约$L^*\sim 10^{10.5}L_{\odot}$(Sodroski et al. 1997), MW的$L_{IR} \approx 10^{10}L_{\odot}$ (Sanders et al. 2003) ,说明本星系群的IR光度并不单纯的是年轻恒星组成(因为拐点处的时间毕竟是以前 理想的应该MW在统计曲线的顶点). ISO提供了深度更深的数据,探测到几百个红移小于1的星系,这些目标的尘埃辐射随红移增加而迅速增加也, 意味着LFs随红移的变化可能也会有影响. Spitzer 极大增强了IR观测数据质量,Le Floc’h et al. (2005) 用$0.3<z<1.2$ 的样本得到IR下的光度函数$\rho_{IR} \propto (1+z)^{3.9\pm 0.4}$ , 显然比FUV的2.5指数要更陡峭, 他们认为是$L_{IR} > 10_{11}L_{\odot}$ 的星系,有$70\%$的IR辐射来自于$z\sim1$ 时期(当今部分只有5-15%,这是低红移样本, Rujopakarn et al. (2010)用光谱红移小于0.65的样本和24-μm 中$z>0.65$样本结合起来,该工作成为$z>1$本星系群和深场研究的最好桥梁.  对于Spitzer 24-μm-based LF的研究, 都倾向于IR的LF高红移比较平, 红移2比红移1要低或高一些. 

而IR对于高红移处的LF估计争议比较大, 无论是暗端还是亮端,暗端的数据对LF斜率限制很少,很少有测量的样本能到红移2的位置,因此很多研究不得不一句低红移的测量来假设暗端的斜率.

Magnelli et al. (2009, 2011)使用深场70-24-μm 数据发现IRLF在低红移的暗端要平一些,红移2附近只是要比本星系群的IRLF拐点处要稍微暗一些,斜率同样不能得到限制, 不过其结果和Reddy et al. (2008) 用UV选择的星系得到的LF的斜率和尘埃吸收很相似.

关于更多用 *Herschel* data 的研究, Gruppioni et al. (2013),Magnelli et al. (2013) 二拨人虽然方法不一样, 但由于数据有重叠的部分,所以不能严格说他们的结果是相互独立的. 他们结果都表示$z>1$的时候光度演化要比Spitzer analysis更明显一些,Magnelli 认为是因为Herschel对FIR更好的测量带来的结果, 但我们发现都没有对高红移的暗端斜率进行有效测量,都选择使用本星系群测量的值外延得到的推算值.Magnelli et al. (2011) used α = −1.6,而Gruppioni et al. (2013) used α = −1.2,但是他们竟然能算出查案不多的IR总光度.

对比UV和IR的LF结果图, 说表对于低的恒星形成率其消光也不会很高,低光度的星系对于SFRD在高红移出的重要占比!
- 相比于UV,IRLFS的截断要更平缓一些在高光度区域
- 同一红移下IRLFs更加延展向高光度部分,而那些活跃星系会更容易被尘埃遮挡.
- 光度一定是和红移有一个演化关系的尤其是IRLFs
- UVLFs在高红移的暗端表现出更陡的斜率,虽然这点没有得到大家一致认可,但很多研究都确实测量到了这一陡的斜率在红移高于2时候.
在Spitzer and Herschel之前, 地基的亚毫米波 单天线望远镜JCMT,对尘埃辐射有很大的研究帮助,测量LFs和SFRD的最大困难在于识别亚毫米波源的对应星系和其红移,这是因为其单天线和光束尺寸所天然带来的,也可能是对应体太暗弱不可见.Barger et al. (2000)就是第一个用亚毫米波来估算SFRD的男人,2012年他又重新用亚毫米阵列重新升级了一下他们的结果, Chapman et al. (2005) 测量了这些射电证认的SMGs的光谱红移, 得到了其LFs.Wardlow et al. (2011) 用他们的样本,这次用测光红衣来做,样本也重新筛选了一次. 发现尘埃SMGs(亚毫米星系)对于高红移的SFRD的贡献很重要, 最后提到CIRB(cosmic IR background)对高红移的尘埃恒星形成的限制.高红移处,尘埃辐射向长波移动,Be  ́thermin et al. (2012)估算出大概17%的CIRB来自于$z>2$的星系.虽然看起来17%很小,单依然允许大量的恒星形成在z>2时候发生,而且这里没有考虑24um的源,如果考虑了比例会更高.

### 星云辐射线巡天
高红移的SFR量化最普遍用的就是通过星云辐射线,其中$H_\alpha$是最有力的,其他元素比如$O_Ⅲ$之类的,但其他元素对于金属丰度,ISM环境 的依赖比较强. 所以还是更普遍于$Ly\alpha$巡天高红移目标, $H_\alpha$在光学波段红外区域,最近的IR技术在4m和8m级镜子上(e.g., UKIRT WFCAM, CFHT WIRCAM, NOAO NEWFIRM, VISTA VIRCAM, VLT HAWK-I),, NIR的多目标光谱成像(e.g., Subaru MOIRCS and FMOS, Keck MOSFIRE, VLT KMOS, LBT LUCI).,无缝光谱(WFC3 on the HST),这些各有长短. 

WISPS (Atek et al. 2010)利用$H\alpha$ 得到LFs. 窄带巡天很少会依赖消光改正,但是在光谱巡天中却很有用. 最后估算的LF和SFRD,Gunawardhana et al. (2013) 给出了最新的从低到高红移分布的测量结果,最早的用H线得到LF则是由Gallego et al. (1995)给出,随着SDSS给出了更多的光谱和测光数据,Brinchmann et al. (2004)研究了本星系的SF,Salim et al. (2007) 主要用测光数据介个GALEX的UV测量,二人的结果极其相近,Gunawardhana et al. (2013)在他们基础上探索了稍高红移($z<0.35$)暗端的LFs.,

需要强调一下,直接的消光观测往往不可靠,光谱仪的狭缝分辨率不可分割的会把$N_Ⅱ$和$H\alpha$ 混合.
新一代的高红移测量随着窄带巡天而开始,WFC3等等.Hα surveys比如Ly et al. (2007, 2011), Hayes et al. (2010), and Sobral et al. (2013).后来有Subaru Suprime-Cam (z = 0.40) and UKIRT WFCAM (z = 0.84, 1.47 and 2.23), VLT and its HAWK-I image. 这些项目都证实了L会随红移演化呈现增大趋势,暗端的斜率$\alpha\approx1.6$ ,和UV部分很相似.

### 射电巡天
射电信号主要来自于活跃星系的恒星形成活动,以及AGN,电子的free-free辐射占据了高频部分,而同步辐射则是在低频部分(来自于SNe).有一个难处就是如何把AGN信号和想要的恒星形成信号区分开, 实际上应该并不行,他们一般直接把强的射电信号排除掉, 剩下的里面 通过射电谱指数,射电形态,radio/IR流量比 optical SED criteria光学SED判据,来区分, 但这几个都很难测量,更不用说用在暗源上面.

本地的射电LF可以用来估算当下的SFRD(Machalski & Godlowski 2000, Condon et al. 2002, Sadler et al. 2002, Serjeant et al. 2002, Mauch & Sadler 2007),毕竟没有尘埃什么的影响. Dunne et al. (2009)发现radio和NIR光度有线性关系(虽然红移依赖的).之后也去测了SFR和SFRD,但是和Karim et al. (2011)结果区别很大,一个是先增后减小,一个是单调减.

### 恒星质量巡天
NIR技术的进步,用NIR测光通过其星系的恒星质量来采样星系也变得可能,直到千禧之交时候作者们才想到把恒星的测光 红移 金属丰度等性质放到星族合成模型中转化成恒星的质量

早先没有SDSS和2dFGRS数据时候, (Persic & Salucci 1992, Fukugita et al. 1998, Salucci & Persic 1999)这些人想要估算本地宇宙的重子物质含量和SMDs, 这个想法加速了新一代光谱巡天的发展. 后来Cole et al. (2001)使用2dFGRS数据测量LF更加准确之后,使用星族模型就能推算出星系的质量,进而得到本星系的恒星质量函数,GSMF, 使用各种星族模型, 质光比关系就是从测光中得到了(Panter et al. 2007, Baldry et al. 2008, Li & White 2009).

随着越来越多的样本,GSMF更加精细的拟合开始, 包括triple Schechter函数,或者其他函数形式, 无一例外发现在低质量端($<10^9M{\odot}$ )要比之前的斜率更加陡一些(e.g., α = −1.47) (Baldry et al. 2012). 在高红移部分, Brinchmann & Ellis (2000)测量恒星质量貌似不随红移($0.4<z<0.9$)而演化, 尽管SFRD在这里衰减很快,Cohen (2002)无独有偶也得到了类似的结论,因为这段时间SFR衰减很快很少有新的恒星诞生,因此质量累积的并不明显. 直到拓展时间基线, Dickinson et al. (2003), Fontana et al. (2003), and Rudnick et al. (2003)使用更深的NIR图像,two HDFs, HST NICMOS (HDF-N) and VLT ISAAC (HDF-S),以及大量的测光和光谱红衣来测量SMD到$z\approx3$ 处的值在如今SMD的5-15%范围, 到达一半时候大概是红移2的时候, 要验证这一点光靠哈勃的小范围样本是不够的.

Spitzer发射后带来耳目一新的IRAC图像, 之后的巡天项目比 如GOODS, S-COSMOS, and SWIRE非常适合用来获得SMFs以及SMD在高红移的分布. 自从2006年之后, 达索关于SMFs文章使用的都是IRAC数据, 同样的数据反复分析,Fontana et al. (2006), Pe  ́rez-Gonz ́alez et al. (2008), Kajisawa et al. (2009), and Marchesini et al. (2009)这些人分析的GOODS区域$z\approx4$ ,Arnouts et al. (2007), Pozzetti et al. (2010), Ilbert et al. (2010), and Brammer et al. (2011)研究稍微浅一些的区域(e.g., COSMOS, VVDS-SWIRE, NMBS)红移大概小于2, 虽然方法不一样他们,但是得到的SMF在$0<z<3$的演化图景近乎一致,比如特征质量,暗端斜率,除了特征密度外都稳步演化. 这确实说明了SMF在高红移的暗端斜率要更陡一些. SMDs的结果在不同方法里相差不到2倍大小,因此关于质量的演化图景大致建立了起来.

Spitzer的IRAC有能力得到$z>4$的星系恒星质量,所以出于这个原因, SMDs在这个范围的结果几乎都来自于GOODS和HUDF区域, McLure et al. (2009)挑选了LBGs在红移5-6附近去测量SEDs和质光比,来估算SMD,其他人也无一例外都选用LBGs因为他样本最丰富Yan et al. (2006), Eyles et al. (2007), Stark et al. (2007), Verma et al. (2007), and Yabe et al. (2009), 因此得到的结果都大差不差, 由于是LBG 的SMF, 其低质量端斜率要比UVLFs的稍微缓一些,这是由于质光比在UV端更暗弱一些.

值得留意的是星云线的辐射, 之所以这么说是因为在高红移中LBGs要比UV-selected星系有更强的星云线,按道理这时候就需要考虑这条线对质量估计的影响,没有这条线的考虑会低估10-70%的质量,因此非常有必要验证这个影响.

### 最新的一些问题
- 本星系的测量SMD主要依赖于光学数据(SED,测光,光谱),尤其是在暗端斜率的不确定性. 但及时加入了NIR部分也依然存在漏光的情况(e.g., Bell et al. 2003)
- $0<z<1$ 这时候是正好是恒星形成衰减的截断,测量的最大难点是他们覆盖了极小的天区,因此其结果会受到宇宙方差不确定性的影响. Moustakas et al. (2013)分析$5.5°$ 立体角的范围研究SMD和SFRD. 未来新的宽场巡天VISTA VIDEO (Jarvis 2012) (ground-based NIR, three fields, 12 deg2) SERVS (Mauduit et al. 2012) (Spitzer IRAC, five fields, 18 deg2, overlapping VIDEO)会促进质量函数估计,前提是测光,红移信息要很可靠才行.
- $1<z<4$  红移大于1的时候,就需要更深的巡天来探索那些暗弱目标,原则来说有很多适合的天区.但是只有少数几个巡天天区的数据被使用, 一方面是因为他们有最好的光谱和测光数据,一方面他们有多波段的信息. 总而言之这些天区适合各种研究.UV波段可以轻松到$z>1.5$ ,在红移2和3附近则是选用LBGs目标. UV辐射会尘埃恒星形成区影响, ALMA 虽然能看的很深但是其观测立体角太小了.恒星质量的估计这一块没有什么问题.
- $z>4$ 这些星系大多是用来测SFR和SMD,用到的天区数据非常有限,都是用的HST数据,天区覆盖小,所以难免担心视线集中效应和宇宙学方差影响. 后者会由The CANDELS program (Grogin et al. 2011, Koekemoer et al. 2011)实现多波段观测. 主要集中在NIR和UV波段,大质量星系的SFR要通过亚毫米波来检测,这些高红移星系可以通过CO辐射来认证,但是这个辐射线对SFR和SMD的贡献到底如何也尚未清楚,但是光谱认真或者测光红移估计对于这类目标依然很难,期待JWST可以解决.


## 从观测到一般原则
早先Lanzetta et al. (1995)建立宇宙化学演化方程开始,有人就开始用观测到的$H_{Ⅰ}$ 来推算恒星形成率SFR,Madau et al. (1996, 1998b) and Lilly et al. (1996)直接用星系巡天数据来推测SFRD.后者是将演化方程和光谱测光性质中才得到的:
$$\rho_\nu(t) = \int_0^t \psi(t-\tau)L[\tau,Z_*(t-\tau)]d\tau$$  左侧是光度密度,右侧则是SFRD,金属丰度Z,和每单位质量所辐射的光度密度L.

### 恒星形成密度

$$\rho_{FUV}(z)=\Gamma(2+\alpha,0.03)\phi^*L^*$$ $\Gamma$ 是不完备的gamma函数,$\alpha$ 则是暗端的斜率.
对于此的研究就很多i.e., α = −2.01±0.21 at z ∼ 7 and α = −1.91 ± 0.32 at z ∼ 8 (Bouwens et al. 2011b), 如果再加上IR的部分那就可以计算SFR了,以及$\kappa$ 系数.  

要想要获得FUV的LFs就必须要一个稳定的对尘埃吸收模型,之前人们要么用Meurer et al. (1999)的吸收红化关系或者是星族模型来拟合UV部分的SEDs来得到LF,现在考虑吸收-红移关系, 发现如不是在本动宇宙,那么其还是很和谐的, 越暗弱星系其UV光谱的斜率越蓝,因此尘埃的红外吸收也就越少. 因为暗端的FUVLF的斜率很高,那些被红化的FUV星系大部分都是来自于那些暗于本动宇宙光度L的星系,

然后得到SFH的结果:明显在红移2的时候有一个峰值.

