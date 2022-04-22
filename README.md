## Course Description

*Programming languages* are notations for describing computations to people and to machines. The world as we know it depends on programming languages, because all the software running on all the computers was written in some programming language. But, before a program can be run, it first must be translated into a form in which it can be executed by a computer.

The software systems that do this translation are called ***compilers***.

*This course is about how to design and implement compilers.* We shall discover that a few basic ideas can be used to construct translators for a wide variety of languages and machines. Besides compilers, the principles and techniques for compiler design are applicable to so many other domains that they are likely to be reused many times in the career of a computer scientist. The study of compiler writing touches upon programming languages, machine architecture, language theory, algorithms, and software engineering.



## Teaching Staff

### Instructor

Prof. **Lirong Wang**（王丽蓉）
  + Contact: wanglr@sdu.edu.cn
  + Office: Room 208-2, Building N3, Qingdao Campus, SDU


### Teaching Assistants

|TA|Responsibility|Contact|
|:-:|:-:|:-:|
|**Ruirui Zhang**（张芮睿）|Class 1|sherryzys@mail.sdu.edu.cn|
|**Zhe ZHANG**（张哲）|Class 2|201805130147@mail.sdu.edu.cn|
|**Lu CHEN**（陈路）|Class 3|chenlusdu@mail.sdu.edu.cn|
|**Jianing Qi**（亓佳宁）|Class 4|1059223346@qq.com|


## Time and Location

| Class |       Lecture Venue         |    Lab Venue     |   Time  |
| :---: | :-------------------------: | :--------------: | :-----: |
| 1 & 2 | Room N406, Zhensheng Garden | [to be announced] |10:10~12:00 MON. <br> 10:10~12:00 THUR.|
| 3 & 4 | Room N403, Zhensheng Garden | [to be announced] |14:00~15:50 MON. <br> 16:10~18:00 TUES.|


+ Course Duration: Week 1 to 17, Spring 2021.

+ Two lectures per week, lab starts from week 8.

+ 68 lecture hours in total, including 16 lab hours.

## Textbook and Resources

+ Textbook：

  + **《程序设计语言编译原理》**（第3版）

     *陈火旺 刘春林* 等编著， 国防工业出版社 [[PDF Download]](./pdf/books/textbook.pdf)

+ Recommended Reading Materials：
	
	+ **Compilers: Principles, Techniques, & Tools**  (Second Edition)
	
	  *Alfred V. Aho, Monica S. Lam, Ravi Sethi, & Jeffrey D. Ullman*. Addison-Wesley
	
	+ **Modern Compiler Implementation in Java**  (Second Edition)
	
	  *Andrew Appel and Jens Palsberg*. Cambridge University Press
	
