[[2023-06-19]]
作者：acalephs  
链接：https://www.zhihu.com/question/31683770/answer/52980207  
来源：知乎  
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。  
  

让我们从最基本的开始……以下如果没有特别说明主角都是电子。

首先从[量子力学](https://www.zhihu.com/search?q=%E9%87%8F%E5%AD%90%E5%8A%9B%E5%AD%A6&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)的基本假设——不连续性可以推出原子外电子的在条件一定的情况下只能取到某些特定的能量，这就是**[能级](https://www.zhihu.com/search?q=%E8%83%BD%E7%BA%A7&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)**：

![](https://picx.zhimg.com/80/9d4af36a610edc44b3ea9e5d73c4a514_720w.webp?source=1940ef5c)

（大家好，我是氢原子的[电子能级](https://www.zhihu.com/search?q=%E7%94%B5%E5%AD%90%E8%83%BD%E7%BA%A7&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)）

当体系中有很多个原子的时候，由于原子间的相互作用，原子的能级会发生移动。原本相同的一条能级变成了一组差别很小的能级，这就是**能带**，也就是**允带**。由于能带内不同能级的能量差别非常小，所以很多时候在能带内可以忽略间隔，认为能量是连续的。

![](https://picx.zhimg.com/80/266f0bd87745c9b8708a28109558c5c1_720w.webp?source=1940ef5c)

（在[微扰](https://www.zhihu.com/search?q=%E5%BE%AE%E6%89%B0&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)影响下，左侧的能级扩展成了右侧的能带）

由于能带是由能级扩展而来，能带和能级一样，相互之间存在没有能级的间隔，这个间隔就是**禁带**，电子无法取到禁带中的能量。

当原子处于基态的时候，它的所有电子从最低能级开始依次向上填充。对于半导体，电子刚好填充到某一个能带满了，下一个能带全空。这些被填满的能带称为**满带**，满带中能量最高的一条称为**价带**。

由于电流的产生需要载流子发生[定向运动](https://www.zhihu.com/search?q=%E5%AE%9A%E5%90%91%E8%BF%90%E5%8A%A8&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)，而价带中电子已经占据了所有可能的能级，绝大多数电子相邻位置上的态都已经被占据了，无法移动，所以**价带中的电子可以认为是不导电的**。

对于半导体，能量最高的一个价带，到能量更高的下一个能带之间有一个禁带，但是这个禁带的宽度（能量）不是很大，所以有一些电子有机会跃迁到下一个能带。由于这个能带几乎是空的，所以电子们跃迁到这个能带之后就可以自由地奔跑，这个能带就是**导带**。

（另外对于绝缘体，这个[禁带宽度](https://www.zhihu.com/search?q=%E7%A6%81%E5%B8%A6%E5%AE%BD%E5%BA%A6&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)太大，基本上不可能有电子跃迁过去。对于金属，根本没有禁带，导带和价带直接重合了，既然最高的能带本身就不满那不需要跃迁就可以导电了。）

![](https://picx.zhimg.com/80/f56ad86d93d990563eac4535d1acdc8d_720w.webp?source=1940ef5c)

需要注意的是以上的能带图、导带、价带的说法都是以电子为基准的（能级越高电子能量越大），如果是针对空穴，就是在导带中不导电（导带中全是空穴……），在价带中能导电。所以我们把（半导体内），导带中的电子和价带内的空穴合称**载流子**。

-------------以下扩展-----------------

为了方便描述电子在能带中的分布，我们引入了**[费米能级](https://www.zhihu.com/search?q=%E8%B4%B9%E7%B1%B3%E8%83%BD%E7%BA%A7&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)**。

费米能级的含义是，当半导体处于[绝对零度](https://www.zhihu.com/search?q=%E7%BB%9D%E5%AF%B9%E9%9B%B6%E5%BA%A6&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)的时候，费米能级以下的所有能级都被电子填满，费米能级以上所有的能级都是空的。当温度高于绝对零度的时候，可以通过费米能级和温度来计算电子的**[费米-狄拉克分布](https://www.zhihu.com/search?q=%E8%B4%B9%E7%B1%B3-%E7%8B%84%E6%8B%89%E5%85%8B%E5%88%86%E5%B8%83&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)。**所以费米能级能够完全描述平衡载流子的分布情况。

纯净的半导体（**[本征半导体](https://www.zhihu.com/search?q=%E6%9C%AC%E5%BE%81%E5%8D%8A%E5%AF%BC%E4%BD%93&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)**）的导电能力是很差的，因为需要很高的温度才能让足够多的载流子跃迁到导带。一般使用半导体的时候都会进行掺杂，通过掺入杂质来引入新的能级。

对于硅来说，掺杂硼可以在禁带中里价带很近的位置上引入一组全空的能级，价带电子可以很容易地跃迁到这个能级上，[电子跃迁](https://www.zhihu.com/search?q=%E7%94%B5%E5%AD%90%E8%B7%83%E8%BF%81&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)之后在价带留下的空穴就可以导电了，这就是**P[型半导体](https://www.zhihu.com/search?q=%E5%9E%8B%E5%8D%8A%E5%AF%BC%E4%BD%93&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)**。

掺杂磷，可以在禁带中里导带很近的位置上引入一组全满的能级，这个能级上的电子可以很容易地跃迁到导带上，成为导带[电子导电](https://www.zhihu.com/search?q=%E7%94%B5%E5%AD%90%E5%AF%BC%E7%94%B5&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)，这就是**[N型半导体](https://www.zhihu.com/search?q=N%E5%9E%8B%E5%8D%8A%E5%AF%BC%E4%BD%93&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A52980207%7D)**。

![](https://pica.zhimg.com/80/4d5192091de43f6601a91662a0f6ef9d_720w.webp?source=1940ef5c)

跃迁前

![](https://picx.zhimg.com/80/9cfb4f120aea450b9973be039e383ef5_720w.webp?source=1940ef5c)

跃迁后