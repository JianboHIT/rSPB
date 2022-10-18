# rSPB
**重构单抛物模型(SPB)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在传统的SPB模型中，
我们通常不可避免地需要计算费米狄拉克积分。这是一个数学上的“广义积分”，
它的积分区间包含正无穷，且无法找到原函数，不具备解析形式。
通过一些现代化的计算软件，我们确实可以采用数值方法对其进行积分，
但是这并不方便我们日常使用。
因此我们这里采用一些初等数学表达式来近似替代原先的复杂表达式，
且误差不超过 1.5 % (**Ref**: Zhu, J., Zhang, X., Guo, M. _et al_. 
Restructured single parabolic band model for quick analysis in thermoelectricity. 
*npj Comput. Mater.* **7**, 116 (2021). **DOI**: 
[10.1038/s41524-021-00587-5](https://doi.org/10.1038/s41524-021-00587-5))。
由于计算的便捷性，我们这里开发了一个基于 Excel 的计算模板，
可以直接从实验数据计算出材料的有效质量 ***m\****、
本征迁移率 ***μ***<sub>0</sub>、权重迁移率 ***μ***<sub>w</sub>、
最优掺杂时的功率因子 ***PF***<sub>opt</sub>以及对应的载流子浓度 ***n***<sub>opt</sub>。
同时可以给出完整的塞贝克系数、
载流子迁移率和功率因子随载流子浓度变化的曲线关系，
为材料研究提供参考。

***Key words:***  thermoelectric, single parabolic band(SPB) model, Boltzmann transport equation(BTE)


<img src="How_to_Use.png" width="85%">


## Change log
___[!!!]Sigma version is strongly recommended！___

2021.07.25  Upload Sigma version and tutorial (in Chinese)

2021.07.24  Update Citation (version 2021.7.24)

2021.06.29  Upload version 1.0.0

2021.03.21  Upload demo calculation template tool(Office Excel®)


## Cite this article
Zhu, J., Zhang, X., Guo, M. _et al_. Restructured single parabolic band model for quick analysis in thermoelectricity. _npj Comput Mater_ **7**, 116 (2021). 
(**Open Access**)

[https://doi.org/10.1038/s41524-021-00587-5](https://doi.org/10.1038/s41524-021-00587-5)
