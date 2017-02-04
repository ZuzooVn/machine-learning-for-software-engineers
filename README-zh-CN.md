# 自上而下的学习路线: 软件工程师的机器学习


灵感来源于 [谷歌面试学习手册](https://github.com/jwasham/google-interview-university/blob/master/README-cn.md)


> * 原文地址：[Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers)
* 原文作者：[ZuzooVn(Nam Vu)](https://github.com/ZuzooVn)
* 翻译：[lsvih](https://github.com/lsvih)


## 这是？

这是本人为期数月的学习计划。我正要从一名移动端软件开发者(自学，无计科文凭)转型成为一名机器学习工程师。

我的主要目标是找到一种以实践为主的学习方法，并为初学者抽象掉大多数的数学概念。
这种学习方法是非传统的，因为它是专门为软件工程师所设计的自上而下、以结果为导向的学习方法。

如果您想让它更好的话，随时欢迎您的贡献。

---

## 目录

- [这是？](#这是)
- [为何要用到它？](#为何要用到它)
- [如何使用它？](#如何使用它)
- [Follow me](#follow-me)
- [别认为自己不够聪明](#别认为自己不够聪明)
- [关于视频资源](#关于视频资源)
- [预备知识](#预备知识)
- [每日计划](#每日计划)
- [动机](#动机)
- [机器学习概论](#机器学习概论)
- [掌握机器学习](#掌握机器学习)
- [有趣的机器学习](#有趣的机器学习)
- [机器学习简介](#机器学习简介)
- [一本深入，非技术的机器学习指南](#一本深入-非技术的机器学习指南)
- [故事与经验](#故事与经验)
- [机器学习算法](#机器学习算法)
- [入门书籍](#入门书籍)
- [实用书籍](#实用书籍)
- [Kaggle知识竞赛](#kaggle知识竞赛)
- [系列视频](#系列视频)
- [MOOC](#mooc)
- [资源](#资源)
- [成为一名开源贡献者](#成为一名开源贡献者)
- [游戏](#游戏)
- [播客](#播客)
- [社区](#社区)
- [面试问题](#面试问题)
- [我崇拜的公司](#我崇拜的公司)

---

## 为何要用到它？

我会为了我未来的工作————机器学习工程师 遵循这份计划。自2011年以来，我一直进行着移动端应用的开发(包括安卓、iOS与黑莓)。我有软件工程的文凭，但没有计算机科学的文凭。我仅仅在大学的时候学习过一点基础科学，包括微积分、线性代数、离散数学、概率论与统计。
我认真思考过我在机器学习方面的兴趣:
- [我能在没有计科硕士、博士文凭的情况下找到一份关于机器学习的工作吗？](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD)
    - 你当然可以，但是我想进入这个领域则无比艰难。
- [我是一名软件工程师，我自学了机器学习，我如何在没有相关经验的情况下找到一份关于机器学习的工作？](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work)
    - 我正在为我的团队招聘机器学习专家，但你的MOOC并不会给你带来工作机会。事实上，大多数机器学习方向的硕士也并不会得到工作机会，因为他们（与大多数上过MOOC的人一样）并没有深入地去理解。他们都没法帮助我的团队解决问题。
- [找一份机器学习相关的工作需要掌握怎样的技能？](http://programmers.stackexchange.com/questions/79476/what-skills-are-needed-for-machine-learning-jobs)
    - 首先，你得有正儿八经的计科或数学专业背景。ML是一个比较先进的课题，大多数的教材都会直接默认你有以上背景。其次，机器学习是一个集成了许多子专业的奇技淫巧的课题，你甚至会想看看MS的机器学习课程，去看看他们的授课、课程和教材。
    - 统计，假设，分布式计算，然后继续统计。

我深陷困境。

据我所知, [机器学习有两个方向](http://machinelearningmastery.com/programmers-can-get-into-machine-learning/)：
- 实用机器学习： 这个方向主要是查询数据库、数据清洗、写脚本来转化数据，把算法和库结合起来再加上一些定制化的代码，从数据中挤出一些准确的答案来证明一些困难且模糊不清的问题。实际上它非常混乱。
- 理论机器学习： 这个方向主要是关于数学、抽象、理想状况、极限条件、典型例子以及一切可能的特征。这个方向十分的干净、整洁，远离混乱的现实。

我认为对于以实践为主的人来说，做好的方法就是 [“练习--学习--练习”](http://machinelearningmastery.com/machine-learning-for-programmers/#comment-358985)，这意味着每个学生一开始就能参与一些现有项目与一些问题，并练习（解决）它们以熟悉传统的方法是怎么做的。在有了一些简单的练习经验之后，他们就可以开始钻进书里去学习理论知识。这些理论知识将帮助他们在将来进行更进一步的训练，充实他们解决实际问题的工具箱。学习理论知识还会加深他们对那些简单练习的理解，帮助他们更快地获得进阶的经验。

这是一个很长的计划，它花去了我一年的时间。如果你已经对它有所了解了，它将会让你省去很多时间。

## 如何使用它？
以下的内容全部是概要，你需要从上往下来解决这些项目。

我使用的是Github独特的flavored markdown的任务列表来检查我计划的进展。

- [x] 创建一个新的分支，然后你可以这样来标出你已经完成的项目，只需要在框中填写一个x即可：[x]

[了解更多有关 Github-flavored markdown的知识](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

## Follow me
我是一名非常非常想去美国工作的越南软件工程师。

我在这份计划中花多少时间？在每天的艰辛工作完成后，每晚花4小时。

我已经在实现梦想的旅途中了。

- Twitter: [@Nam Vu](https://twitter.com/zuzoovn)

| ![Nam Vu - Top-down learning path: machine learning for software engineers](http://sv1.upsieutoc.com/2016/10/08/331f241c8da44d0c43e9324d55440db6.md.jpg)|
|:---:|
| USA as heck |

## 别认为自己不够聪明
当我打开书本，发现他们告诉我多元微积分、统计与推理、线性代数是学习机器学习的先决条件的时候，我非常沮丧。因为我不知道从哪儿开始…

- [我数学不好怎么办](http://machinelearningmastery.com/what-if-im-not-good-at-mathematics/)
- [没有数学专业背景而理解机器学习算法的5种技巧](http://machinelearningmastery.com/techniques-to-understand-machine-learning-algorithms-without-the-background-in-mathematics/)
- [我是如何学习机器学习的？](https://www.quora.com/Machine-Learning/How-do-I-learn-machine-learning-1)

## 关于视频资源

部分视频只有在Coursera、EdX的课程注册了才能观看。虽然它们是免费的，但有些时间段这些课程并不开放，你可能需要等上一段时间(可能是好几个月)。我将会加上更多的公开的视频源来代替这些在线课程的视频。我很喜欢大学的讲座。

## 预备知识

这个小章节是一些在每日计划开始前我想去了解的一些预备知识与一些有趣的信息。

- [ ] [Data Analytics，Data Analysis，数据挖掘，数据科学，机器学习，大数据的区别是什么？](https://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)
- [ ] [学习如何去学习](https://www.coursera.org/learn/learning-how-to-learn)
- [ ] [不要斩断锁链](http://lifehacker.com/281626/jerry-seinfelds-productivity-secret)
- [ ] [如何自学](https://metacademy.org/roadmaps/rgrosse/learn_on_your_own)

## 每日计划

每个主题都不需要用一整天来完全理解它们，你可以每天完成它们中的多个。

每天我都会从下面的列表中选一个出来，一遍又一遍的读，做笔记，练习，用Python或R语言实现它。

# 动机
- [ ] [梦](https://www.youtube.com/watch?v=g-jwWYX7Jlo)

## 机器学习概论
- [ ] [形象的机器学习简介](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [ ] [一份温柔的机器学习指南](https://blog.monkeylearn.com/a-gentle-guide-to-machine-learning/)
- [ ] [为开发者准备的机器学习简介](http://blog.algorithmia.com/introduction-machine-learning-developers/)
- [ ] [菜鸟的机器学习基础](https://www.analyticsvidhya.com/blog/2015/06/machine-learning-basics/)
- [ ] [你如何向非计算机专业的人来解释机器学习与数据挖掘？](https://www.quora.com/How-do-you-explain-Machine-Learning-and-Data-Mining-to-non-Computer-Science-people)
- [ ] [在罩子下的机器学习，博文简单明了地介绍了机器学习的原理](https://georgemdallas.wordpress.com/2013/06/11/big-data-data-mining-and-machine-learning-under-the-hood/)
- [ ] [机器学习是什么？它是如何工作的呢？](https://www.youtube.com/watch?v=elojMnjn4kk&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=1)
- [ ] [深度学习——一份非技术性的简介](http://www.slideshare.net/AlfredPong1/deep-learning-a-nontechnical-introduction-69385936)

## 掌握机器学习
- [ ] [掌握机器学习的方法](http://machinelearningmastery.com/machine-learning-mastery-method/)
- [ ] [程序员的机器学习](http://machinelearningmastery.com/machine-learning-for-programmers/)
- [ ] [掌握并运用机器学习](http://machinelearningmastery.com/start-here/)
- [ ] [Python机器学习小课程](http://machinelearningmastery.com/python-machine-learning-mini-course/)
- [ ] [机器学习算法小课程](http://machinelearningmastery.com/machine-learning-algorithms-mini-course/)

## 有趣的机器学习
- [ ] [机器学习真有趣！](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471#.37ue6caww)
- [ ] [Part 2: 使用机器学习来创造超级马里奥的关卡](https://medium.com/@ageitgey/machine-learning-is-fun-part-2-a26a10b68df3#.kh7qgvp1b)
- [ ] [Part 3: 深度学习与卷积神经网络](https://medium.com/@ageitgey/machine-learning-is-fun-part-3-deep-learning-and-convolutional-neural-networks-f40359318721#.44rhxy637)
- [ ] [Part 4: 现代人脸识别与深度学习](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78#.3rwmq0ddc)
- [ ] [Part 5: 翻译与深度学习和序列的魔力](https://medium.com/@ageitgey/machine-learning-is-fun-part-5-language-translation-with-deep-learning-and-the-magic-of-sequences-2ace0acca0aa#.wyfthap4c)
- [ ] [Part 6: 如何使用深度学习进行语音识别](https://medium.com/@ageitgey/machine-learning-is-fun-part-6-how-to-do-speech-recognition-with-deep-learning-28293c162f7a#.lhr1nnpcy)

## [机器学习简介](https://triskell.github.io/2016/11/15/Inky-Machine-Learning.html)(用手指沾上墨水来书写机器学习简介)
- [ ] [Part 1 : 什么是机器学习？](https://triskell.github.io/2016/10/23/What-is-Machine-Learning.html)
- [ ] [Part 2 : 监督学习与非监督学习](https://triskell.github.io/2016/11/13/Supervised-Learning-and-Unsupervised-Learning.html)

## 一本深入、非技术性的机器学习指南
- [ ] [概述，目标，学习类型和算法](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide/)
- [ ] [数据的选择，准备与建模](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-2/)
- [ ] [模型的评估，验证，复杂性与改进](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-3/)
- [ ] [模型性能与误差分析](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-4/)
- [ ] [无监督学习，相关领域与实践中的机器学习](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-5/)

## 故事与经验
- [ ] [一周的机器学习](https://medium.com/learning-new-stuff/machine-learning-in-a-week-a0da25d59850#.tk6ft2kcg)
- [ ] [一年的机器学习](https://medium.com/learning-new-stuff/machine-learning-in-a-year-cdb0b0ebd29c#.hhcb9fxk1)
- [ ] [我是如何在3天内写出我的第一个机器学习程序的](http://blog.adnansiddiqi.me/how-i-wrote-my-first-machine-learning-program-in-3-days/)
- [ ] [学习路径：你成为机器学习专家的导师](https://www.analyticsvidhya.com/learning-path-learn-machine-learning/)
- [ ] [不是PhD你也可以成为机器学习的摇滚明星](https://backchannel.com/you-too-can-become-a-machine-learning-rock-star-no-phd-necessary-107a1624d96b#.g9p16ldp7)
- [ ] 如何6个月成为一名数据科学家：一名黑客的职业规划
    - [视频](https://www.youtube.com/watch?v=rIofV14c0tc)
    - [幻灯片](http://www.slideshare.net/TetianaIvanova2/how-to-become-a-data-scientist-in-6-months)
- [ ] [5个你成为机器学习工程师必须要掌握的技能](http://blog.udacity.com/2016/04/5-skills-you-need-to-become-a-machine-learning-engineer.html)
- [ ] [你是一个自学成才的机器学习工程师吗？你是怎么做的？花了多长时间？](https://www.quora.com/Are-you-a-self-taught-machine-learning-engineer-If-yes-how-did-you-do-it-how-long-did-it-take-you)
- [ ] [一个人如何成为一名优秀的机器学习工程师？](https://www.quora.com/How-can-one-become-a-good-machine-learning-engineer)
- [ ] [一个专注于机器学习的学术假期](http://karlrosaen.com/ml/)

## 机器学习算法
- [ ] [用“士兵”来表示10种机器学习算法](https://www.analyticsvidhya.com/blog/2015/12/10-machine-learning-algorithms-explained-army-soldier/)
- [ ] [Top10的数据挖掘算法](https://rayli.net/blog/data/top-10-data-mining-algorithms-in-plain-english/)
- [ ] [介绍10种机器学习的术语](http://blog.aylien.com/10-machine-learning-terms-explained-in-simple/)
- [ ] [机器学习算法之旅](http://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/)
- [ ] [机器学习工程师需要知道的10种算法](https://gab41.lab41.org/the-10-algorithms-machine-learning-engineers-need-to-know-f4bb63f5b2fa#.ofc7t2965)
- [ ] [比较监督学习算法](http://www.dataschool.io/comparing-supervised-learning-algorithms/)
- [收集的最简化、可执行的机器学习算法](https://github.com/rushter/MLAlgorithms)

## 入门书籍
- [ ] [Data Smart: Using Data Science to Transform Information into Insight 1st Edition](https://www.amazon.com/Data-Smart-Science-Transform-Information/dp/111866146X)
- [ ] [Data Science for Business: What you need to know about data mining and data­ analytic-thinking](https://www.amazon.com/Data-Science-Business-Data-Analytic-Thinking/dp/1449361323/)
- [ ] [Predictive Analytics: The Power to Predict Who Will Click, Buy, Lie, or Die](https://www.amazon.com/Predictive-Analytics-Power-Predict-Click/dp/1118356853)

## 实用书籍
- [ ] [Machine Learning for Hackers](https://www.amazon.com/Machine-Learning-Hackers-Drew-Conway/dp/1449303714)
    - [GitHub repository(R)](https://github.com/johnmyleswhite/ML_for_Hackers)
    - [GitHub repository(Python)](https://github.com/carljv/Will_it_Python)
- [ ] [Python Machine Learning](https://www.amazon.com/Python-Machine-Learning-Sebastian-Raschka-ebook/dp/B00YSILNL0)
    - [GitHub repository](https://github.com/rasbt/python-machine-learning-book)
- [ ] [Programming Collective Intelligence: Building Smart Web 2.0 Applications](https://www.amazon.com/Programming-Collective-Intelligence-Building-Applications-ebook/dp/B00F8QDZWG)
- [ ] [Machine Learning: An Algorithmic Perspective, Second Edition](https://www.amazon.com/Machine-Learning-Algorithmic-Perspective-Recognition/dp/1466583282)
    - [GitHub repository](https://github.com/alexsosn/MarslandMLAlgo)
    - [Resource repository](http://seat.massey.ac.nz/personal/s.r.marsland/MLbook.html)
- [ ] [Introduction to Machine Learning with Python: A Guide for Data Scientists](http://shop.oreilly.com/product/0636920030515.do)
    - [GitHub repository](https://github.com/amueller/introduction_to_ml_with_python)
- [ ] [Data Mining: Practical Machine Learning Tools and Techniques, Third Edition](https://www.amazon.com/Data-Mining-Practical-Techniques-Management/dp/0123748569)
    - Teaching material
        - [Slides for Chapters 1-5 (zip)](http://www.cs.waikato.ac.nz/ml/weka/Slides3rdEd_Ch1-5.zip)
        - [Slides for Chapters 6-8 (zip)](http://www.cs.waikato.ac.nz/ml/weka/Slides3rdEd_Ch6-8.zip)
- [ ] [Machine Learning in Action](https://www.amazon.com/Machine-Learning-Action-Peter-Harrington/dp/1617290181/)
    - [GitHub repository](https://github.com/pbharrin/machinelearninginaction)
- [ ] [Reactive Machine Learning Systems(MEAP)](https://www.manning.com/books/reactive-machine-learning-systems)
    - [GitHub repository](https://github.com/jeffreyksmithjr/reactive-machine-learning-systems)
- [ ] [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)
    - [GitHub repository(R)](http://www-bcf.usc.edu/~gareth/ISL/code.html)
    - [GitHub repository(Python)](https://github.com/JWarmenhoven/ISLR-python)
    - [视频](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/)
- [ ] [Building Machine Learning Systems with Python](https://www.packtpub.com/big-data-and-business-intelligence/building-machine-learning-systems-python)
    - [GitHub repository](https://github.com/luispedro/BuildingMachineLearningSystemsWithPython)
- [ ] [Learning scikit-learn: Machine Learning in Python](https://www.packtpub.com/big-data-and-business-intelligence/learning-scikit-learn-machine-learning-python)
    - [GitHub repository](https://github.com/gmonce/scikit-learn-book)
- [ ] [Probabilistic Programming & Bayesian Methods for Hackers](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
- [ ] [Probabilistic Graphical Models: Principles and Techniques](https://www.amazon.com/Probabilistic-Graphical-Models-Principles-Computation/dp/0262013193)
- [ ] [Machine Learning: Hands-On for Developers and Technical Professionals](https://www.amazon.com/Machine-Learning-Hands-Developers-Professionals/dp/1118889061)
    - [Machine Learning Hands-On for Developers and Technical Professionals review](https://blogs.msdn.microsoft.com/querysimon/2015/01/01/book-review-machine-learning-hands-on-for-developers-and-technical-professionals/)
    - [GitHub repository](https://github.com/jasebell/mlbook)
- [ ] [Learning from Data](https://www.amazon.com/Learning-Data-Yaser-S-Abu-Mostafa/dp/1600490069)
    - [在线教程](https://work.caltech.edu/telecourse.html)
- [ ] [Reinforcement Learning: An Introduction (2nd Edition)](https://webdocs.cs.ualberta.ca/~sutton/book/the-book-2nd.html)
    - [GitHub repository](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)
- [ ] [使用TensorFlow(MEAP)进行机器学习](https://www.manning.com/books/machine-learning-with-tensorflow)
    - [GitHub repository](https://github.com/BinRoot/TensorFlow-Book)

## Kaggle知识竞赛
- [ ] [Kaggle竞赛：怎么样，在哪里开始？](https://www.analyticsvidhya.com/blog/2015/06/start-journey-kaggle/)
- [ ] [一个初学者如何用一个小项目在机器学习入门并在Kaggle竞争](http://machinelearningmastery.com/how-a-beginner-used-small-projects-to-get-started-in-machine-learning-and-compete-on-kaggle)
- [ ] [如何竞争Kaggle的Master](http://machinelearningmastery.com/master-kaggle-by-competing-consistently/)

## 系列视频
- [ ] [Machine Learning for Hackers](https://www.youtube.com/playlist?list=PL2-dafEMk2A4ut2pyv0fSIXqOzXtBGkLj)
- [ ] [Fresh Machine Learning](https://www.youtube.com/playlist?list=PL2-dafEMk2A6Kc7pV6gHH-apBFxwFjKeY)
- [ ] [Machine Learning Recipes with Josh Gordon](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
- [ ] [Everything You Need to know about Machine Learning in 30 Minutes or Less](https://vimeo.com/43547079)
- [ ] [A Friendly Introduction to Machine Learning](https://www.youtube.com/watch?v=IpGxLWOIZy4)
- [ ] [Nuts and Bolts of Applying Deep Learning - Andrew Ng](https://www.youtube.com/watch?v=F1ka6a13S9I)
- [ ] BigML Webinar
    - [视频](https://www.youtube.com/watch?list=PL1bKyu9GtNYHcjGa6ulrvRVcm1lAB8he3&v=W62ehrnOVqo)
    - [资源](https://bigml.com/releases)
- [ ] [mathematicalmonk's Machine Learning tutorials](https://www.youtube.com/playlist?list=PLD0F06AA0D2E8FFBA)
- [ ] [Machine learning in Python with scikit-learn](https://www.youtube.com/playlist?list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A)
    - [GitHub repository](https://github.com/justmarkham/scikit-learn-videos)
    - [博客](http://blog.kaggle.com/author/kevin-markham/)
- [ ] [My playlist – Top YouTube Videos on Machine Learning, Neural Network & Deep Learning](https://www.analyticsvidhya.com/blog/2015/07/top-youtube-videos-machine-learning-neural-network-deep-learning/)
- [ ] [16 New Must Watch Tutorials, Courses on Machine Learning](https://www.analyticsvidhya.com/blog/2016/10/16-new-must-watch-tutorials-courses-on-machine-learning/)
- [ ] [DeepLearning.TV](https://www.youtube.com/channel/UC9OeZkIwhzfv-_Cb7fCikLQ)
- [ ] [Learning To See](https://www.youtube.com/playlist?list=PLiaHhY2iBX9ihLasvE8BKnS2Xg8AhY6iV)
- [ ] [Neural networks class - Université de Sherbrooke](https://www.youtube.com/playlist?list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH)
- [ ] [2016年的21个深度学习视频课程](https://www.analyticsvidhya.com/blog/2016/12/21-deep-learning-videos-tutorials-courses-on-youtube-from-2016/)
- [ ] [2016年的30个顶级的机器学习与人工智能视频教程 Top Videos, Tutorials & Courses on Machine Learning & Artificial Intelligence from 2016](https://www.analyticsvidhya.com/blog/2016/12/30-top-videos-tutorials-courses-on-machine-learning-artificial-intelligence-from-2016/)
- [ ] [程序员的深度学习实战](http://course.fast.ai/index.html)

## MOOC
- [ ] [Udacity的机器学习导论](https://www.udacity.com/course/intro-to-machine-learning--ud120)
    - [复习Udacity机器学习导论](http://hamelg.blogspot.com/2014/12/udacity-intro-to-machine-learning-review.html)
- [ ] [Udacity的监督学习、非监督学习及深入](https://www.udacity.com/course/machine-learning--ud262)
- [ ] [Machine Learning Foundations: A Case Study Approach](https://www.coursera.org/learn/ml-foundations)
- [ ] [Courserad的机器学习](https://www.coursera.org/learn/machine-learning)
    - [视频](https://www.youtube.com/playlist?list=PLZ9qNFMHZ-A4rycgrgOYma6zxF4BZGGPW)
    - [复习Coursera机器学习](https://rayli.net/blog/data/coursera-machine-learning-review/)
    - [Coursera的机器学习路线图](https://metacademy.org/roadmaps/cjrd/coursera_ml_supplement)
- [ ] [Machine Learning Distilled](https://code.tutsplus.com/courses/machine-learning-distilled)
- [ ] [BigML training](https://bigml.com/training)
- [ ] [Coursera的神经网络课程](https://www.coursera.org/learn/neural-networks)
    - 由Geoffrey Hinton（神经网络的先驱）执教
- [ ] [使用TensorFlow创建深度学习应用](https://www.kadenze.com/courses/creative-applications-of-deep-learning-with-tensorflow/info)
- [ ] [描述统计学概论](https://www.udacity.com/course/intro-to-descriptive-statistics--ud827)
- [ ] [推理统计学概论](https://www.udacity.com/course/intro-to-inferential-statistics--ud201)
- [ ] [6.S094: 自动驾驶的深度学习](http://selfdrivingcars.mit.edu/)
- [ ] [6.S191: 深度学习简介](http://introtodeeplearning.com/index.html)
 
## 资源
- [ ] [一个月学会机器学习](https://elitedatascience.com/machine-learning-masterclass)
- [ ] [一份“非技术性”的机器学习与人工智能指南](https://medium.com/@samdebrule/a-humans-guide-to-machine-learning-e179f43b67a0#.cpzf3a5c0)
- [ ] [Google机器学习工程师最佳实践教程](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)
- [ ] [Hacker News的《软件工程师的机器学习》](https://news.ycombinator.com/item?id=12898718)
- [ ] [开发者的机器学习](https://xyclade.github.io/MachineLearning/)
- [ ] [给开发者的关于机器学习的建议](https://dev.to/thealexlavin/machine-learning-advice-for-developers)
- [ ] [机器学习入门](http://pythonforengineers.com/machine-learning-for-complete-beginners/)
- [ ] [为新手准备的机器学习入门教程](https://medium.com/@suffiyanz/getting-started-with-machine-learning-f15df1c283ea#.yjtiy7ei9)
- [ ] [初学者如何自学机器学习](https://elitedatascience.com/learn-machine-learning)
- [ ] [机器学习自学资源](https://ragle.sanukcode.net/articles/machine-learning-self-study-resources/)
- [ ] [提升你的机器学习技能](https://metacademy.org/roadmaps/cjrd/level-up-your-ml)
- [ ] [一份'坦诚'的机器学习指南](https://medium.com/axiomzenteam/an-honest-guide-to-machine-learning-2f6d7a6df60e#.ib12a1yw5)
- [ ] 用机器学习让Hacker News更具可读性
    - [视频](https://www.youtube.com/watch?v=O7IezJT9uSI)
    - [幻灯片](https://speakerdeck.com/pycon2014/enough-machine-learning-to-make-hacker-news-readable-again-by-ned-jackson-lovely)
- [ ] [深入机器学习](https://github.com/hangtwenty/dive-into-machine-learning)
- [ ] [软件工程师的{机器、深度}学习](https://speakerdeck.com/pmigdal/machine-deep-learning-for-software-engineers)
- [ ] [深度学习入门](https://deeplearning4j.org/deeplearningforbeginners.html)
- 大学中的机器学习课程
    - [ ] [斯坦福](http://ai.stanford.edu/courses/)
    - [ ] [机器学习夏令营](http://mlss.cc/)
    - [ ] [牛津](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
    - [ ] [剑桥](http://mlg.eng.cam.ac.uk/)
- Flipboard的主题
    - [机器学习](https://flipboard.com/topic/machinelearning)
    - [深度学习](https://flipboard.com/topic/deeplearning)
    - [人工智能](https://flipboard.com/topic/artificialintelligence)
- Medium的主题
    - [机器学习](https://medium.com/tag/machine-learning/latest)
    - [深度学习](https://medium.com/tag/deep-learning)
    - [人工智能](https://medium.com/tag/artificial-intelligence)
- 每月文章Top10
    - 机器学习
        - [2016年7月](https://medium.mybridge.co/top-ten-machine-learning-articles-for-the-past-month-9c1202351144#.lyycen64y)
        - [2016年8月](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-2f3cb815ffed#.i9ee7qkjz)
        - [2016年9月](https://medium.mybridge.co/machine-learning-top-10-in-september-6838169e9ee7#.4jbjcibft)
        - [2016年10月](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-35c37825a943#.td5im1p5z)
        - [2016年11月](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-b499e4213a34#.7k39i08tv)
        - [2016年](https://medium.mybridge.co/machine-learning-top-10-of-the-year-v-2017-7552599935c0#.wtx2mchqn)
    - 算法
        - [2016年9月](https://medium.mybridge.co/algorithm-top-10-articles-in-september-8a0e6afb0807#.hgjzuyxdb)
        - [2016年10月-11月](https://medium.mybridge.co/algorithm-top-10-articles-v-november-e73cba2fa87e#.kothimkhb)
- [全面的数据科学家的资源](http://www.datasciencecentral.com/group/resources/forum/topics/comprehensive-list-of-data-science-resources)
- [DigitalMind的人工智能资源](http://blog.digitalmind.io/post/artificial-intelligence-resources)
- [令人惊叹的机器学习](https://github.com/josephmisiti/awesome-machine-learning)
- [CreativeAi的机器学习](http://www.creativeai.net/?cat%5B0%5D=machine-learning)

## 成为一名开源贡献者
- [ ] [tensorflow/magenta: Magenta: Music and Art Generation with Machine Intelligence](https://github.com/tensorflow/magenta)
- [ ] [tensorflow/tensorflow: Computation using data flow graphs for scalable machine learning](https://github.com/tensorflow/tensorflow)
- [ ] [cmusatyalab/openface: Face recognition with deep neural networks.](https://github.com/cmusatyalab/openface)
- [ ] [tensorflow/models/syntaxnet: Neural Models of Syntax.](https://github.com/tensorflow/models/tree/master/syntaxnet)

## 游戏
- [Halite：AI编程游戏](https://halite.io/)
- [Vindinium: 挑战AI编程](http://vindinium.org/)
- [Video Game AI比赛](http://www.gvgai.net/)
- [愤怒的小鸟AI比赛](https://aibirds.org/)
- [The AI Games](http://theaigames.com/)
- [Fighting Game AI Competition](http://www.ice.ci.ritsumei.ac.jp/~ftgaic/)
- [CodeCup](http://www.codecup.nl/intro.php)
- [星际争霸AI学生锦标赛](http://sscaitournament.com/)
- [AIIDE星际争霸AI竞赛](http://www.cs.mun.ca/~dchurchill/starcraftaicomp/)
- [CIG星际争霸AI竞赛](https://sites.google.com/site/starcraftaic/)
- [CodinGame - AI Bot Games](https://www.codingame.com/training/machine-learning)

## 播客
- ### 适合初学者的播客：
    - [Talking Machines](http://www.thetalkingmachines.com/)
    - [Linear Digressions](http://lineardigressions.com/)
    - [Data Skeptic](http://dataskeptic.com/)
    - [This Week in Machine Learning & AI](https://twimlai.com/)

- ### “更多”进阶的播客：
    - [Partially Derivative](http://partiallyderivative.com/)
    - [O’Reilly Data Show](http://radar.oreilly.com/tag/oreilly-data-show-podcast)
    - [Not So Standard Deviation](https://soundcloud.com/nssd-podcast)

- ### 盒子外的播客：
    - [Data Stories](http://datastori.es/)

## 社区
- Quora
    - [机器学习](https://www.quora.com/topic/Machine-Learning)
    - [统计学](https://www.quora.com/topic/Statistics-academic-discipline)
    - [数据挖掘](https://www.quora.com/topic/Data-Mining)

- Reddit
    - [机器学习](https://www.reddit.com/r/machinelearning)
    - [计算机视觉](https://www.reddit.com/r/computervision)
    - [自然语言处理](https://www.reddit.com/r/languagetechnology)
    - [数据科学](https://www.reddit.com/r/datascience)
    - [大数据](https://www.reddit.com/r/bigdata)
    - [统计学](https://www.reddit.com/r/statistics)

- [Data Tau](http://www.datatau.com/)

- [Deep Learning News](http://news.startup.ml/)

- [KDnuggets](http://www.kdnuggets.com/)

## 面试问题
- [ ] [如何准备机器学习职位的面试](http://blog.udacity.com/2016/05/prepare-machine-learning-interview.html)
- [ ] [40个机器学习与数据科学的面试问题](https://www.analyticsvidhya.com/blog/2016/09/40-interview-questions-asked-at-startups-in-machine-learning-data-science)
- [ ] [21个必须要知道的数据科学问题与回答](http://www.kdnuggets.com/2016/02/21-data-science-interview-questions-answers.html)
- [ ] [Top 50 机器学习面试问题与回答](http://career.guru99.com/top-50-interview-questions-on-machine-learning/)
- [ ] [机器学习面试问题](https://resources.workable.com/machine-learning-engineer-interview-questions)
- [ ] [常用的机器学习面试问题](http://www.learn4master.com/machine-learning/popular-machine-learning-interview-questions)
- [ ] [机器学习面试问题有哪些相同的？](https://www.quora.com/What-are-some-common-Machine-Learning-interview-questions)
- [ ] [什么是评价一个机器学习研究者的最好的问题？](https://www.quora.com/What-are-the-best-interview-questions-to-evaluate-a-machine-learning-researcher)
- [ ] [机器学习面试问题大搜集](http://analyticscosm.com/machine-learning-interview-questions-for-data-scientist-interview/)
- [ ] [121个需要掌握的问题与回答](https://learn.elitedatascience.com/mlqa-welcome)


## 我崇拜的公司
- [ ] [ELSA - 你虚拟的口语教练](https://www.elsanow.io/home)
