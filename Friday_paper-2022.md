
- **No.1    [A Nascent Tidal Dwarf Galaxy Forming within the Northern HI Streamer of M82](https://arxiv.org/abs/2112.07052) (update:17/12/21) **

<font color=#4682B8 >Con: </font> Using the DTA(Dragon fly Telephoto Array) and Keck:Ⅰ(LRIS) to observe M82, from its' $H_{\alpha}$,H Ⅰ， molecular hydrogen  distribution induced by  M81, they confirm a ~600 pc-wide region of active SF, indecating that it is likely a tidal dwarf galaxy. (First time Obs in DTA)

<font color=#4682B8 >method:</font> 
- **No.2   [Hidden power of near-infrared data for the study of young clusters: Illustrative case of RCW 38](https://arxiv.org/abs/2203.01064) (update:11/03/22) **

* Con：*Finally, we show that the typical methods for inferring masses from these data may produce substantially unreliable results.we estimate a distance of $1.5 kpc$ and a $K_S -band$ excess fraction larger than 60%.*

Method： CTTSs( Classcal TTauri stars)  in color space, typical methods for inferring masses and distace from NIR data may produce substantially unreliable result. Because Due to theory, env should impact the gaseous component much stonger than dust,  sources fall redward of reddening band have excess with respect to their photosphers, in the past, effect of excess form circumstellar material can be modeled based on observed population( disk models, integrated SEDs from dis+ac, vector with slope). The author think disk-vector and CE breaks the degeneracy between extinction and excess.

Pro of typical & New way: Discrepancy between CC and CMD methord is clearly. Neither estimate is reliable. Couse if  no excess,  their colors are consistent only for $37\%$ out of the 729 sources in the reddening band. When allowing for excess, using set of constrains by excess, color and luminosity, CC and CMD provide consitent estimates of mass and extinction for this source.

- **No.3   [Hot Subdwarf Stars](https://arxiv.org/abs/2203.01064) (update:25/03/22) **

Subdwarf stars, sometimes denoted by 'sd',  refers to a series of stars with anomalous spectra. Cool sd usually with low metallicity( unenriched in elements heavier than helium).  Lower metallicity decreases the opacity of their outer layers and decreases the radiation pressure. 

*Hot subdwarf stars, of spectral types O an B*,also termed "extreme [horizontal-branch](https://en.wikipedia.org/wiki/Horizontal_branch "Horizontal branch")stars". Considered as the late stage of the stars envolvement，if part of mass droped before its cores begins to fuse helium, the star won't climb He-flash 就不会沿着RGB爬升经历氦闪，而是沿着水平支演化，外包层损失露出里面高温核，光度正比于$\sim T^4 * r^{2}$, 神奇的正好沿水平演化，然后沿着白矮星轨迹冷却下降。从得到的光谱中，依据He增丰与否分为 sdO (enriched He) 和 sdB(He deficient)。

关于其形成当下流行的是双星机制解释，对于单个热亚矮星，可能是双白矮星并合（Double WDs merge ---> He enriche, sdO）或者来自其行星或旁边褐矮星的影响.  比如Common-Envelop(CE)情形下，原初sdB是一个巨星，充满了其Roche-lobe，紧跟着伴星吸积其物质最后也充满自身的RL，CE 便形成了（细节并不清楚，当下主要是 $\gamma~and ~\alpha$ 机制，分别代表能量量守恒下角动量方程和角动量守恒下能量方程)。CE最后会因为轨道能量释放而被抛掉露出两个主体，其一为前身为giant 的sdB，另一个为前身为主序的RGB，再继续演化则sdB吸积RGB进入第二个CE阶段，CE之后剩下WD和sdB。 第二种是dynamically stable 不会产生CE，稳定的RLOF(Roche-lobe Overflow)。

然后是其双星存在形式，具体是密近双星还是说有一个中子星或者黑洞伴星，或者是超新星原身，或者说是composite-color binary以及不同形式对应的研究情况。

## 1/4/2022
朝歌：Revisiting the lensed fraction of high redshift quasar.
![[Pasted image 20220401154505.png|center|600]]
被引力透镜作用概率：$\frac{有强引力作用天体}{有强引力作用天体+无强引力天体}$ 
高红移像典型间距0.8 ''

HⅠ 质量函数 HIMF？
**No.4   [Revealing the Galaxy-Halo Connection Through Machine Learning](https://arxiv.org/abs/2204.10332) (update:28/04/22) **
Col: They train a ML method called EBM(Explainable Boosting Machines) to infer how the stellar mass and star formation rate of nearly 6 million simulated galaxies depend on the physical properties of halo mass($M_{vir}$), the peak circular velocity($V_{peak}$), cosmic environment($\rho_1,~T_1~,\Upsilon_{0.1}$) and redshift. Result reveal that $V_{peak},M_{vir}$ have a relative importance(nearly same ratio) of these properties in setting galaxy stellar mass and SFR. 

- BKG: Simulations can capture the physics of cooling, supernova,feedback,radiative feedback and ionization, and the role of dynamics simultaneously while tracking the growth of cosmological structure formation. The simulated galaxy populations result form models reprodece observed stellar population or galaxy type. The complex physics encode by these models and simulations can be diffcult to interpret, and relative contribution of baryonic feedback, dark matter halo formation, and environment in setting galaxy properties remains challenging to disentangle. 
- Details: To value the dependencies of a target quantity on each physical parameter $\theta_i$ are encapsulated by *feature function* of one parameter (e.g., $f^i(\theta_i)$) or *interaction functions* of two parameter(e.g., $f^{ij}(\theta_i,\theta_j)$ . EBM model will give the predicted value of target quantity ,e.g., $\gamma(M_*|\theta)$ is then a sum of the functions $f^i$ . Previous work (e.g. Lovell uses tree-ased learning, Xu train a Random Forest) have applied ML model to infer connections between simulated galaxy properties. This paper study the detailed connection between halo and enviornmental prperties.
- parameter: $\sigma_8$ : rms density fluctuations measured in spheres of radius of R = 8Mpc).
					$\rho_1 \equiv 1+\Delta_1$ :where $\Delta_1$ is the dimensionless matter overdensity measured within 1 Mpc.
					$T_1$ : averaged on 1 Mpc scales.
					$\Upsilon_1 \equiv 1 +M_{max,0.1}/M_{vir}$ where the virial mass $M_{max,0.1}$ means of the most massive neighboring halo within 100 kpc
- Interesting: Full distribution of SFR or stellar mass in simulated galaxy catalogs can be recovered accurately with only $\sim 1-3\%$ outliers. [SFR or stellar mass computed by simulation code CROC]. For galaxy with low spatial resolution or without merger trees to capture formation histories, it's not suitable. So they ameliorate the model exclude $V_{peak}$ ,fit a base CEBM in the same manner as fitting the EBM, then fit an outlier EBM $\delta(y|\theta')$ to those discrepant samples.Between the models, the outlier fraction is only$\sim 2-5\%$
**No.5   [Testing galaxy Formation Models With The GHOSTS Survey: The Color Profile Of M81's Stellar Halo*](http://dx.doi.org/10.1088/0004-637X/766/2/106) (update:09/05/22)**
**Con: They study the properties of the stellar halo out to a projected distance of ~50 kpc from the galactic center. The red giant branch(RGB) of M81's halo is well matched with isochrone of ~10Gyr and metallicities [Fe/H] ~1.2 dex. They do not detect any color gradient within the halo of M81 from 15 kpc out to 50 kpc, which are same as the cosmologically motivated models.**

* BKG. Under the picture of $\Lambda CDM$ , galaxies form hierachically through the accretion of small objects that, due to gravity, merge together to form the larger systems we see today. Predition of this theory, such as the coherent streams, shellsm satellite galaxies, stellar population variations(metallicity variation also expected) within stellar  halos, and other substructure in halo of galaxies.
* Details: Use HST ACS/WFC images in F606w and F814w filter of 19 fields near M81 from GHOSTS survey. Stellar photometry was performed using DOLPHOT. The estimated galaxy density was obtained using the GalaxyCount program. A 10 Gyr old, [Fe/H] - -1.2 dex isochrone from the BaSTI library matches reasonably well the shape of the RGB. By analyzing the colors of the RGBs as a function(CF) fo galactocentric distance, they found no sign of a color gradient in the halo of M81. Comparing with models of galaxy formation(a merger tree is generated using the extended Press-Schechter formalism) shows that mean luminosity-weighted age is rather constant with radius(10.6 Gyr) and weak metallicity gradient. The gradient is consequence of the modeled halo's merger history. The amount of substructure predicted by simulations strongly depend on the accretion history.
* Interesting: 
	Due to the stellar evolutionary models do not contains metallicities lower than -2.2, they assigned a [Fe/H]=-2.2 dex to all the particles with Z lower than that value.
		
	At last in his conclusion,is it reasonable to say that little or no metallicity gradient when many satellites contribute comparably to  the final halo? While metallicity profiles show steeper gradients or present sharp variations when only one or two massive satellites contribute significantly to the halo.I thought that conclusion is based on the assumption that the host halo has enough variation with other halo. Now I know M81 do have a color gradient for $R\leq 20 kpc$ which is not due to the effects of crowding.
**No.6  [The Hot Interstellar Medium](https://arxiv.org/abs/2205.02855) (update:17/05/22)**
They review the current knowledge on the origin and retention of the hot ISM in star-forming and early-type galaxies.A substantial fraction of ISM is heated to temperatures of $\sim 10^6-10^7 K$, no obvious source of energy input to the ISM was systematically involved. A various physical processes(e.g. star formation, AGN feed back, SN) have relative importance varies with respect to different galaxy classes. As star-forming and early-type galaxies can be thought of as the opposite ends of the same evolutionary sequence, which covers the full life cycle of the hot ISM.

**Learned**: The X-ray bubbles in the halo of the MW proves beyond doubt that the hot ISM keeps a record of any past activity. The terminal stages of stellar evolution are characterized by violent, high-energy events that natually lead to X-ray emmision, which including acceration onto a compact object in high and low-mas X-ray binaries, shock-heating and synchrotro radiation from yong supernova remnants, boosted Compton up-scattering of infrared photons by ambient relativistic electrons. Extended X-ray emission with complex morphological features in star-forming galaxies has been viewed since the *Einstein* mission, and the tight spatial correlation with $H_\alpha$ filamenta in optical halo(this coincidence may from the cooling of the hot, fast wind or the interaction with inhomogeneous ISM in the halo).

**No.7  [X-ray detection of a nova in the fireball phase](https://doi.org/10.1038/s41586-022-04635-y) (update:19/05/22)**

Even though UV emission has been detected for a few novae, searches for the X-ray flash, have so far been unsuccessful. What eROSITA saw, according to University of Erlangen-Nuremberg astrophysicist [Ole Koenig](https://www.sternwarte.uni-erlangen.de/~koenig/) and his colleagues, was a phenomenon that astrophysicists had predicted but never seen. It’s called an X-ray ignition flash or, more dramatically, the fireball phase of a nova. The “new and extremely bright” X-ray fireball marked the moment just before the white dwarf star MGAB-V207 blasted most of its outer layers into space at several thousand kilometers per second
**No.8  [Warm ionized gas in the blue compact galaxy Haro 14 viewed by MUSE⋆The diverse ionization mechanisms acting in low-mass starbursts](http://arxiv.org/abs/2206.02754v1) (update:09/06/22)**
line ration map plays an nonnegligible role in dwarf or faint galaxy study.may provide additional information that helps to reconstruct a consistent picture of the physical processes taking place in the galaxy and their impact on the surrounding ISM(万能的结论总结估计是).If so ,how often and for which conditions(装逼的句子).
**No.9  [Momentum and energy injection by a wind-blown bubble into an inhomogeneous interstellar medium](https://arxiv.org/abs/2207.03370) (update:08/07/22)**
The anti-correlation of giant molecular clouds (GMCs) and ionized regions on 100 pc scales and less (e.g. Chevance et al. 2022):

``the ability of a wind-blown bubble (WBB) to do 𝑃𝑑𝑉 work on surrounding gas depends on the interior of the bubble remaining hot.(热气泡对周围气体做功的能力取决于气泡内的温度)``是故星风作用的影响程度又充满了不确定，气泡内外热冷气体分界面上的湍流混合也会影响气泡的冷却速率（离谱的是还能扯上分形结构），就导致气泡出现类似动量守恒的现象，热汽泡冲到冷介质阻尼减速感觉诶。第二个问题是数值模拟下低于分辨率的气泡所做功的量级偏小，对周围气体影响近乎于无。 所以他们不稿模拟了？
``assume that clouds are numerous and continuously distributed in the surrounding medium. We then assume that the clouds that are overrun by the bubble are destroyed within the bubble interior and inject mass into the bubble at a global rate that is proportional to the mass-loss rate of the star, the flow can be treated as a single fluid, which requires that the material liberated from the clouds rapidly merges with the global flow and attains the same density, velocity and temperature.``
- [ ] 假设1 气体云是连续分布的介质
- [ ] 假设2 气体云进入气泡后被摧毁，正比于恒星mass-loss rate 的速率注入到气泡中。
- [ ] 假设3 当单一流体看待，且流体云气在气泡中不再是一个渐变过程了？

其结果便是冷却机制只受气体云和气泡混合程度（恒星的质量损失率影响），而界面处的效应不作考虑，将单独采用相反的假设，模拟非均匀介质中的冷热气体界面冷却效应情况。

**No.10  [The entropy of galaxy spectra: How much information is encoded?](https://arxiv.org/abs/2208.05489) (update:14/08/22)**
This paper aims  to discuss the fundamental limitation of extracting information from galaxy spectra to derive stellar formation histories. A vast literature devoted to the traditional methodology that perform careful analyses to mitigate the inherent degeneracies  among the population properties. They choose the entropy as the base concept, then explore both synthetic models and real galaxy to find a set of spectral regions that encode most of the information.

It seems uninformative when underlying information being too much sometimes

**No.11  [Hidden Depths in the Local Universe: the Stellar Stream Legacy Survey](https://arxiv.org/abs/2104.06071) (update:22/08/22)**

[[Astro-pedia#Stellar Stream Legacy Survey|Stellar Stream Legacy Survey]]
New word : [[Astro-pedia#Galactic cirri|Galactic cirri]]
They use  24 new stellar streams to constrains the galaxy formation theory through  comparison to cosmological galaxy simulation.
These tidal tails and other structures arising from mergers with a characteristic mass ratio less than 1:10 , in which we called major merger remants. 

Conclusion: This survey aims to provide robust distribution of dwarf galaxies' mass , morphlogy and color. In this paper, they mainly introduced the techniques they will used for the entire survey: 1st Methods to distinguish galaxy accretion from major mergers and perturbations to galactic discs.  2nd The repocessing data pattern is competitive with other ultra-deep OB, 3rd  their data well matched to $\lambda~CDM$ simulations.

May be I can use the way they distinguish stellar stream with galatic cirri. 

“constructing a statistically meaningful sample of tidal streams beyond the Local Group has proven a daunting observational challenge, and the full potential for deepening our understanding of galaxy assembly using stellar streams has yet to be realised.” ([Martinez-Delgado 等。, 2021, p. 2](zotero://select/library/items/2GYGIMB7)) ([pdf](zotero://open-pdf/library/items/LJJ5FYXX?page=2&annotation=N94AXK6R))
>the problem we met underlying

**No.12  [Diverse stellar haloes in nearby Milky Way mass disc galaxies](https://doi.org/10.1093/mnras/stw2992) (update:25/08/22)**
[[Author-paper#Benjamin Harmsen | Benjamin Harmsen]]  这是作者.
They want examine the relation between stellar halo population and host
galaxy. Stellar halo masses, metallicities and colors are properties used in this work, they expect to see the halo density profiles and shape can provide important constrains on the merging and accretion history of a galaxy.  Each CMDs uses RGB stars above the 50 per cent completeness, then the density profiles fitted with power-law slope.

When comparing result with models( accrection only and hydrodynamical), for the most part, accrection-only model have a stong mess-metallicity relation, but discrepancy between model to model are neglectable. On the other hand, hydrodynamical model( tempt to more completely capture the  
gas, stellar, and feedback physics of galaxy formation) appear fot the most part to overpredict stellar halo masses.  Such a large discrepancy implies that both the accreted and in situ parts of the halo are over produced in such lower resolution models. Finally, a diversity of stellar halo metallicity gradients was predicted by current high-resolution hydrodynamical simulations.

“it is too early to say if highresolution hydrodynamical simulations naturally reproduce the observed stellar halo metallicities–stellar halo mass correlation.” ([Harmsen 等。, 2017, p. 1509](zotero://select/library/items/CULCL2RN)) ([pdf](zotero://open-pdf/library/items/ENPFBKID?page=19&annotation=PMHMSZGE))
> 说得好，质量方面观测和理论对不上的原因需要进一步确认

**No.13  [Indication of a Local Source of Ultra-High-Energy Cosmic Rays in the Northern Hemisphere](https://arxiv.org/abs/2208.12274) (update:23/09/22)**
This paper is a kind of review and comparing study. 

**No.14  [Fundamentals of Stellar Parameters Estimation through CMD of Star Clusters: Open (NGC 2360) and Globular (NGC 5272)](http://arxiv.org/abs/2209.03019) (update:8/09/22)**

用疏散星团 (NGC 2360) 和球状星团 (NGC 5272)为例 教学，如何利用测光来恒星参数进行分析估计。但是不包括前期的去假源(spurious objects)，误判(error estimations)以及成员星判断(membership determination)。
考虑仪器效应后的星等估计：$M = m_{ins} -\Lambda +ZP+kX+C\times CI$ ,其中的$m_{ins}$ 代表仪器星等，大气消光系数k，空气质量X，颜色修正项C，颜色指数CI，$\Lambda~~and~~ZP$  表示常熟和星等零点。绘CMD，然后再到 isochrones 拟合，年龄或者金属丰度。
![[isochrones-Fundamentals of Stellar Parameters Estimation.png|center|500]]
拟合完之后还需要Chi-squared 检验。
**No.15  [The Pristine Inner Galaxy Survey (PIGS) V: a chemo-dynamical investigation of the early assembly of the Milky Way with the most metal-poor stars in the bulge](http://arxiv.org/abs/2208.13791) (update:9/09/22)**
介绍了一个PIGS项目，利用化学动力学研究MW内部bulge的恒星，发现成员星的金属丰度都类似晕星一样很低(17个低于-2)，其中两个有着2代恒星相似的丰度，说明了球状星团在MW内部瓦解的事实；对于低过-3的认为是早期宇宙贫金属球状星团存在的证据；还要一颗有着极低的$\alpha$ 元素，说明其形成于一个近乎没有污染的区域（只有几个低质量超新星环境），它的轨道又是在银盘，与 [[Astro-pedia#Building Blocks|Building blocks]] 有关可能。

- Introduction part

传统认为MW的最早一批恒星 会被一两次超新星事件所污染，模拟给出小于$Fe/H <2.5$ 的恒星是大爆炸后2-3 Gyr 时候形成的，大部分都是低质量，因此被称为"Building blocks" ，它们会逐渐掉入引力势阱中，成为bulge 束缚部分。而后来吸积的矮星系成员恒星倾向于沉淀在晕中，成为晕星。尽管bulge 的贫星 作为MW演化历史的绝佳研究对象，因为其混在富星、年轻年老星、瓦解的星团、恒星形成区多种复杂环境下，因为搜寻变得极为困难。The Extremely Metal-poor BuLge stars with AAOmega (EMBLA) 利用高分辨率找了63颗，PIGS项目利用的是Canada-France-Hawaii Telescope (CFHT),曾经找到了小于-4的贫星，在找到的这些超贫样本中，发现恒星旋转速度和金属丰度成正比，意味着越贫速度越弥散。从化学丰度角度去看，bulge的大约25%恒星质量来自于瓦解球状星团，其恒星成员化学成分类似于二代恒星组成。 因此他们利用PIGS找到的17个极贫(<-2)候选体,研究其动力学(近心距，径向速度)，以及其大气参数。

- Discussion and conclusion part
- [ ]  如果认为bulge 和 halo 都形成于早期演化出来的的砖瓦(Building blocks) 那么他俩组分(化学丰度气体组成 以及暗物质分布) 应该是类似的，尤其是恒星的化学丰度。
文章认为不同的宇宙学模拟下星系演化的2-3 Gyr 年龄阶段，许多低质量系统($<10^8\rm{M}\odot$) 随机并合形成了源星系，这些砖瓦(低质量系统) 裹挟其内部最老最原始的恒星、气体、暗物质一同完成合并。这些砖块的质量比差距并不是很大使得不同砖块的恒星可以出现在星系任何可能的地方(甚至特别中心区域)。到了演化后期，由吸积捕获的恒星主要分布在外晕或有概率到盘上。因此星系内部主要是是一些年老恒星，而外晕则是不同年龄恒星的混合。

故单独考虑bulge部分，其化学丰度角度是很难区分二者。文章也做了测试$[\alpha/Fe],[Ba/H]$  ,结果都是难以区分(fig 8 &10)。

- [ ] 找到的17个样本没有发现PISNe 的痕迹。
按照星系演化，早期的贫星形成于被PISNe事件污染的气体介质中(对应的超新星150-260 $M\odot$ , 正负电子对湮灭)，问题是IMF实际情况还不是很清楚，第一代恒星就这么大质量有待商榷。

假设是PISNe，那么便会产生很强的 “odd-even effect (ratios of oddZ to even-Z elements” ([Sestito 等。, 2022, p. 14](zotero://select/library/items/DCUFBRJK)) ([pdf](zotero://open-pdf/library/items/SVR9HZEJ?page=14&annotation=ID7HLYIL)), 比如说 Al，Mg。经典的贫星(<-2.5)是来自于小质量贫的核坍缩超新星事件(core-collapse supernovae,CCSNe). 但是样本的 odd-z和PISNe模型对比并没有显著的相关性(fig11)。因此认为样本中未收到PISNe的干扰。

- [ ] 样本中的一些星化学丰度很类似于球状星团的二代恒星，与河外情况一致
文章提到有人认为MW的砖块也可能是早期原始的球状星团被引力瓦解形成。
>“Quantitatively, Schiavon et al. (2017) and Horta et al. (2021b) have estimated that up to ∼ 25% of the stellar mass of the inner halo within 2 kpc from the Galactic centre is made of disrupted GCs, where those clusters were more massive (by 10 − 100) than those observed today.” ([Sestito 等。, 2022, p. 14](zotero://select/library/items/DCUFBRJK)) ([pdf](zotero://open-pdf/library/items/SVR9HZEJ?page=14&annotation=L7STIR9P))

之所以这么认为是因为一些元素丰度相关性属于典型的二代 球状星团恒星特征(CNO 循环主导的核燃烧机制)，[Mg/Fe]≤ 0.1 vs. [Mg/Fe]≤ 0.4 作为区分一二代恒星的判据。显然从fig12里面看到有三个属于二代。

再对比核外情况，文章对比的是M31，Sagittarius, Fornax and Large Magellanic Clouds，他们的 Mg 比银河系的 GCs 略低。 值得注意的是其中一颗恒星P171457的$[Fe/H] = -3.25$ 再一次对理论估计的丰度下限阈值-2.8提出了挑战，同时其径向速度弥散也比一般的GCs要大，说明其极有可能来自被瓦解的GC，说明MW早期以前还形成过更贫的球状星团。

- [ ] 样本中确认2个碳增丰的恒星(s-process and r-process),分别是P182221,P184700
碳增强贫金属（CEMP）恒星在银河晕中的贫金属恒星中其实是常见，前人们认为这类恒星在bulge并不是很常见是因为只找到了几个。按照Eu 和Ba成分将其分为三类：
>“Stars are r-process-enhanced if [Eu/Fe]> 1.0 (CEMP-r), s-process enhanced if [Ba/Fe]> 1.0 and [Ba/Eu]> 0.5 (CEMP-s), mixed if 0.0 <[Ba/Eu]< 0.5 (CEMP-r/s), and with no over abundance of n-capture elements if [Ba/Fe]< 0 (CEMP-no)” ([Sestito 等。, 2022, p. 16](zotero://select/library/items/DCUFBRJK)) ([pdf](zotero://open-pdf/library/items/SVR9HZEJ?page=16&annotation=Y22SKQEP))

他们样本中96个新CEMP 恒星在内晕中，而其中的P183229 and P184700被证实为CEMP-s 类。第三个P182221可能是一个CEMP-s，恒星参数表面他是一个水面支，已经经历过了RGB tip阶段，因此C的含量被消耗了很多
- [ ] P180956远到12kpc的近心轨道，轨道平面在银盘上，和极低的丰度极有可能说明是来自一个极暗矮星系(UFD)，而且只经历了少数几次超新星事件，表面早期演化阶段MW就经历了一次或多次吸积事件。 早期已经有研究表面那些在银道面上的VMPs很可能是源银河的砖块。从模拟角度看这些砖块成员恒星运动方向应该是顺行的，如果是吸积捕获可能会出现逆行，且带有偏心率。未来期待有高分辨率光谱和高精度自行数据兼得。

待补充：目标的演化阶段。如何判断bulge和halo
**No.16  [A Deep View into the Nucleus of the Sagittarius Dwarf Spheroidal Galaxy with MUSE. III. Discrete multi-component population-dynamical models based on the Jeans equations](http://arxiv.org/abs/2209.06229) (update:15/09/22)**

- Aims or Conclusion: Based on Jeans dynamical, they use models to fit the population properties. spatial distributions, and kinematics simultaneously. Their model successfully distinguish the different stellar population in Sgr's nucles via their different spatial . ages, metallicities, and kinematic feature.  
- Background:  [[Astro-pedia#Nuclear star cluster|NSC]] usually have extreme stellar densities($> 10^6M_{\odot}\rm{pc}^3$). The star cluster M54 in Sgr dwarf spheroidal galaxy (dsph) still intact while its host being tidally stripped by the MW, strongly suggest if can't be an old stellar dominated star cluster. The formation scenery emerged form these studies is in agreement with the most widely accepted theory: 
>“in situ star formation from accreted gas” 
>“mergers of globular clusters” ([Kacharov 等。, 2022, p. 2](zotero://select/library/items/Q632QET2)) ([pdf](zotero://open-pdf/library/items/A2HW6SDC?page=2&annotation=ZKI6ADUE))

So they focus on constraining the gravitational potential and explore the interplay of the various distinct M54 stellar populations in the context of NSC formation theories.

- Result and conclusion:
>-i)  a mixture of globular cluster stars (OMP) that belong to at least one massive, but possibly a merger of several globular clusters, due to their large metallicity spread;
>ii) stars formed recently in situ (YMR) that are very centrally concentrated and still have a high degree of rotation;
>iii) stars that belong to the inner Sgr field population (IMR) that have a large age spread, very extended spatial distribution, and a relatively flat velocity dispersion profile.

Their model can explain the majority of observed properties of M54's complex stellar populations simultaneously and self-consistently.
- 评价： 它的工作在于基于jeans 方程 和化学丰度、光度、速度分布得到三个估计参数（恒星种类概率PDF，面亮度PDF（依赖于jeans）以及速度PDF）估计星团恒星属于哪一类的概率是多大从而进行分类、最后能和N-body 模拟对上的认为是最好的，是否适用于其他NSC未知，不过提供了一个解析核球附件NSC历史的途径，没有任何物理内容在里面，很无趣，纯拟合，压根没有任何物理。编故事手段倒是不小

**No.17 [On the validity of the spectroscopic age indicators [Y/Mg], [Y/Al], [Y/Si], [Y/Ca], and [Y/Ti] for giant stars](http://arxiv.org/abs/2208.12891) (update:15/09/22)**
This paper is a kind of review or comparing study. 
BKG: sem

Criticism: First, whether the giant star is the member of open cluster remains question. And the chemical abundance naturally reduce with age, on the other hand, the convection or dynamic activities  results these abundance changed irregularly.

**No.18 [Collapsing Molecular Clouds with Tracer Particles: Part I, What Collapses?](http://arxiv.org/abs/2209.13687) (update:30/09/22)**
我们都知道恒星来自于星云坍缩然后点火聚变，那么在什么样的条件下星云才能完成坍缩，这种初始条件对星系演化有些什么影响
> What are the properties of the gas that becomes a prestellar core? 

**No.19 [Early results from GLASS-JWST VIII: An Extremely Magnified Blue Supergiant Star at Redshift 2.65 in the Abell 2744 Cluster Field](http://arxiv.org/abs/2207.11658) (update:13/10/22)**
Background: 对于一个透镜系统，其临界曲线(critical curves,[[Astro-pedia#Critical curve|critical curve]]) 相接的致密天体源增幅最大，也就是流量越容易被放大观测到。因此足够大且致密的恒星被 galaxy-cluster 透镜超级放大的可能性也是有的。第一个发现被透镜超级放大的恒星(Icarus, $z =1.49$) 由 Kelly et al. (2018). 所发现，其放大率约2000。 Welch et al. (2022) 在 星系团 WHL0137-08 找到一个 $z=6.2$ 的恒星(说实话盲猜争议很大)，但未得到源的尺寸的可信约束。 利用 JWST 6倍于 HST 灵敏度，他们在 Ablell 2744 发现了 $z=2.65$ 的透镜恒星事件，放大率可能高达8000(文章没有当结论写道摘要，看来还是很可疑的)。

-  **意义** Through observations of such extreme-magnification events, we can probe individual stars at cosmological distances, including potentially individual Population III stars. The discoveries of this kind of lensed stars in JWST and HST observations could be used to place constraints on the abundance of primordial black holes as a promising candidate to compact dark matter.

Aims & Conclusion: They aims to find and confirm the transient is a  microlensing event.  考虑到两幅图像的时间延时只有几个小时，排除掉恒星超新星爆发之类的爆炸，从SED 角度(吸积盘不会在$4000 Å$ 出现明显的截断) 排除了 黑洞吸积AGB伴星的可能，也排除了 最终证实确实是一个恒星的微透镜事件，该恒星温度大约 $7000-12000 \rm K$ .

- Method: 利用HST 多色图像(F140,F160. JWST F115, F150, F200) 在该透镜区域图像来证实了该瞬时事件 可信度有 $8\sigma$ , 再测光结果 得到临界曲线位置，期望对称位置也有探测信号，但遗憾没有，从这个角度排除了恒星爆发的可能性。然后是无缝光谱的SED去拟合温度，MW的消光得到8500K而 SMC的消光则得到7700K。而源的尺寸限制方面，event 距离临界曲线0.15 " . 利用 Diego 对微透镜仿真处理， 事件的 duration time 与源尺寸和 速度有个经验关系，根据这个关系估算 源最小 $14 M_{\odot} \times v/500 \rm km s^{-1}$ , 但实际500 km/s 也只是个特征值，实际伤速度可能更高，按2000km/s 算就是 大约56 太阳半径。对应放大率 $\mu \sim 8000$  .

- **问题:** 认证的过程还买有趣的。为什么如果是一个蓝巨星的话另一个像就几乎看不到？是和光路有关系么？SED 拟合用的消光率选择怎么选？源的尺寸和放大率息息相关，而尺寸的判定本身作者也不是很确定，恒星的运动速度这个量怎么测？ 速度差10倍，R就差10倍，放大率就会差3倍多（根号关系）。对质量的依赖反而不是很大。
**No.20 [Thermal Conduction in Clumpy Disks and BLR clouds](10.48550/arXiv.2210.10466) (update:21/10/22)**
**Aims**: Study the dynamics of clumps of clumps individually. To see how much the trajectory of a [[Astro-pedia#Broad line region|BLR]](Broad line region) cloud region will be affected by thermal conduction.
**Background:** •For non-visible active astronomical objects such as black holes and neutron stars, the main phenomenon of engine released by these objects we observe is the accretion process. The main types of black hole accretion flows are classified based on their apparent shapes and the transportation mechanism (mainly 4 classes, 3+advection-dominated accretion flow (ADAF)). Thermal instability can lead to the form of cold dense clumps(confirmed as the BLR). But how these cold clumps formed in such hot, high pressure environment still an active research field.
[![|center|400](https://www.isdc.unige.ch/~ricci/Website/AGN_in_the_X-ray_band_files/X_ray_refl.pptx_1.jpg)]
**Method and Result:**  Assume the clouds behaves like collision-less particles with velocity whose averaged value equals their host medium velocity. The results show that the presence of thermal conduction increases the root of the averaged radial velocity square and this in turn speeds up the process of capturing the clouds through the tidal force. They found out how much the stability of a BLR system can be changed by characteristic parameters (that is, 𝛼 𝑓 and 𝛾) of their hot host medium.

**No.21 [ELVES IV: The Satellite Stellar-to-Halo Mass Relation Beyond the Milky-Way](http://arxiv.org/abs/2210.14233) (update:29/10/22)**
Author: Shany Danieli,1, ∗ Jenny E. Greene,1 Scott Carlsten,1
**Aims:** Using the Milky Way (MW)-like galaxies, breaking the limitation of only using the MW satellite population (impossible to quantify the degree to which the host-to-host scatter impacts the average SHMR).
**Background:** •Dark matter halos embedded within the cosmic web of the large-scale structure are thought to be well-traced by galaxies and gas. So people believe there must be an connection between galaxy and host halo. The relationship between the stellar mass and halo mass, namely, the stellar-to-halo mass relation (SHMR). For galaxies above $M_{halo}\geq 10^{12}M_{\odot}$  have scatter smaller than 0.2 dex, however in $M_{halo}\sim 10^{11}-10^{12} M_{\odot}$ , the SMHR is not well-understood.
**Method and Result:**  ELVES 巡天数据，SExtractor加算法(Bennet et al. (2017) and Greco et al. (2018)) 半自动目标检测识别源。距离用SBF(Surface Brightness Function，Tonry & Schneider 1988) ， stellar masses are obtained by fitting a 2-D sersic model to the DECam or CFHT data, or calculated from the 2MASS. 先观测了local volum,  derived the mass function of stellar halo, 再去Constructing a “Local Volume Subhalo Mass Function”， be attention, subhalo mass means the dark matter . (50 realizations of the subhalos around the 27 ELVES host galaxies)处理数据时候首先是排除掉了影响结果的“大质量卫星星系数量过多的星系群”，利用测出的距离与group距离一致性来判断是否是satellite galaxy。完备性方面，加入 artificial galaxies (按巡天样本的颜色赋予采样星系), 得到星等和面亮度，用他自己之前工作得到该星系被探测到的概率，完备性检验就这些。
R:Moderate slope of α = 2.02+0.10 −0.13, steeper than (α = 1.6 − 1.9; Behroozi et al. 2013; Moster et al. 2013; Garrison-Kimmel et al. 2014) and shallower than (α = 2.6) Garrison-Kimmel et al. (2017)

问题：定距离那里不太确定是否合适，没有读他用SBF定距离paper。

**No.22[Euclid preparation. XXVII. Covariance model validation for the 2-point correlation function of galaxy clusters](http://arxiv.org/abs/2211.12965)(update:6/11/22)**

Galaxy clustering is characterised by a Gaussian covariance, representing the main contribution at large scales, plus a non-Gaussian term arising from nonlinear gravitational instability, galaxy/halo bias and redshift-space distortions, which dominates at small scales.
- assume the cross-correlation between redshift bins to be negligible, as verified from the numerical matrix
- neglect the contribution from higher-order correlation functions, only including the lowest order shot-noise contributions of the non-Gaussian covariance, in addition to the Gaussian part
- do not include the terms that contribute only at zero separation
- do not account for the survey footprint, but consider a simplistic window-function described by a fixed size opening angle.
星系团的的聚集程度可以用一个高斯协方差(大尺度的主要贡献部分)加一个非高斯项目(来自于引力不稳定以及星系的haolo和红移空间的扰动，这部分主导了小尺度部分的贡献)。实际应该是用这样一个简单模型来测试是否适合描述星系巡天的协方差，估算Euclid巡天中来自未知的一些高级项的扰动影响程度。 然后来考虑用这个方法来限制宇宙学参数。
数据分布：an area of 10 313 deg2 and redshift range z = 0 – 2.5
我们是不是可以考虑换一个方程去求解'哈勃常数',因为现在已知的误差确实和观测的精度对比矛盾了。说明这套理论不适合了，我们需要新的表证宇宙演化的方程，或者另一个FRW度规。

**No.23[Shape, alignment, and mass distribution of baryonic and dark-matter halos in one EAGLE simulation](http://arxiv.org/abs/2212.08880)(update:29/12/22)**
**Aims:** Using the cosmological hydrodynamic simulation, the Evolution and Assembly of GaLaxies and their Environments (EAGLE), we aim to provide a comprehensive analysis of the evolution of the morphology of galaxy halos and of their mass distributions with a focus on the snapshot at redshift z = 0.5.

**Methods.** First they build a working spherical with radius, $r_{80cc}$, which the density drops by 80% from the central core(the location of the highest density peak of particles) density. Then they use principal component analysis (PCA) to measure semi-axis and shape parameter, so as to investigate the difference in orientation 、shape of halos. the mass distribution are characterised by a half-mass radius, a concentration parameter and (projected) axis ratios. At last, they analysis dependence of those properties on the redshift.

**Results.** At z = 0.5, the minor axis of the gas halos preferentially aligns with the minor axis of the DM halos. The differences in alignment between the gas and stellar components are larger than those between DM and gas halos.The distribution of the axis ratios of the various components behave similarly, except for gas halos that already form stars and are much more flattened. The gas halos that form stars have larger concentration values than gas halos not forming stars. The value of the concentration parameter of DM and star halos increases continuously from redshift z = 15 to z = 0. Gas halos that do not form any star appear to be light halos. (Result 全部复制粘贴，挑选出的关键词句与摘要所总结的相差不多,考虑用连接词串起来)
**No.24[Low-Surface-Brightness Galaxies are missing in the observed Stellar Mass Function](http://arxiv.org/abs/2212.14539)(update:3/1/23)**
**Aims** They investigate the impact of the surface brightness (SB) limit on the galaxy stellar mass functions (GSMFs).  This study aims at quantifying the fraction of missing LSBGs as a function of the SB detection limit using the Horizon Run 5 (hereafter HR5) simulation.(两句话一个意思)
**Method**  To begin with they derived a galaxy catalog by HR5  simulation. Then analyse:  Stellar Brightness and Mass function,  environment effect(star formation activities) on galaxy, Stellar Brightness and Mass function, Cosmological Surface Brightness Dimming Effect, Distribution of the Surface Brightness of Galaxies and et al.
**Result** The GSMF of HR5 is shaped on the dwarf mass scale before z = 2 and it barely evolves in z ∼ 1−2(which is contradict with consensus). HR5 shows a strong number density evolution with decreasing redshift while observations report relatively weak evolution. The surface-brightness limit of galaxy surveys is one of the important factors fixing the survey completeness at the faint-end of GSMFs



How to tell a paper story?
- [x] 什么样的故事
- [x] 怎么讲的，用了什么数据，方法是什么
- [ ] 意义在哪
- [ ] 问题有哪些
- [ ] **黑话**(术语)和**白话**(高深的概念用简洁的语言来表达)
下次要演练一下呀~
How to change the idea into a paper?
方法论的重要性