# 编程大学

> 我起初创建这个的目的是作为一个记录成为一个软件工程师的学习主题的简短的 to-do 列表，但是它慢慢变成了一个你现在看到的一个庞大的列表。经过完成了这个学习计划，我作为一个软件开发工程师被 Amazon 聘用了！可能你不需要和我学习一样的内容。不管怎样，你需要的东西都在这了。

>这里列出的项目会让你对所有的软件公司包括那些巨头: Amazon,Facebook,Google或者 Microsoft的面试做好准备。

>祝你好运！

## 这是什么？

这是我为了从一个 web 开发者(自学，没有 CS 学位)到一个巨型公司的软件工程师的数月的学习计划。

![](https://camo.githubusercontent.com/9e32acff11b04496eb14e09b198fcbb055c9ccf0/68747470733a2f2f646e67356c33717a7265616c362e636c6f756466726f6e742e6e65742f323031362f4175672f636f64696e675f626f6172645f736d616c6c2d313437303836363336393131382e6a7067)

这是提供给那些刚刚成为软件工程师或者那些选择从软件/网页开发转到软件工程(需要计算机科学知识)的人。如果你多年的软件工程经验，那你就得接收更严格的面试。

如果你有多年的软件/网页开发经验，要注意大型的软件公司像Google，Amazon，Facebook和Microsoft将软件工程看作是和软件/网页开发不同的东西，软件工程需要有计算机科学知识。

如果你想成为一个可靠的工程师或者运营工程师，那就多学习可选列表(网络，安全)中的内容。

## 目录

## 为什么使用它？

当我开始启动这个项目，我不知道 heap 中的 stack ,一点都不了解 Big-O(复杂度)，也完全不了解树，或者如何进行图遍历(树遍历也是图遍历的一种)。如果我需要写一个排序算法的代码，我可以说写的不会很好。我使用的每一个数据结构都是语言里内置好的，并且我也不懂他们底层的原理。我从来没有管理过内存除非它抛出了一个"out of memory"的异常，这个时候我才会去寻找一个解决方案。我使用过一些多维数组和数千次的 associative arrays(关联数组，也称作映射)，但是我从来没有从头开始创建一个数据结构。

这是一个长远的计划。它可能会花费你数月的时间。如果你已经熟悉其中的很多内容那么会节省下来很多的时间。

## 如何使用它？

下面所有的东西都是一个大纲，而且你需要从上到下去处理这些项目。

我使用的是 Github 里指定的 markdown 风格，包括了任务列表到进度检查。

**创建一个新的分支这样你可以像这样使用方括号包裹的X标记完成的项目:[X]**

通过以下的命令来 fork 一个分支

```
git checkout -b progress
```
```
git remote add jwasham https://github.com/jwasham/coding-interview-university
```
```
git fetch --all
```

当你完成你的改变的时候在方框里打叉
```
git add .
```
```
git commit -m "Marked x"
```
```
git rebase jwasham/master
```
```
git push --force
```

[更多关于 Github 风格的 markdown 信息](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

## 不要觉得你不够聪明

- 成功的软件工程师都是聪明的，但是他们很多人觉得自己不够聪明而缺乏安全感
- [X] [天才程序员的神话(The myth of the Genius Programmer)](https://www.youtube.com/watch?v=0SARbwvhupQ)
  - 内容概要:<br>
There is no genius<br>
Lose the ego<br>
Criticism is not evil<br>
Embrace failure<br>
Iterate Quickly<br>
Be a small fish<br>
Be influenced<br>
Be vulnerable<br>
Tools<br>
Involve collaborators early, but not too (at the 'sweet spot')<br>

- [X] [独自一人是很危险的:在技术领域和无形的怪兽战斗(It's Dangerous to Go Alone: Battling the Invisible Monsters in Tech)](https://www.youtube.com/watch?v=1i8ylq4j_EY)

- [X] [相信你自己可以改变(Believe you can change)](http://www.aaronsw.com/weblog/dweck)

## 关于视频资源

一些视频只有在登录了 Coursera, EdX,或者 Lynda.com 的班级才能观看。这些是慕课。有的时候这些课程不在开课时间中，所以你必须等待几个月的时间，这段时间内你没有权限观看这些视频。Lynda.com 的课程并不是免费的。

```
如果你们能帮助我添加免费且永久可用的公共资源我会非常感谢，比如 YouTube 视频来辅助在线课程视频。
我喜欢使用大学讲座。
```

## 面试的流程 & 通常的面试准备过程

- [x] [ABC: 保持编程(ABC: Always Be Coding).](https://medium.com/always-be-coding/abc-always-be-coding-d5f8051afce2#.4heg8zvm4)[中文译文](../../../OneDrive/Code/CodeRecord/mind/ABC-Always-Be-Coding.md)
- [x] [白板编程(Whiteboarding)](https://medium.com/@dpup/whiteboarding-4df873dbba2e#.hf6jn45g1) [中文译文](../../../OneDrive/Code/Way To Google/GitHubCodeInterview/Whitebording.md)
- [x] [ 在编程面试中进行高效的白板编程(Effective Whiteboarding during Programming Interviews)](http://www.coderust.com/blog/2014/04/10/effective-whiteboarding-during-programming-interviews/) [中文译文](../../../OneDrive/Code/Way To Google/GitHubCodeInterview/Effective-Whitebording-During-Programing-Interviews.md)
- [x] [揭开技术招聘的秘密(Demystifying Tech Recruiting)](https://www.youtube.com/watch?v=N233T0epWTs)
- [ ] 攻破编程面试 集合1:
    - [ ] [Gayle L McDowell - 攻破编程面试(视频)(Gayle L McDowell - Cracking The Coding Interview (video))](https://www.youtube.com/watch?v=rEJzOhC5ZtQ)
    - [ ] [和 Gayle Laakmann McDowell 一起攻破编程面试(Cracking the Coding Interview with Author Gayle Laakmann McDowell (video))](https://www.youtube.com/watch?v=aClxtDcdpsQ)
- [ ] 如何获得4个巨头公司的工作:
    - [ ] [如何获得4个巨头公司的工作 - Amazon ,Facebook,Google & Microsoft (视频)(How to Get a Job at the Big 4 - Amazon, Facebook, Google & Microsoft (video))](https://www.youtube.com/watch?v=YJZCUhxNCv8)
- [ ] 预备课程:
    - [ ] [软件工程师面试出炉(付费课程)(Software Engineer Interview Unleashed (paid course))](https://www.udemy.com/software-engineer-interview-unleashed):
        - 学习如何让你自己准备好接受前 Google 面试官的软件工程师面试。
    - [ ] [Python 的数据结构，算法，以及面试(Python for Data Structures, Algorithms, and Interviews! (paid course))](https://www.udemy.com/python-for-data-structures-algorithms-and-interviews/):
        - 一个以 Python 为中心面试的准备课程，覆盖了数据结构，算法，模拟面试等等。

## 为面试选择一门语言

在面试的编程部分你可以选择一个你熟悉的语言，但是对于大公司来说，这些是可靠的选择:

- C++
- Java
- Python

你也可以使用这些，但是先阅读清楚.那里可能有一些警示:

- JavaScript
- Ruby

你需要非常熟悉这个语言而且对这个语言的有深入的了解。

更多的选择:
- http://www.byte-by-byte.com/choose-the-right-language-for-your-coding-interview/
- http://blog.codingforinterviews.com/best-programming-language-jobs/

[在这里查看语言资源](programming-language-resources.md)

你会看到下面的学习资源包含一些 C,C++,和 Python，因为我在学习这些。在底部还有一些书籍推荐。

## 书单

这个书单比我使用的的还要简短一些。这个缩略的书单节省你的时间。

### 面试准备

- [ ] [揭秘编程面试:找到你下一份工作的秘密，第2版(Programming Interviews Exposed: Secrets to Landing Your Next Job, 2nd Edition)](http://www.wiley.com/WileyCDA/WileyTitle/productCd-047012167X.html)
    - 使用 C++ 和 Java
    - 这对于攻破编程面试是一个很好的热身
    - 不会太困难，大部分的问题可能会比你面试中的要更简单(从我看到的内容来看)
- [ ] [攻破编程面试，第2版(Cracking the Coding Interview, 6th Edition)](http://www.amazon.com/Cracking-Coding-Interview-6th-Programming/dp/0984782850/)
    - 使用 Java

如果你有大量的额外的时间:

- [ ] [编程面试的要素(C++版本)(Elements of Programming Interviews (C++ version))](https://www.amazon.com/Elements-Programming-Interviews-Insiders-Guide/dp/1479274836)
- [ ] 编程面试的要素(Java 版本)(Elements of Programming Interviews (Java version))
    - [书](https://www.amazon.com/Elements-Programming-Interviews-Java-Insiders/dp/1517435803/)
    - [配套项目-书中的每一个问题的解决方法和例子的记录](https://github.com/gardncl/elements-of-programming-interviews)

### 计算机架构

如果只有短时间的话:

- [ ] [写伟大的代码:卷1:理解机器(Write Great Code: Volume 1: Understanding the Machine)](https://www.amazon.com/Write-Great-Code-Understanding-Machine/dp/1593270038)
    - 这本书发行于 2004 年，虽然有些过时，但是对于简单了解计算机的话是一个极好的资源。
    - 这个作者创造了 HLA( High Level Assembler 高级汇编程序)，所以带有一些风趣的使用 HLA 提及了一些例子。虽然没有广泛的使用，但这些例子看起来是十分得体的。
    - 这些章节对于打下一个良好的基础是十分值得阅读的:
        - 第2章 - 数字化表示(Numeric Representation)
        - 第3章 -  二进制算术和位操作(Binary Arithmetic and Bit Operations)
        - 第4章 - 浮点型表示(Floating-Point Representation)
        - 第5章 - 字符表示(Character Representation)
        - 第6章 - 内存管理和访问(Memory Organization and Access)
        - 第7章 - 复合数据类型和内存对象(Composite Data Types and Memory Objects)
        - 第9章 - CPU 架构(CPU Architecture)
        - 第10章 - 指令集架构(Instruction Set Architecture)
        - 第11章 - 内存架构和管理(Memory Architecture and Organization)

如果你有更多的时间(我想要这本书):

- [ ] [计算机架构，第6版:定量方法(Computer Architecture, Sixth Edition: A Quantitative Approach)](https://www.amazon.com/dp/0128119055)
    - 获取更多更及时的内容可以使用 2017 版，但是需要花更多的的时间

### 选定语言

**你需要为面试选择一门语言(看上面)。** 这里是我对语言选择的推荐。我没有所有语言的资源。我欢迎大家添加。

如果你阅读其中的一种，你应该掌握编程问题中需要的所有的数据结构和算法知识。
**你可以跳过这个项目中的所有的视频课程** ，除非你想要做一个复习。

[这里是额外的指定语言的资源。](programming-language-resources.md)

### C++

我还没有读过这两本书，但是他们是高分的并且是 Sedgewick 写的。他是一个了不起的人。

- [ ] [C++ 算法 ，1-4: 基础，数据结构，排序，搜索(Algorithms in C++, Parts 1-4: Fundamentals, Data Structure, Sorting, Searching)](https://www.amazon.com/Algorithms-Parts-1-4-Fundamentals-Structure/dp/0201350882/)
- [ ] [C++ 算法 5:图算法(Algorithms in C++ Part 5: Graph Algorithms)](https://www.amazon.com/Algorithms-Part-Graph-3rd-Pt-5/dp/0201361183/)

如果在 C++ 上你有更好的推荐，请让我知道。我们正在寻找全面的资源。

### Java

- [ ] [算法(Sedgewick 和 Wayne)(Algorithms (Sedgewick and Wayne))](https://www.amazon.com/Algorithms-4th-Robert-Sedgewick/dp/032157351X/)
    - 书籍内容的视频(有 Sedgewick！)
        - [算法 I(Algorithms I)](https://www.youtube.com/user/algorithmscourses/playlists?view=50&sort=dd&shelf_id=2)
        - [算法 II(Algorithms II)](https://www.youtube.com/user/algorithmscourses/playlists?shelf_id=3&view=50&sort=dd)

或者:

- [ ] [Java 数据结构与算法(Data Structures and Algorithms in Java)](https://www.amazon.com/Data-Structures-Algorithms-Michael-Goodrich/dp/1118771338/)
    - 由 Goodrich, Tamassia, Goldwasser 编著
    - 作为加州大学伯克利分校的 CS 课程的额外学习内容
    - 可以参考下面 Python 的书籍报告。这本书覆盖了相同的内容。

### Python

- [ ] [Python 数据结构与算法(Data Structures and Algorithms in Python)](https://www.amazon.com/Structures-Algorithms-Python-Michael-Goodrich/dp/1118290275/)
    - 由 Goodrich, Tamassia, Goldwasser 编著
    - 我爱这本书。它覆盖了所有东西并且更多。
    - Pythonic 的代码
    - 我的书籍报告: https://startupnextdoor.com/book-report-data-structures-and-algorithms-in-python/

### 可选书籍

**有些人推荐这些，但是我觉得太过度了，除非你有很多年的软件工程经验并且想要一个更难的面试:**

- [ ] [算法设计手册(Algorithm Design Manual)](http://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1849967202) (Skiena)
    - 作为复习和问题识别
    - 算法目录部分已经远远超过了你在面试中会遇到的难题的范围。
    - 这本书有两个部分:
        - 数据结构和算法的教材
            - 优点:
                - 对于任何算法教材都可以当做很好的复习材料
                - 这是一个很好的故事讲述了通过他的经验解决了工业商和学术上的问题
                - 例子使用了 C 语言
            - 缺点:
                - 和 CLRS (算法导论（Introduction to Algorithms）) 一样的密集或晦涩的，甚至在某些情况下，CLRS 可能会是一个更好的选择。
                - 要理解第 7，8，9 章是非常痛苦的，因为有些项目是没有解释的易于理解或者要求有比我更好的头脑
                - 不要误解我: 我喜欢 Skiena ，他的教学风格，他的行为处事，但是可能我不是一个 Stony Brook 那样的材料
        - 算法目录:
            - 这是你买这本书的真正原因。
            - 有关于这部分的内容。一旦我使用自己的方法理解它后将会在这里更新。
    - 可以在 kindle 上租用它
    - 答案:
        - [解决方案](http://www.algorithm.cs.sunysb.edu/algowiki/index.php/The_Algorithms_Design_Manual_(Second_Edition))
        - [解决方案](http://blog.panictank.net/category/algorithmndesignmanualsolutions/page/2/)
    - [正误表](http://www3.cs.stonybrook.edu/~skiena/algorist/book/errata)

- [ ] [算法导论(Introduction to Algorithms)](https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844)
    -   **重点:** 阅读这本书只会有有限的价值。这本书是复习算法和数据结构的一本极好的书，但是不会教你如何写好的代码。你要能够编写一个高效的解决方案。
    - 也叫 CLR ，有时候也叫 CLRS ，因为 Stein 晚了一步

- [ ] [编程珠玑(Programming Pearls)](http://www.amazon.com/Programming-Pearls-2nd-Jon-Bentley/dp/0201657880)
    - 前几章展示了对编程问题的巧妙的解决办法(有些使用了非常古老的数据磁带)但是这仅仅只是一个简介。这是一个程序设计和架构的指南，于 Code Complete 极为相似，但是更加的简短。

- ~~"算法与编程:问题和解决方案(Algorithms and Programming: Problems and Solutions)" Shen 编著~~
    - 是一本好书，但是在解决了几页的问题后我对 Pascal 失去了信心，问题有 do while 循环， 1-indexed 数组，和不明确后置条件的满意度调查结果。
    - 还不如花时间在其它的书的编程问题上或者在线编程问题上。

## 在你开始之前

这个列表成长了许多个月，是的，它有点失控了。

这里有些我犯得错误可能会让你得到一些更好的经验。

### 1. 你不会记得所有的内容

我看了数个小时的视频并且记录了大量的笔记，但是几个月后我已经忘了很多内容。我花了3天阅读了笔记并且制作了抽认卡片以便于我可以复习。

请阅读这些避免你也犯下我犯的错误:

[记忆计算机科学的知识](https://startupnextdoor.com/retaining-computer-science-knowledge/)

### 2. 使用抽认卡

为了解决这个问题，我做了一些抽认卡页面这样我可以添加两种类型的抽认卡(flashcards):通用知识和代码。每一种卡片有不同的格式。

我制作了一个优先考虑手机的网站这样我可以不管在什么地方都可以使用我的手机和平板进行复习。

免费制作你自己的卡片:

- [抽认卡仓库](https://github.com/jwasham/computer-science-flash-cards)
- [我的抽认卡数据库 (旧版 - 1200 张卡)](https://github.com/jwasham/computer-science-flash-cards/blob/master/cards-jwasham.db):
- [我的抽认卡数据库(新版 - 1800 张卡)](https://github.com/jwasham/computer-science-flash-cards/blob/master/cards-jwasham-extreme.db):

要注意我已经过度记录了内容，这些卡片的内容从汇编语言和 Python 的细节到机器学习和统计学。相对于需要掌握的内容超出了太多。

**抽认卡的注意事项:** 当你第一次觉得你知道答案的时候，不要将它标记为已知。你必须阅读同样的卡片数次并且都答对了才算你真正懂了。不断的重复将会让知识深入你的大脑。

另一个使用我的抽认卡站点的方式是 [Anki](http://ankisrs.net/) ，已经向我推荐过很多次了。它使用了重复系统来帮助你记忆。

它对用户很友好，支持全平台并且有一个云同步系统。它在 iOS 上要花费 $25 而在其它平台是免费的。

我的 Anki 格式的抽认卡数据库: https://ankiweb.net/shared/info/25173560 (thanks [@xiewenya](https://github.com/xiewenya))

### 3. 复习，复习，复习

我保留了一些 ASCII ，OSI 堆栈，复杂度等等的速查表，我在空闲时间学习他们。

从编程问题里休息半小时来看你的抽认卡。

### 4. 专注

有很多的东西会让你分心浪费了宝贵的时间。专注和集中精力是很困难的。

## 在这里你看不到的内容

这些流行的技术不在这个学习计划里:

- SQL
- Javascript
- HTML, CSS, and other front-end technologies

## 每日计划

有些科目只要用一天的时间，但是有些将会花费很多天。有些只要学习而不用去做什么。

每天我都会从下面的列表中选取一个来做，看有关这个科目的视频，并且写一些有关的实现:
- C - 使用结构体和函数，该函数会接受一个结构体指针 * 及其他数据作为参数。
- C++ - 不使用内置的数据类型
- C++ - 使用内置的数据类型，如使用 STL 的 std::list 来作为链表。
- Python - 使用内置数据类型(持续联系 Python)
- 并且要写测试程序来保证自己做对了，有时候只要使用简单的 assert() 声明就可以了。
- 你也可以使用 Java 或者其它的语言，这个只是我的计划。

你并不需要这里所有的内容。你只需要  [一门用来面试的语言](#pick-one-language-for-the-interview).

为什么要使用所有的语言实现一次?
- 练习，练习，练习，直到我厌倦它，并且可以正确的完成它()
Practice, practice, practice, until I'm sick of it, and can do it with no problem (some have many edge cases and bookkeeping details to remember)
- Work within the raw constraints (allocating/freeing memory without help of garbage collection (except Python))
- Make use of built-in types so I have experience using the built-in tools for real-world use (not going to write my own linked list implementation in production)

I may not have time to do all of these for every subject, but I'll try.

You can see my code here:
 - [C](https://github.com/jwasham/practice-c)
 - [C++](https://github.com/jwasham/practice-cpp)
 - [Python](https://github.com/jwasham/practice-python)

You don't need to memorize the guts of every algorithm.

Write code on a whiteboard or paper, not a computer. Test with some sample inputs. Then test it out on a computer.

## Prerequisite Knowledge

- [ ] **Learn C**
    - C is everywhere. You'll see examples in books, lectures, videos, *everywhere* while you're studying.
    - [ ] [C Programming Language, Vol 2](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628)
        - This is a short book, but it will give you a great handle on the C language and if you practice it a little
            you'll quickly get proficient. Understanding C helps you understand how programs and memory work.
        - [answers to questions](https://github.com/lekkas/c-algorithms)

- [ ] **How computers process a program:**
    - [ ] [How does CPU execute program (video)](https://www.youtube.com/watch?v=42KTvGYQYnA)
    - [ ] [Machine Code Instructions (video)](https://www.youtube.com/watch?v=Mv2XQgpbTNE)

## Algorithmic complexity / Big-O / Asymptotic analysis
















## Reference
https://github.com/jwasham/coding-interview-university
