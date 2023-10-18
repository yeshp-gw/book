###### 关于出差地市的一些总结

[直达广州](#guangzhou)

### 三门峡

[三门峡，这是地方冬天可以观赏美丽的天鹅，本次出差无缘。](https://baike.baidu.com/item/%E4%B8%89%E9%97%A8%E5%B3%A1%E5%B8%82%E5%A4%A9%E9%B9%85%E6%B9%96%E5%9F%8E%E5%B8%82%E6%B9%BF%E5%9C%B0%E5%85%AC%E5%9B%AD/9988908)

格林波分设备三门峡放置于`新大楼（5楼）`和`六峰路局（3楼）`，业务类型`point to point`，现场配置为两光一电，4块PDSD，组网如下：

<img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/6bf52mi7AJedrjn.png" alt="image.png" style="zoom: 200%;" />

<center> <img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/WdPacbUeEpCAhLJ.png" style="zoom: 65%;" /> </center>

总结： 此次出差作为接触波分的第一站，问题全靠常识，这点还得记功劳于多年的读书上。这次出差算是仅仅认识了波分设备，理论知识几乎为0，还有就是一些现场操作问题，可忽略！

### 鹤壁

鹤壁，全国文明城市排名前五的城市，是一座宜居城市，环境优美。

鹤壁组网同三门峡，设备放置于`新大楼（5楼）`和`大梁庄（2楼）`业务模式`point to point`，现场5块PDSD。

<img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/VQuYoqPKfIjlh4B.png" alt="image.png" style="zoom:58%;" />

总结：  此次出差是接触波分设备的第二站，相同的组网已经完全没有难度。这次调测光路仅掌握了show  mode命令，因为当时一路光调不通，经排查为mode 设置错误。

​          期间，还去周口开通U设备

### 洛阳

洛阳，全国唯一非省会城市开通地铁的城市，千朝古都，汉服文化盛行，地铁基本都能看到。

洛阳是波分设备的第三站，组网方式不同于三门峡、鹤壁，是一个环网结构，设备放置于西工、洛南、和谷水，配置4光3电、4光4电。谷水机房远离市区并且安全级别较高，进入机房需要人打申请。组网如下：

<center> <img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/56Dz3ecgmiAO7GZ.png"style="zoom: 57%;" /> </center>    

<center> <img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/p6IGctdeRKCJhBQ.png"style="zoom: 58%;" /> </center>

<img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/8fg7cjFDiAmk9vE.png" width="90%"/> 

  ![](https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/55.jpg)

<center><img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/WdPacbUeEpCAhLJ.png" style="zoom: 67%;" /></center> 

总结：接触波分设备的第三站，这次是波分知识和人际关系的爆破点，波分知识增长不少，人际关系开始紧张。

串波、环网、标签、上ODF架等，都是全新的知识。但是基本的命令还是涉及的不够多。大局了解的比较多。

了解最多的还是上ODF架的一些东西，打印标签的一些格式：`机柜号+框+槽位+板卡名称+接口名称-TX/RX  电框`，

`框+槽位+板卡名称+接口名称-TX/RX  光框`，没有一定的东西，好坏参半不必太当真。

### 庆阳

庆阳，莫酸奶真的好喝，人口排名居甘肃省前列。

接触波分设备测试的头一回，坐标庆阳电信，负责人李小娟，简单的点对点10GE业务测试，测试项目主要是传输设备的稳定性和设备性能，顺带测了op倒换和损耗。

<center><img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/%E5%BA%86%E9%98%B3.jpg" style="zoom:39%;" /></center>

<div align='center' ><font size=3>现场图</font></div>

{% youtube %}

https://youtube.com/shorts/_nw_C2xk4dk

{% endyoutube %}

总结：  就学会了一个上网管 、倒换阈值的设置、延迟时间设置、打环命令、计算光路提升了下，学会了写路由等。其他再补充。

### <span id="guangzhou"></span>广州

试点系统图

![](https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/%E5%B9%BF%E5%B7%9E.png)

试点连纤图

<img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/%E5%B9%BF%E5%B7%9E%E8%AF%95%E7%82%B9.png" style="zoom:80%;" />

需要仪器

| <font color="red">光功率计</font> | <font color="red">58仪表100G</font> | <font color="red">光谱分析仪</font> |  <font color="red">光衰减器</font>  |
| :-------------------------------: | :---------------------------------: | :---------------------------------: | :---------------------------------: |
|           **尾纤20根**            |           **光衰3dBmx2**            |       **理线架、标签32个**、        | <font color="red">**分光器**</font> |

发货清单

<img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/%E8%AE%BE%E5%A4%87%E6%B8%85%E5%8D%95.png" style="zoom:95%;" />

模块发光指标

![](https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/%E5%8F%91%E5%85%89%E6%8C%87%E6%A0%87.png)

<img src="https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/202310131352466.png" style="zoom: 50%;" />

测试项目

- 背靠背OSNR容限

![](https://gitbook-pic-1301999062.cos.ap-beijing.myqcloud.com/202310130900931.png)

光可调衰减器B：光缆损耗，3dB/10KM

光可调衰减器A：设置大于噪声源

ASE：设置一个值

光谱仪：记录S+N值、N值等，最后通过公式计算得出OSNR值，查看FEC

业务分析仪：打流，模拟业务
