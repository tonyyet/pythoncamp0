# puzzle based learning


	这里主要是收录我在学习python过程当中遇到的一些源于实际生活的问题，以及我的求解过程及结果。我尽量把这些问题以谜题（puzzle）的形式呈现出来，希望这样可以[引起更大的兴趣](http://www.puzzlebasedlearning.edu.au/)，以及更容易记忆。
	2015.03.16 凌晨 始记于香港


## 问题一：怎样对一组数据进行随机分组？

问题源于开智python微课开课第一晚，我们六十多位学员要进行分组，分到9个小组里。假如是在传统课堂的话，最简单而且应该也是最常用的方法就是叫大家报数，从一报到九，然后再重复。不过由于所有学员遍及大江南北，无法面对面报数。所以需要找到一个可以用作代理的符号，以资识别。

最后是先选出9个组长，然后再对剩余的学员按照其填报资料的顺序来排列，每九个就一次循环。

所以其实这个做法跟在实体环境下进行报数的原理还是一样的。应该可以用程序来实现。要争取早日把这样的程序写出来。

另外分组的这个事件还引发我思考到底有没有真正意义上的随机这个问题。还有，所谓随机到底意味着什么？它有数学上的解释吗？

随便Google了一下，发现MIT电机工程系的一个[计算机科学入门课](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00sc-introduction-to-computer-science-and-programming-spring-2011/unit-2/lecture-16-using-randomness-to-solve-non-random-problems/)就有讲到这个，看来要找时间去认真看看。

---

题外话：

之前有听说过一家做网上票务的公司，他们为了减轻现场验票工作人员的负担（尤其是在人流大的时候），所以就给每一张电子票设定了独特的颜色组合，而由于一个城市里每天在使用中的票的总数不过数千，其实也比较容易控制。
