# 2/4/2022
回归预测，分类
1.输入方程 2.定义loss. 3 优化参数
![[Pasted image 20220402093014.png|500]]
Relu，sigmoid以及liner 激活函数
池化层：增加非线性，均匀缩减数据规模

计算机视觉工作流？
图像 -> 预处理（Noise reduction,Scale,Change clor space）

batch_size ~ 学习率，learning_rate = batch_size * base ls

学习率的调整来避免一部分局部最优，不能保证一定得到全局最优
batch_size 最好选$2^n$,4或者8或者16，也可以128
数据集的shuffle 记得

Blog and paper, reading

#### 7/4/22
$\kappa^2$方法和其似然概率分布两种方法
#### 8/4/22
Quenched gals and star forming gals. Their relation of SFR and age.  massive BH grow rate, $t_{max}$  : SFR最大对应时标

Cool model: From cole dense cloud of filenment
Hot model: Shock-heated 
# 14/7/22
## Problem
Optimizer choice: SGD, Adam,Adadelta, etc.
loss function choice: corss-entropy loss, focal loss, etc..
Data preprocess: **simulated image - background, No flat**

仿真的数据噪声分布：
possion noise 的sky_level越大，噪声越大。目前设level=0.最后的噪声均值为2，最大为
sky noise部分，我的天光背景26等，噪音大概1.3或者1.4的样子

# Fri_other
## 4/7 璐哥精度

## 4/14  崔哥星系处理
What kind of relation in the color gradient and their bulge, morphology
GALFIT function
massive quiescent galaxies, $R_{SMA}:$ 有效半径


the photon number density being $N(E) ∝ E^{−Γ}$ 

## 6/16 王瑞 LAMOST 

分辨率低 和观测波段范围总是一个代价博弈状态, LAMOST 的$R\sim 1800$ 

时域和非时域

恒星大气参数测量: 正向建模(通过光谱模板和参数来拟合找最佳), 经验回归(回归预测的形式,一种是类似于二次回归么? 另一个是啥)
经验光谱 基础上去插值. 优缺点啥来着?
标签迁移. 中分辨光谱和高分辨参数一一对应建立回归关系. 缺点依赖于高分辨的标定准确度. 简单说就是大哥死了小弟全死.

流量空间?

域迁移. 生成理论光谱, 得到离散的点. 因此还需要一个插值器. 怎么选插值器
理论光谱和实测光谱存在不一致的是. 通过 一个投影算法, 可以保证高维 到低维的映射后保持欧氏距离不变.
引出迁移学习: 特征空间对二者进行提取,  生成对抗 后实现一种一致?   一个迁移到另一个后特征空间一开始不重叠, 对抗过程中使其重叠混合. 这是什么. 最后可以实现 二者互相转移.

LAMOST 这些低信噪比成员星 是距离还是天气 还是消光带来的.  大概多少等可以算好...
![[Pasted image 20230616154420.png]]

## 6-20 杨航 宇宙学模拟
初始暗晕的角动量来源: Tidal Torques theory(四极矩 和潮汐场 作用下).自旋参数 $\lambda = \frac{J}{\sqrt{2}MVR}$ ,是一个对数正态分布. 自选越大,盘的尺寸越大($r\varpropto \lambda$ ). 早期的恒星形成多的话会减小角动量. feedback作用很重要.

同样的初始条件, 对比TNG和EAGLE两个模拟, 发现其星系的角动量演化不一样.  对比后发现是存在一个Fountain(被恒星作用后粒子会被喷出去然后cooling又落回来). 根源在于二者采用的feedback机制不一样.  分辨率过低时候, 气体加热的作用机制被稀释了.  加热了但很快又冷却了,相当于没加热. 

Q: 这个因素会影响星系演化那些过程? 只是影响星系 50kpc以内部分是么?
大尺度模拟下这些差别就很小了. 

## 花花: Accessing the association with GCs, NGC 4147 substructure
Sagi.. the first passenger ? How do u known?
ra,dec, pmra,pmdec, v_r,dist
NGC4147 , ruled out the association with Sgr by pm info. So who is him?
DESI survey, Gaia dr3 stellar population, parsec fitting.
NGC 4136 older or younger than Sgr.


