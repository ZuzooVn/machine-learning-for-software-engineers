# 自上而下的學習路線：軟體工程師的機器學習


靈感來源於[谷歌面試學習手冊](https://github.com/jwasham/google-interview-university/blob/master/README-cn.md)


> * 原文地址：[軟體工程師的機器學習](https://github.com/ZuzooVn/machine-learning-for-software-engineers)
> * 原文作者：[ZuzooVn(Nam Vu)](https://github.com/ZuzooVn)
> * 翻譯：[NeroCube](https://github.com/NeroCube)


## 這是？

這是本人為期數月的學習計劃。我正要從一名行動裝置開發者(自學，沒有計算機學位)轉型成為一名機器學習工程師。

我的主要目標是找到一種以實踐為主的學習方法，並為初學者抽象掉大多數的數學概念。
這種學習方法是非傳統的，因為它是專門為軟體工程師所設計的自上而下，以結果為導向的學習方法。

如果您想讓它更好的話，隨時歡迎您的貢獻。

---

## 目錄

- [這是？](#這是)
- [為何要用到它？](#為何要用到它)
- [如何使用它？](#如何使用它)
- [Follow me](#follow-me)
- [別認為自己不夠聰明](#別認為自己不夠聰明)
- [關於影片資源](#關於影片資源)
- [預備知識](#預備知識)
- [每日計劃](#每日計劃)
- [動機](#動機)
- [機器學習概論](#機器學習概論)
- [掌握機器學習](#掌握機器學習)
- [有趣的機器學習](#有趣的機器學習)
- [染墨的機器學習簡介](#染墨的機器學習簡介)
- [一本深入的機器學習指南](#一本深入的機器學習指南)
- [故事與經驗](#故事與經驗)
- [機器學習演算法](#機器學習演算法)
- [入門書籍](#入門書籍)
- [實用書籍](#實用書籍)
- [Kaggle知識競賽](#kaggle知識競賽)
- [系列影片](#系列影片)
- [MOOC](#mooc)
- [資源](#資源)
- [遊戲](#遊戲)
- [成為一名開源貢獻者](#成為一名開源貢獻者)
- [廣播](#廣播)
- [社區](#社區)
- [相關會議](#相關會議)
- [面試問題](#面試問題)
- [我崇拜的公司](#我崇拜的公司)

---

## 為何要用到它？

我會為了我未來的工作————機器學習工程師 遵循這份計劃。自2011年以來，我一直進行著行動裝置的開發(包括安卓、iOS 與黑莓)。我有軟體工程的文憑，但沒有計算機科學的文憑。我僅僅在大學的時候學習過一點基礎科學，包括微積分、線性代數、離散數學、概率論與統計。
我認真思考過我在機器學習方面的興趣:
- [我能在沒有計算機科學碩士、博士文憑的情況下找到一份關於機器學習的工作嗎？](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD)
    - *"你當然可以，但是我想進入這個領域則無比艱難。"* [Drac Smith](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD/answer/Drac-Smith?srid=oT0p)
- [我是一名自學機器學習的軟體工程師，我如何在沒有相關經驗的情況下找到一份關於機器學習的工作？](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work)
    - *"我正在為我的團隊招聘機器學習專家，但你的 MOOC 並不會給你帶來工作機會。事實上，大多數機器學習方向的碩士也並不會得到工作機會，因為他們(與大多數上過 MOOC 的人一樣)並沒有深入地去理解。他們都沒法幫助我的團隊解決問題。"* [Ross C. Taylor](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work/answer/Ross-C-Taylor?srid=oT0p)
- [找一份機器學習相關的工作需要掌握怎樣的技能？](http://programmers.stackexchange.com/questions/79476/what-skills-are-needed-for-machine-learning-jobs)
    - *"首先，你得有正兒八經的計科或數學專業背景。ML 是一個比較先進的課題，大多數的教材都會直接默認你有以上背景。其次，機器學習是一個集成了許多子專業的奇技淫巧的課題，你甚至會想看看 MS 的機器學習課程，去看看他們的授課、課程和教材。"* [Uri](http://softwareengineering.stackexchange.com/a/79717)
    - *"統計，假設，分佈式計算，然後繼續統計。"* [Hydrangea](http://softwareengineering.stackexchange.com/a/79575)

我發現自己遇到了麻煩。

據我所知, [機器學習有兩個方向](http://machinelearningmastery.com/programmers-can-get-into-machine-learning/)：
- 實用機器學習： 這個方向主要是查詢資料庫、數據清洗、寫腳本來轉換數據，把演算法和函式庫結合起來再加上一些客製化的程式，從數據中擠出一些準確的答案來證明一些困難且模糊不清的問題。實際上它非常混亂。
- 理論機器學習： 這個方向主要是關於數學、抽象、理想狀況、極限條件、典型例子以及一切可能的特徵。這個方向十分的乾凈、整潔，遠離混亂的現實。

我認為對於以實踐為主的人來說，做好的方法就是 [“練習--學習--練習”](http://machinelearningmastery.com/machine-learning-for-programmers/#comment-358985)，這意味著每個學生一開始就能參與一些現有項目與一些問題，並練習(解決)它們以熟悉傳統的方法是怎麼做的。在有了一些簡單的練習經驗之後，他們就可以開始鑽進書里去學習理論知識。這些理論知識將幫助他們在將來進行更進一步的訓練，充實他們解決實際問題的工具箱。學習理論知識還會加深他們對那些簡單練習的理解，幫助他們更快地獲得進階的經驗。

這是一個很長的計劃，它花去了我一年的時間。如果你已經對它有所瞭解了，它將會讓你省去很多時間。

## 如何使用它？
以下的內容全部是概要，你需要由上往下來解決這些項目。

我使用 Github 獨特的 flavored markdown 方式，以任務列表來檢查我計劃的進展。

- [x] 創建一個新的分支，然後你可以這樣來標出你已經完成的項目，只需要在框中填寫一個x即可：[x]

[瞭解更多有關 Github-flavored markdown 的知識](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

## Follow me
我是一名非常非常想去美國工作的越南軟體工程師。

我在這份計劃中花多少時間？在每天的艱辛工作完成後，每晚花4小時。

我已經在實現夢想的旅途中了。

- Twitter: [@Nam Vu](https://twitter.com/zuzoovn)

| ![Nam Vu - Top-down learning path: machine learning for software engineers](http://sv1.upsieutoc.com/2016/10/08/331f241c8da44d0c43e9324d55440db6.md.jpg)|
|:---:|
| USA as heck |

## 別認為自己不夠聰明
當我打開書本，發現他們告訴我多變量微積分、推理統計、線性代數是學習機器學習的先決條件的時候，我非常沮喪。因為我不知道從哪兒開始…

- [我數學不好怎麼辦](http://machinelearningmastery.com/what-if-im-not-good-at-mathematics/)
- [沒有數學專業背景而理解機器學習演算法的5種技巧](http://machinelearningmastery.com/techniques-to-understand-machine-learning-algorithms-without-the-background-in-mathematics/)
- [我是如何學習機器學習的？](https://www.quora.com/Machine-Learning/How-do-I-learn-machine-learning-1)

## 關於影片資源

部分影音只有在 Coursera 、 EdX 的課程註冊了才能觀看。雖然它們是免費的，但有些時間段這些課程並不開放，你可能需要等上一段時間(可能是好幾個月)。我將會加上更多的公開的影片源來代替這些在線課程的影片。我很喜歡大學的講座。

## 預備知識

這個小章節是一些在每日計劃開始前我想去瞭解的一些預備知識與一些有趣的信息。

- [ ] [資料分析，資料解析，資料探勘，資料科學，機器學習，大數據的區別是什麼？](https://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)
- [ ] [學習如何去學習](https://www.coursera.org/learn/learning-how-to-learn)
- [ ] [不要斬斷鎖鏈](http://lifehacker.com/281626/jerry-seinfelds-productivity-secret)
- [ ] [如何自學](https://metacademy.org/roadmaps/rgrosse/learn_on_your_own)

## 每日計劃

每個主題都不需要用一整天來完全理解它們，你可以每天完成多個。

每天我都會從下面的列表中選一個出來，一遍又一遍的讀，做筆記，練習，用 Python 或 R語言實現它。

# 動機
- [ ] [夢](https://www.youtube.com/watch?v=g-jwWYX7Jlo)

## 機器學習概論
- [ ] [機器學習的形象簡介](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [ ] [一份輕鬆的機器學習指南](https://blog.monkeylearn.com/a-gentle-guide-to-machine-learning/)
- [ ] [為開發者準備的機器學習簡介](http://blog.algorithmia.com/introduction-machine-learning-developers/)
- [ ] [菜鳥的機器學習基礎](https://www.analyticsvidhya.com/blog/2015/06/machine-learning-basics/)
- [ ] [你如何向非計算機專業的人來解釋機器學習與資料探勘？](https://www.quora.com/How-do-you-explain-Machine-Learning-and-Data-Mining-to-non-Computer-Science-people)
- [ ] [機器學習：葫蘆裡賣什麼藥，部落格簡單明瞭地介紹了機器學習的原理](https://georgemdallas.wordpress.com/2013/06/11/big-data-data-mining-and-machine-learning-under-the-hood/)
- [ ] [機器學習是什麼？它是如何工作的呢？](https://www.youtube.com/watch?v=elojMnjn4kk&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=1)
- [ ] [深度學習——一份非技術性的簡介](http://www.slideshare.net/AlfredPong1/deep-learning-a-nontechnical-introduction-69385936)

## 掌握機器學習
- [ ] [掌握機器學習的方法](http://machinelearningmastery.com/machine-learning-mastery-method/)
- [ ] [程式設計師的機器學習](http://machinelearningmastery.com/machine-learning-for-programmers/)
- [ ] [掌握並運用機器學習](http://machinelearningmastery.com/start-here/)
- [ ] [Python 機器學習小課程](http://machinelearningmastery.com/python-machine-learning-mini-course/)
- [ ] [機器學習演算法小課程](http://machinelearningmastery.com/machine-learning-algorithms-mini-course/)

## 有趣的機器學習
- [ ] [機器學習真有趣！](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471#.37ue6caww)
- [ ] [Part 2: 使用機器學習來創造超級馬利奧的關卡](https://medium.com/@ageitgey/machine-learning-is-fun-part-2-a26a10b68df3#.kh7qgvp1b)
- [ ] [Part 3: 深度學習與捲積神經網路](https://medium.com/@ageitgey/machine-learning-is-fun-part-3-deep-learning-and-convolutional-neural-networks-f40359318721#.44rhxy637)
- [ ] [Part 4: 現代人臉識別與深度學習](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78#.3rwmq0ddc)
- [ ] [Part 5: 翻譯與深度學習和序列的魔力](https://medium.com/@ageitgey/machine-learning-is-fun-part-5-language-translation-with-deep-learning-and-the-magic-of-sequences-2ace0acca0aa#.wyfthap4c)
- [ ] [Part 6: 如何使用深度學習進行語音識別](https://medium.com/@ageitgey/machine-learning-is-fun-part-6-how-to-do-speech-recognition-with-deep-learning-28293c162f7a#.lhr1nnpcy)
- [ ] [Part 7: 使用生成式對抗網路創造 8 像素藝術](https://medium.com/@ageitgey/abusing-generative-adversarial-networks-to-make-8-bit-pixel-art-e45d9b96cee7)
- [ ] [Part 8: 如何故意欺騙神經網路](https://medium.com/@ageitgey/machine-learning-is-fun-part-8-how-to-intentionally-trick-neural-networks-b55da32b7196)

## [染墨的機器學習簡介](https://triskell.github.io/2016/11/15/Inky-Machine-Learning.html)
- [ ] [Part 1 : 什麼是機器學習？](https://triskell.github.io/2016/10/23/What-is-Machine-Learning.html)
- [ ] [Part 2 : 監督學習與非監督學習](https://triskell.github.io/2016/11/13/Supervised-Learning-and-Unsupervised-Learning.html)

## 一本深入的機器學習指南
- [ ] [概述，目標，學習類型和演算法](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide/)
- [ ] [數據的選擇，準備與建模](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-2/)
- [ ] [模型的評估，驗證，復雜性與改進](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-3/)
- [ ] [模型性能與誤差分析](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-4/)
- [ ] [無監督學習，相關領域與實踐中的機器學習](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-5/)

## 故事與經驗
- [ ] [一周的機器學習](https://medium.com/learning-new-stuff/machine-learning-in-a-week-a0da25d59850#.tk6ft2kcg)
- [ ] [一年的機器學習](https://medium.com/learning-new-stuff/machine-learning-in-a-year-cdb0b0ebd29c#.hhcb9fxk1)
- [ ] [我是如何在3天內寫出我的第一個機器學習程式的](http://blog.adnansiddiqi.me/how-i-wrote-my-first-machine-learning-program-in-3-days/)
- [ ] [學習路徑：你成為機器學習專家的導師](https://www.analyticsvidhya.com/learning-path-learn-machine-learning/)
- [ ] [不是 PhD 你也可以成為機器學習的明日之星](https://backchannel.com/you-too-can-become-a-machine-learning-rock-star-no-phd-necessary-107a1624d96b#.g9p16ldp7)
- [ ] 如何6個月成為一名資料科學家：一名駭客的職業規劃
    - [影片](https://www.youtube.com/watch?v=rIofV14c0tc)
    - [投影片](http://www.slideshare.net/TetianaIvanova2/how-to-become-a-data-scientist-in-6-months)
- [ ] [5個你成為機器學習工程師必須要掌握的技能](http://blog.udacity.com/2016/04/5-skills-you-need-to-become-a-machine-learning-engineer.html)
- [ ] [你是一個自學成才的機器學習工程師嗎？你是怎麼做的？花了多長時間？](https://www.quora.com/Are-you-a-self-taught-machine-learning-engineer-If-yes-how-did-you-do-it-how-long-did-it-take-you)
- [ ] [一個人如何成為一名優秀的機器學習工程師？](https://www.quora.com/How-can-one-become-a-good-machine-learning-engineer)
- [ ] [一個專注於機器學習的學術假期](http://karlrosaen.com/ml/)

## 機器學習演算法
- [ ] [用10種機器學習演算法來解釋“部隊士兵”](https://www.analyticsvidhya.com/blog/2015/12/10-machine-learning-algorithms-explained-army-soldier/)
- [ ] [Top10的資料探勘演算法](https://rayli.net/blog/data/top-10-data-mining-algorithms-in-plain-english/)
- [ ] [介紹10種機器學習的術語](http://blog.aylien.com/10-machine-learning-terms-explained-in-simple/)
- [ ] [機器學習演算法之旅](http://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/)
- [ ] [機器學習工程師需要知道的10種演算法](https://gab41.lab41.org/the-10-algorithms-machine-learning-engineers-need-to-know-f4bb63f5b2fa#.ofc7t2965)
- [ ] [比較監督學習演算法](http://www.dataschool.io/comparing-supervised-learning-algorithms/)
- [ ] [機器學習算法：最簡化、可執行的機器學習演算法集合](https://github.com/rushter/MLAlgorithms)

## 入門書籍
- [ ] [《Data Smart: Using Data Science to Transform Information into Insight》第 1 版](https://www.amazon.com/Data-Smart-Science-Transform-Information/dp/111866146X)
- [ ] [《Data Science for Business: What you need to know about data mining and data analytic-thinking》](https://www.amazon.com/Data-Science-Business-Data-Analytic-Thinking/dp/1449361323/)
- [ ] [《Predictive Analytics: The Power to Predict Who Will Click, Buy, Lie, or Die》](https://www.amazon.com/Predictive-Analytics-Power-Predict-Click/dp/1118356853)

## 實用書籍
- [ ] [Hacker 的機器學習](https://www.amazon.com/Machine-Learning-Hackers-Drew-Conway/dp/1449303714)
    - [GitHub repository(R)](https://github.com/johnmyleswhite/ML_for_Hackers)
    - [GitHub repository(Python)](https://github.com/carljv/Will_it_Python)
- [ ] [Python 機器學習](https://www.amazon.com/Python-Machine-Learning-Sebastian-Raschka-ebook/dp/B00YSILNL0)
    - [GitHub repository](https://github.com/rasbt/python-machine-learning-book)
- [ ] [集體智能編程: 創建智慧 Web 2.0 應用](https://www.amazon.com/Programming-Collective-Intelligence-Building-Applications-ebook/dp/B00F8QDZWG)
- [ ] [機器學習: 演算法視角，第二版](https://www.amazon.com/Machine-Learning-Algorithmic-Perspective-Recognition/dp/1466583282)
    - [GitHub repository](https://github.com/alexsosn/MarslandMLAlgo)
    - [Resource repository](http://seat.massey.ac.nz/personal/s.r.marsland/MLbook.html)
- [ ] [Python 機器學習簡介: 資料科學家指南](http://shop.oreilly.com/product/0636920030515.do)
    - [GitHub repository](https://github.com/amueller/introduction_to_ml_with_python)
- [ ] [資料探勘: 機器學習工具與技術實踐，第 3 版](https://www.amazon.com/Data-Mining-Practical-Techniques-Management/dp/0123748569)
    - Teaching material
        - [1-5 章投影片(zip)](http://www.cs.waikato.ac.nz/ml/weka/Slides3rdEd_Ch1-5.zip)
        - [6-8 章投影片(zip)](http://www.cs.waikato.ac.nz/ml/weka/Slides3rdEd_Ch6-8.zip)
- [ ] [Machine Learning in Action](https://www.amazon.com/Machine-Learning-Action-Peter-Harrington/dp/1617290181/)
    - [GitHub repository](https://github.com/pbharrin/machinelearninginaction)
- [ ] [Reactive Machine Learning Systems(MEAP)](https://www.manning.com/books/reactive-machine-learning-systems)
    - [GitHub repository](https://github.com/jeffreyksmithjr/reactive-machine-learning-systems)
- [ ] [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)
    - [GitHub repository(R)](http://www-bcf.usc.edu/~gareth/ISL/code.html)
    - [GitHub repository(Python)](https://github.com/JWarmenhoven/ISLR-python)
    - [影片](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/)
- [ ] [使用 Python 構建機器學習系統](https://www.packtpub.com/big-data-and-business-intelligence/building-machine-learning-systems-python)
    - [GitHub repository](https://github.com/luispedro/BuildingMachineLearningSystemsWithPython)
- [ ] [學習 scikit-learn: 用 Python 進行機器學習](https://www.packtpub.com/big-data-and-business-intelligence/learning-scikit-learn-machine-learning-python)
    - [GitHub repository](https://github.com/gmonce/scikit-learn-book)
- [ ] [Probabilistic Programming & Bayesian Methods for Hackers](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
- [ ] [Probabilistic Graphical Models: Principles and Techniques](https://www.amazon.com/Probabilistic-Graphical-Models-Principles-Computation/dp/0262013193)
- [ ] [Machine Learning: Hands-On for Developers and Technical Professionals](https://www.amazon.com/Machine-Learning-Hands-Developers-Professionals/dp/1118889061)
    - [Machine Learning Hands-On for Developers and Technical Professionals review](https://blogs.msdn.microsoft.com/querysimon/2015/01/01/book-review-machine-learning-hands-on-for-developers-and-technical-professionals/)
    - [GitHub repository](https://github.com/jasebell/mlbook)
- [ ] [從數據中學習](https://www.amazon.com/Learning-Data-Yaser-S-Abu-Mostafa/dp/1600490069)
    - [在線教學](https://work.caltech.edu/telecourse.html)
- [ ] [強化學習——簡介(第 2 版)](https://webdocs.cs.ualberta.ca/~sutton/book/the-book-2nd.html)
    - [GitHub repository](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)
- [ ] [使用TensorFlow(MEAP)進行機器學習](https://www.manning.com/books/machine-learning-with-tensorflow)
    - [GitHub repository](https://github.com/BinRoot/TensorFlow-Book)

## Kaggle知識競賽
- [ ] [Kaggle 競賽：怎麼樣，在哪裡開始？](https://www.analyticsvidhya.com/blog/2015/06/start-journey-kaggle/)
- [ ] [一個初學者如何用一個小項目在機器學習入門並在 Kaggle 競爭](http://machinelearningmastery.com/how-a-beginner-used-small-projects-to-get-started-in-machine-learning-and-compete-on-kaggle)
- [ ] [如何競爭 Kaggle 的 Master](http://machinelearningmastery.com/master-kaggle-by-competing-consistently/)

## 系列影片
- [ ] [Machine Learning for Hackers](https://www.youtube.com/playlist?list=PL2-dafEMk2A4ut2pyv0fSIXqOzXtBGkLj)
- [ ] [Fresh Machine Learning](https://www.youtube.com/playlist?list=PL2-dafEMk2A6Kc7pV6gHH-apBFxwFjKeY)
- [ ] [Josh Gordon 的機器學習菜譜](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
- [ ] [在 30 分鐘以內瞭解機器學習的一切](https://vimeo.com/43547079)
- [ ] [一份友好的機器學習簡介](https://www.youtube.com/watch?v=IpGxLWOIZy4)
- [ ] [Nuts and Bolts of Applying Deep Learning - Andrew Ng](https://www.youtube.com/watch?v=F1ka6a13S9I)
- [ ] BigML Webinar
    - [影片](https://www.youtube.com/watch?list=PL1bKyu9GtNYHcjGa6ulrvRVcm1lAB8he3&v=W62ehrnOVqo)
    - [資源](https://bigml.com/releases)
- [ ] [mathematicalmonk's Machine Learning tutorials](https://www.youtube.com/playlist?list=PLD0F06AA0D2E8FFBA)
- [ ] [Machine learning in Python with scikit-learn](https://www.youtube.com/playlist?list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A)
    - [GitHub repository](https://github.com/justmarkham/scikit-learn-videos)
    - [部落格](http://blog.kaggle.com/author/kevin-markham/)
- [ ] [播放清單 - YouTuBe 上最熱門的機器學習、神經網路、深度學習影片](https://www.analyticsvidhya.com/blog/2015/07/top-youtube-videos-machine-learning-neural-network-deep-learning/)
- [ ] [16 個必看的機器學習教學](https://www.analyticsvidhya.com/blog/2016/10/16-new-must-watch-tutorials-courses-on-machine-learning/)
- [ ] [DeepLearning.TV](https://www.youtube.com/channel/UC9OeZkIwhzfv-_Cb7fCikLQ)
- [ ] [Learning To See](https://www.youtube.com/playlist?list=PLiaHhY2iBX9ihLasvE8BKnS2Xg8AhY6iV)
- [ ] [神經網路課程 - Université de Sherbrooke](https://www.youtube.com/playlist?list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH)
- [ ] [2016年 的 21 個深度學習影片課程](https://www.analyticsvidhya.com/blog/2016/12/21-deep-learning-videos-tutorials-courses-on-youtube-from-2016/)
- [ ] [2016 年的 30 個頂級的機器學習與人工智慧影片教學 Top Videos, Tutorials & Courses on Machine Learning & Artificial Intelligence from 2016](https://www.analyticsvidhya.com/blog/2016/12/30-top-videos-tutorials-courses-on-machine-learning-artificial-intelligence-from-2016/)
- [ ] [程式設計者的深度學習實戰](http://course.fast.ai/index.html)

## MOOC
- [ ] [edX 的人工智慧導論](https://www.edx.org/course/introduction-artificial-intelligence-ai-microsoft-dat263x)
- [ ] [Udacity 的機器學習導論](https://www.udacity.com/course/intro-to-machine-learning--ud120)
    - [復習 Udacity 機器學習導論](http://hamelg.blogspot.com/2014/12/udacity-intro-to-machine-learning-review.html)
- [ ] [Udacity 的監督學習、非監督學習及深入](https://www.udacity.com/course/machine-learning--ud262)
- [ ] [Machine Learning Foundations: A Case Study Approach](https://www.coursera.org/learn/ml-foundations)
- [ ] [Coursera的機器學習](https://www.coursera.org/learn/machine-learning)
    - [影片](https://www.youtube.com/playlist?list=PLZ9qNFMHZ-A4rycgrgOYma6zxF4BZGGPW)
    - [復習 Coursera 機器學習](https://rayli.net/blog/data/coursera-machine-learning-review/)
    - [Coursera 的機器學習路線圖](https://metacademy.org/roadmaps/cjrd/coursera_ml_supplement)
- [ ] [機器學習淬煉](https://code.tutsplus.com/courses/machine-learning-distilled)
- [ ] [BigML training](https://bigml.com/training)
- [ ] [Coursera 的神經網路課程](https://www.coursera.org/learn/neural-networks)
    - 由Geoffrey Hinton(神經網路的先驅)執教
- [ ] [使用 TensorFlow 創建深度學習應用](https://www.kadenze.com/courses/creative-applications-of-deep-learning-with-tensorflow/info)
- [ ] [描述統計學概論](https://www.udacity.com/course/intro-to-descriptive-statistics--ud827)
- [ ] [推理統計學概論](https://www.udacity.com/course/intro-to-inferential-statistics--ud201)
- [ ] [6.S094: 自動駕駛的深度學習](http://selfdrivingcars.mit.edu/)
- [ ] [6.S191: 深度學習簡介](http://introtodeeplearning.com/index.html)
- [ ] [Coursera 深度學習教學](https://www.coursera.org/specializations/deep-learning)
 
## 資源
- [ ] [一個月學會機器學習](https://elitedatascience.com/machine-learning-masterclass)
- [ ] [一份“非技術性”的機器學習與人工智慧指南](https://medium.com/@samdebrule/a-humans-guide-to-machine-learning-e179f43b67a0#.cpzf3a5c0)
- [ ] [Google 機器學習工程師最佳實踐教學](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)
- [ ] [Hacker News 的《軟體工程師的機器學習》](https://news.ycombinator.com/item?id=12898718)
- [ ] [開發者的機器學習](https://xyclade.github.io/MachineLearning/)
- [ ] [為人類🤖👶準備的機器學習](https://medium.com/machine-learning-for-humans/why-machine-learning-matters-6164faf1df12)
- [ ] [給開發者的關於機器學習的建議](https://dev.to/thealexlavin/machine-learning-advice-for-developers)
- [ ] [機器學習入門](http://pythonforengineers.com/machine-learning-for-complete-beginners/)
- [ ] [為新手準備的機器學習入門教學](https://medium.com/@suffiyanz/getting-started-with-machine-learning-f15df1c283ea#.yjtiy7ei9)
- [ ] [初學者如何自學機器學習](https://elitedatascience.com/learn-machine-learning)
- [ ] [機器學習自學資源](https://ragle.sanukcode.net/articles/machine-learning-self-study-resources/)
- [ ] [提升你的機器學習技能](https://metacademy.org/roadmaps/cjrd/level-up-your-ml)
- [ ] [一份'真誠'的機器學習指南](https://medium.com/axiomzenteam/an-honest-guide-to-machine-learning-2f6d7a6df60e#.ib12a1yw5)
- [ ] 用機器學習讓 Hacker News 更具可讀性
    - [影片](https://www.youtube.com/watch?v=O7IezJT9uSI)
    - [投影片](https://speakerdeck.com/pycon2014/enough-machine-learning-to-make-hacker-news-readable-again-by-ned-jackson-lovely)
- [ ] [深入機器學習](https://github.com/hangtwenty/dive-into-machine-learning)
- [ ] [軟體工程師的{機器、深度}學習](https://speakerdeck.com/pmigdal/machine-deep-learning-for-software-engineers)
- [ ] [深度學習入門](https://deeplearning4j.org/deeplearningforbeginners.html)
- [ ] [深度學習基礎](https://github.com/pauli-space/foundations_for_deep_learning)
- [ ] [機器學習思維導圖/小抄](https://github.com/dformoso/machine-learning-mindmap)
- 大學中的機器學習課程
    - [ ] [斯坦福](http://ai.stanford.edu/courses/)
    - [ ] [機器學習夏令營](http://mlss.cc/)
    - [ ] [牛津](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
    - [ ] [劍橋](http://mlg.eng.cam.ac.uk/)
- Flipboard的主題
    - [機器學習](https://flipboard.com/topic/machinelearning)
    - [深度學習](https://flipboard.com/topic/deeplearning)
    - [人工智慧](https://flipboard.com/topic/artificialintelligence)
- Medium的主題
    - [機器學習](https://medium.com/tag/machine-learning/latest)
    - [深度學習](https://medium.com/tag/deep-learning)
    - [人工智慧](https://medium.com/tag/artificial-intelligence)
- 每月文章Top10
    - 機器學習
        - [2016年7月](https://medium.mybridge.co/top-ten-machine-learning-articles-for-the-past-month-9c1202351144#.lyycen64y)
        - [2016年8月](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-2f3cb815ffed#.i9ee7qkjz)
        - [2016年9月](https://medium.mybridge.co/machine-learning-top-10-in-september-6838169e9ee7#.4jbjcibft)
        - [2016年10月](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-35c37825a943#.td5im1p5z)
        - [2016年11月](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-b499e4213a34#.7k39i08tv)
        - [2016年](https://medium.mybridge.co/machine-learning-top-10-of-the-year-v-2017-7552599935c0#.wtx2mchqn)
    - 演算法
        - [2016年9月](https://medium.mybridge.co/algorithm-top-10-articles-in-september-8a0e6afb0807#.hgjzuyxdb)
        - [2016年10月-11月](https://medium.mybridge.co/algorithm-top-10-articles-v-november-e73cba2fa87e#.kothimkhb)
- [全面的數據科學資源清單](http://www.datasciencecentral.com/group/resources/forum/topics/comprehensive-list-of-data-science-resources)
- [DigitalMind 的人工智慧資源](http://blog.digitalmind.io/post/artificial-intelligence-resources)
- [令人驚嘆的機器學習](https://github.com/josephmisiti/awesome-machine-learning)
- [CreativeAi 的機器學習](http://www.creativeai.net/?cat%5B0%5D=machine-learning)

## 遊戲
- [Halite：AI 編程遊戲](https://halite.io/)
- [Vindinium: 挑戰 AI 編程](http://vindinium.org/)
- [Video Game AI 比賽](http://www.gvgai.net/)
- [憤怒的小鳥 AI 比賽](https://aibirds.org/)
- [The AI Games](http://theaigames.com/)
- [Fighting Game AI Competition](http://www.ice.ci.ritsumei.ac.jp/~ftgaic/)
- [CodeCup](http://www.codecup.nl/intro.php)
- [星際爭霸 AI 學生錦標賽](http://sscaitournament.com/)
- [AIIDE 星際爭霸 AI 競賽](http://www.cs.mun.ca/~dchurchill/starcraftaicomp/)
- [CIG 星際爭霸 AI 競賽](https://sites.google.com/site/starcraftaic/)
- [CodinGame - AI Bot Games](https://www.codingame.com/training/machine-learning)

## 成為一名開源貢獻者
- [ ] [tensorflow/magenta: Magenta: 用機器智慧生成音樂與藝術](https://github.com/tensorflow/magenta)
- [ ] [tensorflow/tensorflow: 使用數據流圖進行計算進行可擴展的機器學習](https://github.com/tensorflow/tensorflow)
- [ ] [cmusatyalab/openface: 使用深層神經網路進行面部識別](https://github.com/cmusatyalab/openface)
- [ ] [tensorflow/models/syntaxnet: 神經網路模型語法](https://github.com/tensorflow/models/tree/master/syntaxnet)

## 廣播
- ### 適合初學者的廣播：
    - [Talking Machines](http://www.thetalkingmachines.com/)
    - [Linear Digressions](http://lineardigressions.com/)
    - [Data Skeptic](http://dataskeptic.com/)
    - [This Week in Machine Learning & AI](https://twimlai.com/)

- ### “更多”進階的廣播：
    - [Partially Derivative](http://partiallyderivative.com/)
    - [O’Reilly Data Show](http://radar.oreilly.com/tag/oreilly-data-show-podcast)
    - [Not So Standard Deviation](https://soundcloud.com/nssd-podcast)

- ### 盒子外的廣播：
    - [Data Stories](http://datastori.es/)

## 社區
- Quora
    - [機器學習](https://www.quora.com/topic/Machine-Learning)
    - [統計學](https://www.quora.com/topic/Statistics-academic-discipline)
    - [資料探勘](https://www.quora.com/topic/Data-Mining)

- Reddit
    - [機器學習](https://www.reddit.com/r/machinelearning)
    - [計算機視覺](https://www.reddit.com/r/computervision)
    - [自然語言處理](https://www.reddit.com/r/languagetechnology)
    - [資料科學](https://www.reddit.com/r/datascience)
    - [大數據](https://www.reddit.com/r/bigdata)
    - [統計學](https://www.reddit.com/r/statistics)

- [Data Tau](http://www.datatau.com/)

- [Deep Learning News](http://news.startup.ml/)

- [KDnuggets](http://www.kdnuggets.com/)

## 相關會議
  - ([NIPS](https://nips.cc/))
  - ([ICLR](http://www.iclr.cc/doku.php?id=ICLR2017:main&redirect=1))
  - ([AAAI](http://www.aaai.org/Conferences/AAAI/aaai17.php))
  - ([IEEE CIG](http://www.ieee-cig.org/))
  - ([IEEE ICMLA](http://www.icmla-conference.org/))
  - ([ICML](https://2017.icml.cc/))

## 面試問題
- [ ] [如何準備機器學習職位的面試](http://blog.udacity.com/2016/05/prepare-machine-learning-interview.html)
- [ ] [40 個機器學習與資料科學的面試問題](https://www.analyticsvidhya.com/blog/2016/09/40-interview-questions-asked-at-startups-in-machine-learning-data-science)
- [ ] [21 個必須要知道的資料科學問題與回答](http://www.kdnuggets.com/2016/02/21-data-science-interview-questions-answers.html)
- [ ] [Top 50 機器學習面試問題與回答](http://career.guru99.com/top-50-interview-questions-on-machine-learning/)
- [ ] [機器學習面試問題](https://resources.workable.com/machine-learning-engineer-interview-questions)
- [ ] [常用的機器學習面試問題](http://www.learn4master.com/machine-learning/popular-machine-learning-interview-questions)
- [ ] [機器學習面試問題有哪些相同的？](https://www.quora.com/What-are-some-common-Machine-Learning-interview-questions)
- [ ] [什麼是評價一個機器學習研究者的最好的問題？](https://www.quora.com/What-are-the-best-interview-questions-to-evaluate-a-machine-learning-researcher)
- [ ] [機器學習面試問題大搜集](http://analyticscosm.com/machine-learning-interview-questions-for-data-scientist-interview/)
- [ ] [121 個需要掌握的問題與回答](https://elitedatascience.com/mlqa-reading-list)


## 我崇拜的公司
- [ ] [ELSA - 你虛擬的口語教練](https://www.elsanow.io/home)