+ Recommended Online Courses:
	
	+ **Compilers**  Stanford School of Engineering  [[Link]](https://online.stanford.edu/courses/soe-ycscs1-compilers)

+ Slides and Tutorials:
	
	+ Chapter1: Introduction to Compilers [[Slides Download]](./pdf/slides/chapter1_intro.pdf)
	+ Chapter2: High-level Language and Grammar Representation [[Slides Download]](./pdf/slides/chapter2_grammar.pdf)
	+ Chapter3: Lexical Analysis [[Slides Download]](./pdf/slides/chapter3_lexical.pdf)
	+ Chapter4: Syntax Analysis Top-Down Parsing [[Slides Download]](./pdf/slides/chapter4_syntax_top_down.pdf)
	+ Chapter5: Syntax Analysis Bottom-Up Parsing[[Slides Download]](./pdf/slides/chapter5_syntax_bottom_up.pdf)
	+ Chapter6: Syntax-Directed Translator
	+ Chapter7: Semantic Analysis and Intermediate Code Generation
	+ ... ...

## Assignments and Lab

| :warning: | WARNING: Plagiarism is definitely unacceptable in this course! All codes submitted will be examined through Stanford MOSS system. There will be severe consequences for those who have plagiarism detected! |
|:-:|:-:|
| :memo:    | **ATTENTION**: Do make sure to read the lab requirements before programming since your code will be judged by an **Auto-Grading System**. Detailed information will be announced soon. |

### Submission Guidelines

+ Assignment Submission:
  + Please upload the electronic version of your homework to **SDU Cloud**
    + Class 1 Link: https://icloud.qd.sdu.edu.cn:7777/link/C69B22D5CACF35FB7D354474E84B1832
    + Class 2 Link: https://icloud.qd.sdu.edu.cn:7777/link/5E550E9732313E9A1BBC1A128B80A7A8
    + Class 3 Link: https://icloud.qd.sdu.edu.cn:7777/link/2557995A2AF1D6816D6C21032E0D4825
    + Class 4 Link: https://icloud.qd.sdu.edu.cn:7777/link/F528DAAEC93BC115E12633C5E50AED21
  + Requirements：
  	+ Complete independently! You may discuss with your classmates, but DO NOT CHEAT!
  	+ Please upload in PDF format and name your file as "Assignment Number_Student ID_Student Name"
	+ Further details will be announced soon...
  + Delay：
    + Submissions for all assignments are open all across this semester 
    + Delay in submission will not affect your final score
  
+ Lab Submission:
  + **SDU OJ** for judging code correctness 
  + **GitHub Classroom** for submitting final project
    + Class 1 GitHub Classroom Link: https://classroom.github.com/a/3tf61T5v
    + Class 2 GitHub Classroom Link: https://classroom.github.com/a/w7xHvBC1
    + Class 3 GitHub Classroom Link: https://classroom.github.com/a/bIq-EZN0
    + Class 4 GitHub Classroom Link:

### Assignments

| Assignment |           Chapter           |     Due Date     |   PDF Download  |  Answer  |
| :--------: | :-------------------------: | :--------------: | :-------------: | :------: |
|1|Introduction to Compilers|[to be announced]|||
|2|Context-Free Grammar|[to be announced]|||
|3|Lexical Analysis|[to be announced]|||
|...|...||||


### Labs

+ Old version of lab requirements [[PDF Download]](./pdf/labs/lab-old.pdf)
+ Description of PL-0 Grammar

|  Lab  |           Content            | Suggested Time |              Requirements              |
| :---: | :--------------------------: | :------------: | :------------------------------------: |
| Lab 1 |       Lexical Analyzer       |    2 hours     | \[[PDF](./pdf/labs/lab-lexical.pdf)\]  |
| Lab 2 |       Syntactic Parser       |    4 hours     |  \[[PDF](./pdf/labs/lab-syntax.pdf)\]  |
| Lab 3 |         PL0 Compiler         |    6 hours     | \[[PDF](./pdf/labs/PL0-compiler.pdf)\] |
| Lab 4 | Integration & Report Writing |    4 hours     | \[[PDF](./pdf/labs/PL0-compiler.pdf)\] |




## Grading Policy

+ **Final Exam**：60%
+ **Labs**：30%
	+ Program Correctness (70%)
	+ Code style and tidiness (20%)
	+ Final Report (10%)
+ **Assignments**：10%
	+ Completion and Accuracy
+ **Bonus**：10%
	+ Note-sharing Project
	+ Research and Study Report
	+ Additional Features on Lab


## Discussions and Seminar

+ Discussion and QA Time：[to be announced]
+ Discussion and QA Venue：N3 Building, Shandong University Qingdao Campus
+ Seminar Information：[to be announced]


## Note-sharing Project

🎉🎉第一版笔记（初稿）下载 \[[PDF](./pdf/books/notes_first_edition.pdf)\]

+ 项目介绍：招募同学在学习过程中整理笔记，供其他同学及学弟学妹参考
+ 工作模式：每个核心知识点由至少2名同学共同整理，内容应包含该知识点总结与例题解析，以文档形式提交并在课程网站公开
+ 人员需求：预计招募**24**人，文字编辑与作图能力较强者优先，按**自愿报名**原则，**报满为止**
+ 报名方式：
  + 自*2021年3月11日（周四）*起开始接受报名
  + 为保证班级间公平，在*3月14日（周日）晚24点* 前，每班限报6人，有意参与者请联系本班助教
  + 3月15日公布剩余名额，剩余名额将不再按班级平均分配，可接受来自任意班级同学报名
+ 项目奖励：优秀笔记贡献者视情况给予奖励加分
+ 第一版笔记内容与编者：

|  章节  |            知识点            |         编写人员         |
| :----: | :--------------------------: | :----------------------: |
| 第3章  | 正则表达式转NFA转DFA及最小化 | 陈晓曦，米有麦彦，徐宏涛 |
| 第4章  |          LL(1)文法           |  朱可欣，薛宇涵，尹永琪  |
| 第5章  |  自下而上基本问题+算符优先   |   杜雅莉，徐容，孙书镇   |
| 第5章  |            LR文法            |  刘千一，黑乃磊，李博远  |
| 第6章  |      属性文法+语法制导       |        张倩，来苑        |
| 第7章  |         中间代码生成         |      牛庆莹，赵子涵      |
| 第9章  |      运行时存储空间组织      |      王新宇，尹浩飞      |
| 第10章 |             优化             |   张雨，王晨旭，赵雨晗   |
| 第11章 |         目标代码生成         |      王志睿，施博凡      |


![](./fig/Qingdao_gate.jpg)
