---
permalink: /
title: "个人简介"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

王尚旭，教授，博士生导师，博士学位，全国政协委员，国家973首席科学家。1962年生，北京市人。1984年毕业于武汉地质学院物探系获得学士学位，1990年毕业于华东石油学院获得博士学位。1990年至今在中国石油大学（北京）任教。曾任中石油物探重点实验室主任、中石化油藏地球物理研究中心主任和北京市地球探测与信息技术重点实验室主任，现任油气资源与探测国家重点实验室副主任。

主要从事地震勘探领域的研究，包括岩石物理实验、地震物理模型实验、地震信号分析与反演。作为首席科学家主持了两轮国家973项目研究，总计发表SCI论文61篇，获发明专利5项，获国家科技进步二等奖2项。

科研成果
======
[1] Shangxu Wang, XiangYang Li, Zhongping Qian, Bangrang Di, Jianxin Wei； Physical modelling studies of 3-D P-wave seismic for fracture
detection； Geophysical Journal International；168(2)(2007)

[2] Sanyi Yuan, Shangxu Wang, Nan Tian； Swarm intelligence optimization and its application in geophysical data inversion； Applied Geophysics； 6(2)(2009)；

[3] Shangxu Wang, Xiangyang Li, Bangrang Di, David Booth； Reservoir fluid substitution effects on seismic profile interpretation:A physical modeling experiment； Geophysical Research Letters； 37(10)(2010)

[4] Sanyi Yuan, Shangxu Wang, Guofa Li； Random noise reduction using Bayesian inversion； Journal of Geophysics and Engineering；
9(1)(2012)

[5] Shangxu Wang, JianguoZhao, Zhenhua Li, Jerry M. Harris, Youli Quan； Differential Acoustic Resonance Spectroscopy for the acoustic measurement of small and irregular samples in the low frequency range； Journal of Geophysical Research； 117(13)(2012)

[6] Jianguo Zhao, Genyang Tang,Jixin Deng, Xiaolong Tong, Shangxu Wang； Determination of rock acoustic properties at low frequency:A differential acoustical resonance spectroscopy device and its estimation technique； Geophysical Research Letters； 40(12)(2013)

[7] Sanyi Yuan,Shangxu Wang； Edge-preserving noise reduction based on Bayesian inversion with directional difference constraints； Journal of Geophysics and Engineering； 10(2)(2013)

[8] Sanyi Yuan, Shangxu Wang； Spectral sparse Bayesian learning reflectivity inversion； Geophysical Prospecting； 61(4)（2013）

[9] Xintao Chai, Shangxu Wang, Sanyi Yuan, Jianguo Zhao, Langqiu Sun, Xian Wei； Sparse reflectivity inversion of nonstationary seismic data； Geophysics； 79(3)(2014)

[10] Sanyi Yuan, Shangxu Wang, Chunmei Luo, Yanxiao He； Simultaneous multitrace impedance inversion with transform-domain sparsity promotion； Geophysics； 80(2)（2015）

[11] Sanyi Yuan, Shangxu Wang, Ming Ma, Yongzhen Ji, Li Deng； Sparse Bayesian learning-based time-variant deconvolution； IEEE Transactions on Geoscience and Remote Sensing ； 55(11)(2017)；

科研成就
======
[1] 中国石油和化工自动化行业优秀科技论文奖

[2] 中国高校科学技术奖

[3] 国家科学技术奖

[4] 高等学校科学研究优秀成果奖(科学技术)

[5] 中国石油和化学工业联合会科学技术奖

[6] 中国石油和化学工业联合会科学技术奖
. . .

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
