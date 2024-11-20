本篇章的思路来源于github上ZuzooVn前辈的记录  
"machine-learning-for-software-engineers", 翻译自lsvih, 译为"自上而下的学习路线: 软件工程师的机器学习"  
当我们真正开始一段学习之前, 我很少会开始一段计划, 抑或是做一个记录, 我厌恶那种形式主义的内容, 但某种意义上说, 这或许是一种有趣的填空游戏, 从而激励自己能够坚持长期的学习过程, 即使对于我而言, 我依然会选择尽可能集中的学习方式。  
随着事情的增多, 我们的精力与时间被分散, 像以往那样集中专一的学习方式似乎不太可行, 我们可以再做尝试, 但to do list或许确实是一种适合的解决方式, 我们不应该在面临繁多事务时坚持理想主义的唯一, 事实上合理的规划时间精力, 正是这种矛盾状态下与自己和解的方式  
OK, let's start it  
## Why use this?
我们不去叙述作者的经历, 现状, 只是我们自己。  
目前进入大三, 自己面临学业/竞赛/考研/论文/恋爱以及那可有可无的生活抑或是说谋生等各种莫名其妙的压力, 更准确地说, 太多想做的事情要做的事情让自己分心, 以至于没能做好甚至一件事。一直以来面临多种选择时我们都选择非常简单的做法: 即放弃某一或某几项, 这使得我们格外的专注, 但同时也失去很多, 这正是当下为什么失去了保研的机会导致在考研和论文之间挣扎。  
OK, anyway路已至此, 我们该做什么? 我并不乐意专注于考研, 也可以说, 应试让我无比厌恶以及反感, 坚持自己讨厌的事情会失去动力, 因此我选择学习ML来补充精力。这很诡异但事实如此, 我希望做一点热爱的事情学一点热爱的东西来支持我的精力去学习那些我所厌恶的事务。诚然, 这很困难, 因此时间分配和进度安排尤其重要, therefore use this.  
## How to use this?
任务列表: 
- [ ] 未完成
- [x] 已完成
## Prerequest knowledge
作者提出的一些Prerequest knowledge我想是我一直有做但未曾提及的, 时间有限, Let's do it later:  
- [ ] What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big data? For my part, Deep learning also ought to be added in.
- [ ] Learnging How to Learn
- [ ] Don't Break The Chain
- [ ] How to learn on your own
## Motivation
作者的视频我有去看, 我同样很喜欢, 但他稍微有些空, 更像是心灵鸡汤, 无所谓, 这的确不错:  
- [ ] [Dream](https://www.youtube.com/watch?v=g-jwWYX7Jlo)
## Machine Learning Overview
我本打算自己去写, 但作者在这里提供了一些链接, 我想这应当有一定道理, 并前往仔细阅读。事实证明, 这样优秀的文章在国内的一些平台并不容易找到, 我很庆幸自己没有过度自大。这里我会认真阅读作者提供的阅读文章, 并尽可能补充自己的资料, 包括自己的理解, 如果时间允许, 我会添加自己的内容:
- [x] [A visual introduction to machine learning(房屋分类案例来介绍何为ML)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [ ] ~~[Gentle Guide to Machine Learning](https://blog.monkeylearn.com/gentle-guide-to-machine-learning/)~~(无法访问, 不知道是否是网络问题, 后续再做尝试)
- [x] [Model Tuning and the Bias-Variance Tradeoff(讲述模型调参/方差/偏差/过拟合等)](http://www.r2d3.us/visual-intro-to-machine-learning-part-2/)
- [ ] ~~[Introduction to Machine Learning for Developers](http://blog.algorithmia.com/introduction-machine-learning-developers/)~~(无法访问)
- [x] [Beginner Guide to Basic Machine Learning: Concepts and Techniques(一篇科普性文章, 宏观讲述机器学习的一些步骤/概念等)](https://www.analyticsvidhya.com/blog/2015/06/machine-learning-basics/#h-supervised-learning-predictive-models)(该网站里还有一些其他的比如Deep Learning的内容值得一看, by the way简单浏览了一下真的挺棒)
- [x] [How do you explain Machine Learning and Data Mining to non Computer Science people?(一个科普性的论坛?没有细看..)](https://www.quora.com/How-do-you-explain-Machine-Learning-and-Data-Mining-to-non-Computer-Science-people)(但值得关注的是, 这类似于国外的一个知识平台, 并非崇洋媚外但国内的知识平台如知乎/CSDN的信息有过多冗余)
- [x] [Big Data, Data Mining and Machine Learning: Under the Hood(科普性文章)](https://georgemdallas.wordpress.com/2013/06/11/big-data-data-mining-and-machine-learning-under-the-hood/)
- [x] [What is machine learning, and how does it work?(一个介绍ML的视频)](https://www.youtube.com/watch?v=elojMnjn4kk&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=2)(同样, 这是一系列的视频资源)
- [x] [How to become a Machine Learning Engineer](https://www.scaler.com/blog/how-to-become-a-machine-learning-engineer/#career-benefits-of-completing-an-ml-certification-course)
## Machine Learning is Fun!
作者的这个板块我本不想去做, 或许是独有的国内外思维差异, 我不太喜欢这种益智的通俗易懂的知识, 但某种意义上说, 学会如何用最简单的语言描述某个所谓复杂的事物才真正意味着我们懂了, 因此, 即使是记住他们的例子, 抑或是一种不同的表达方式, 尝试去理解他们, 或许并非毫无意义。
- [x] [Machin Learning is Fun(同样一个科普性的文章, 作者补充了一些课程资源可以在文章里找到)](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471#.37ue6caww)  
- [x] [Part 2: Using Machine Learning to generate Super Mario Maker levels](https://medium.com/@ageitgey/machine-learning-is-fun-part-2-a26a10b68df3#.kh7qgvp1b) - Machine Learning is Fun, 作者完美的做到了这一点。作为一个并非纯外行人, 我看到了其中某些有意义的东西, 见识到不同于我们传统的循规蹈矩的教材式的知识讲解, 庆幸自己认真去看了这篇文章。除此之外, 里面有一些有关循环神经网路的思想和代码, 我想其实他们是我能力范围之内的事情, 我们会找到时间动手实践一遍。  
经过尝试非常可惜, 该作者使用了一种lua的语言, 而我们对此一窍不通。
- [x] [Part 3: Deep Learning and Convolutional Neural Networks](https://medium.com/@ageitgey/machine-learning-is-fun-part-3-deep-learning-and-convolutional-neural-networks-f40359318721#.44rhxy637)  
讲解有关卷积神经网络的part3, 唯一可惜的是其中代码部分对数据处理并未提及, 而这正是困扰我的点...
- [x] [Part 4: Modern Face Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78#.3rwmq0ddc)   
part4中有关人脸识别的代码尝试去复现一下
- [x] [Part 5: Language Translation with Deep Learning and the Magic of Sequences](https://medium.com/@ageitgey/machine-learning-is-fun-part-5-language-translation-with-deep-learning-and-the-magic-of-sequences-2ace0acca0aa#.wyfthap4c)   
机器翻译这一节讲到seq2seq我想是他的巅峰之作之一, 当然Part4的有关encoding的描述也是精彩至极。
- [x] [Part 6: How to do Speech Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-6-how-to-do-speech-recognition-with-deep-learning-28293c162f7a#.lhr1nnpcy)   
语音识别这一块我个人兴趣不大, 但或许也是分心的缘故and上课不愿意学, 如果有时间, 我想重新看看信号处理会是一个好选择。
- [x] [Abusing Generative Adversarial Networks to Make 8-bit Pixel Art](https://medium.com/@ageitgey/abusing-generative-adversarial-networks-to-make-8-bit-pixel-art-e45d9b96cee7)   
生成对抗网络, 我个人感觉最值得去看和发展的方向之一