## Martin: 一些基础的宇宙学问题,比如
Why expansion? Ob and Theoretical
我们真的看到的是宇宙膨胀么?????
1. Tired light hypothese, 光延迟假说, 光子和其他未知介质发生作用导致红移效果, 但是如果是散射这种作用就会导致光的传播方向发生变化,也会导致我们看到的星系形态发生变化, 影响分辨率
2. 也有其他的理论
3. 卧槽, 看起来相互作用的星系测到的红移差别可以那么大,(0.12 到0.2)
4. QSO 在低红移的罕见是为什么?
5. 红移随观测时间发生轻微变化???? (1cm/s/yr 我了个去), 可以实现, 只要设备到位就可以, 精度方面满足,只是体积上有点难
6. CMB 早在1941 年时候就已经被测过,2.3K
7. TCMB 检验成功!!!
8. SN的光变曲线检验同样也成功. 但是quisar 没有看到这类时间延迟的验证. 
9. cosmic chronometer ,test 8, H(z)
10. 星系计数 角度貌似也可以倾向于tired light假说
11. 面亮度 方向的出发点感觉不是很物理,前提假设了星系广度
12. 星等与星系数的关系, 膨胀和static不一样
13. Angular size test, TL 模型拟合的也太好了. 
14. Alcock-Paczynski test???/ 貌似最值得期待
- Beijing Normal University 11/14
CP violation to the success of the Modern standard Cosmology


## 秋哥: 双星系统的统计性质
不同星团中双星的比例对于恒星形成会有影响. 球状星团年龄要更老...
年龄越大星团,双星比例会越少(但是疏散星团中证据不足),所以用了85哥疏散星图作为样本进行研究.
距离越近 双星完备度越低(很自然),需要改进一下.
和星团的年龄,质量关系, 置信度作为一个参考.
质量密度 和双星占比 看起来没有关系(在R_h 内统计), 看到外面> R_h后就看到了明显的反相关~~~

## 浩哥: 
测光,光谱, 天测 三类巡天. 对应类比 位置, 指纹DNA, 动作
GAIA 100 pc. 还有精准度的描述
MW in its evolve history, under the assumption of $\lambda CDM$ , we think the MW must have much more small satellite Gal or substructure remains(遗迹) caused by merge or interactions.    
Method: Slice the sample with PM info. high clustering features would be seen.
Result: member stars selected out. 8 RGB
Analyze: Fit CMD by isochrone curve. Dist distribution fitting so as to get orbital info. 
Con: New stream discovered.

Q:Why 旋转坐标到longitude

张圣文: 评估机器学习方法的 方法
好多公式,字符
可解释性模型 解释, 再把这些认为重要的部分抹去, 抹去之后拿去给模型识别, 比较识别前后的置信度.
期望梯度: Base-line ? 

Tree explainer 
## 9/28周YY师姐: 疏散星团自行数据得到
球状星团: 形成于MW且年老,halo分布
疏散星团: 年轻且引力束缚弱 (10-1000个,分散)是一个面plan分布
疏散星团 整体运动(盘的运动方向)+ 内部随机运动,结合那么多星表,把整体运动部分去掉
研究它的: 收缩膨胀旋转 的速度场, 假设其空间分布为一个连续分布(速度场来自于长期演化不会发生陡增陡降)且互相关,且相关
那么就可以那些异常的运动部分会?

INLA?: 
Latent Gaussian models: 粗略理解为所有参数服从一个高斯分布
最后得到少数的星团有一个旋转和膨胀的模式,并不是很普遍. 
Discussion: 可以理解为一个去噪或者信号增强的过程

## 10/17 璐哥: PSF拟合还原?
结论是用 3-Gaussian 拟合 效果最好. 位置精度 在>21等 时候比DOLPHOT和SEXtractor要好.

Other: 分子云气体的团块边界划分, 引力势能如何计算()考虑到分子云的不规则形状,中心密集区域的引力势能或许比较好估算,外圈的引力势能?  内区不稳定处于逃逸的随机运动状态? 那么那些轮子发条状的结构怎么形成?  

## 10/24 亭哥: 科学的撒双星(依据IMF)
假设其来自于星团瓦解, 影响双星分布的因素: 主序前本征演化 & 受激演化
半质量半径: N-body simulation 来拟合
可以得到 关于恒星 动能-存活概率 分布.
故想要得到长兴

Q:不同的半质量的拟合结果差异来源可能是什么?(G-dwarf 0.1 pc,M-dwarf 0.3pc之类的)

## 10/31 颖颖师姐： CSST无缝光谱目标检测
300+ images，standard box 太大了 ---> 变为 narrow box
Model： Retinanet
re-scale image . different way 
IOU evaluate. threshold ~ 0.5 acceptable .  g,u band show relative worse detection rate.