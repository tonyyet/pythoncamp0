# 迷人的 github 



## 1. 我与 github 的一段缘

记得我第一次知道 github 是2010年的时候。那时候我在一家公益领域的创业公司工作，我们当时想做一个网站，负责技术的同事当时决定用ruby on rails来写这个网站。也写得蛮快的，一个月不到就写出了个大致的框架。当时我也很惊讶，怎么可以这么快做出来呢？

后来有一天问他，才知道原来他有很多东西是采用了（嗯，准确的是也许是 fork 了）别人的开源代码，他只需要根据项目的实际需要去做出必要的修改。第一版的网站其实挺多bug的，我问他是不是有类似bugzilla那样的平台可以提交错误报告。然后他就给我看当时已经放到 github 的我们的项目网站。

当时我没有看懂，也没有深入去了解到底 github 是何方神圣，居然可以捕获一个年轻的小伙子的灵魂（嗯，我这位同事的编程技巧也是半路出家自学的）。

直到后来我发现有不少人在用一些很奇特的方式制作他们的幻灯片（slides），并且这些「奇特的制作方式」的源代码都是托管在github上面，我才认真去看，然后才发现了这个神奇的世界。


## 2. github 使用三部曲（add, commit, push, pull request）

记得当初刚开始用 github 的时候，感觉很不熟悉，什么push, pull, commit那些完全不懂。后来看了几个git的使用教程之后，慢慢明白了，原来作为初学者，你只需要懂得三个命令就可以了。它们分别是：

git add：告诉git你要把最近修改过的代码添加到代码仓库（我一般直接用 "git add ."，这样可以一次过把当前目录以及所有子目录的修订通通都添加进去 ）
git commit：确认你要把这些修订添加到代码仓库
git push：将这些修订推送到远端的服务器

到后面更熟悉一些之后，还有第四个比较神奇的命令，就是 pull request，就是当你在和别人通过git来合作编写代码或者任何文本的东西，并且你还没有commit的权限的时候，你可以通过pull request告诉你的合作伙伴，说我做了这个修订，你看看管不管用，管用的话你就采纳。据说很多人就是通过pull request成为某些开源项目的贡献者的。

## 3. github vs git

初学者有时候会把 github 和 git 混为一谈。事实上它们是两个东西。git是一种管理代码历史版本的方式，跟它类似的还有subversion, 等等。而github则是一个代码托管的平台，因为它对git的支持非常好，所以很多人会用github来托管自己的代码，并且在github上面与其他人合作来完成一些软件乃至其他文本性质的项目。

假如你想学会怎么用git，可以看 [Pro Git](https://progit.org/) 这本书。


## 4. github 上的神奇repo

既然讲到github，那当然不能不提上面的一些神奇的repo。以下是我知道的一些较为有趣的项目，大家不妨参考一下：

[Bloomberg-Beta Operating Manual](https://github.com/Bloomberg-Beta/Manual)

[《连线杂志Wired》也曾在github上发表过关于github的文章](http://www.wired.com/2012/02/github-revisited/)

[德国政府的宪法及法律](https://github.com/bundestag/gesetze)


现在其实github官方有专门的政府机构页面，从他们列出来的清单看，大多数欧美国家的政府都有用github来推进他们自身的政府信息公开的进程，有些你甚至还可以参与到法律制订的讨论过程当中去呢。

假如你还想知道更多，不妨试一试在 github.com 那里去搜索 beer, recipe, farmer 或者其他任何你感兴趣的话题，说不定真的会有惊喜呢。

## 5. github 团队如何用 github 来协作创建 github 

这是github团队早期员工 [Zach Holman](http://zachholman.com/about) 多年前的[一个演讲](http://zachholman.com/talk/how-github-uses-github-to-build-github/)，讲的是很meta的东西，但从中可以看出github的无比威力。Zach 还写过一篇文章讲[为什么github是一家很cool的公司](http://zachholman.com/posts/how-github-works-creativity/)，有兴趣的话也可以看看。