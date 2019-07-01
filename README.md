# settle_beijing_2018
2018年成功落户北京名单分析

## 文件说明
* open_script.ipynb : 程序文件
* bjjflu20181015.xlsx : 2018年落户北京名单数据
* 中国统计年鉴_分省年度人口数据.csv : 记录2018年各省人口数据，来源国家统计局
* images文件夹 : 存放分析输出的可视化图

## 结论分析
### 2.1 分数分布
2018年北京市放出了6019个落户名额，根据积分落户的规则，最低分为90.75分，最高分为122.59分。大部分人的分都是相对不高，优秀的人还是很少的。
![image](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/分数分布.png)

### 2.2 年龄分布
截止2019年1月1日，成功落户的人中年龄最大为61岁，最小为34岁，大部分人集中在40-45之间。看来要落户北京，还得奋斗十几二十年。但是呢，根据政策，45岁以下可以加20分，这个可是不少的分数。
![image](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/年龄分布图.png)

### 2.3 教育背景
  过半落户者具有本科学历，硕士也接近3成，博士也相对稀缺。大专以下的只有2.04%。而且考虑到落户者大多80年，甚至70后的，他们读大学的年代，上本科教育可没有现在那么容易。相信未来落户北京，对于整体学历上，还会进一步提高。
  ![image](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/学历水平.png)
  
### 2.4 性别比例
在源数据中，并没有直接揭示落户者的性别信息。但作者还是可以通过一些特殊手段还原中各个人的性别。因此涉及到隐私和信息安全的问题，在此不提及处理方法。落户的人中，63%为男性，男性是落户主力军，从统计学的角度，男女比例具有显著性差异。
  ![image](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/性别比例.png)
  
### 2.5 落户者原户籍
从落户规模看，北方人民最热衷北京，特别是河北人民，差不多900人落户北京，占比总体接近15%，西藏、重庆人民则比较佛系，可能是西藏太远还有重庆的火锅太好吃。
  ![image](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/原户籍分布_bar.png)
  如果从省份的热力图看的话，似乎是离北京越近，落户北京的动力越足。且北方明显比南方更热爱北京。
  ![image](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/原户籍分布_map.png)
上面的说话实际上有点不准确。就好像广东的亿万富豪最多这个说法一样，要知道广东有1亿人口呢。所以需要对比下各省的人口，计算出每10万人中，有多少人落户北京，这样才能公平。
![image](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/各省落户北京概率_bar.png)

### 2.6 创新创业
  创新创业也算积分的。根据不同的等级，可以加1-12分不等。不过大部分人都无此项加分。
  ![image](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/创新创业.png)
  
### 2.7 荣誉表彰
荣誉表彰就更加稀缺了，毕竟能加20分。一般都是那些省级劳动模范、全国道德模范、见义勇为等。
  ![image](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/荣誉表彰.png)
  
### 2.8 就业单位
统计落户人数最多的前25个公司，落户人数最多的单位为北京华为数字有限公司、后面依次为中央电视台、首钢建设、联想等。这些公司体量较大，员工也多，所以落户人数多一点也很正常。更重要的应该是在这些科技公司上，交税和创新方面可能还会有点优势。
![image](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/就业单位.png)

![企业名称词云图](https://github.com/Aplicity/settle_beijing_2018/blob/master/images/单位名称词云图.png)
