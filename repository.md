Git是一个分布式版本管理系统，记录一个文件从时间维度上的变化，可以更好地管理 linux 内核。

### repository 仓库

---

存储一个文件和目录时间维度上的变化

![https://backlog.com/git-tutorial/cn/img/post/intro/capture_intro1_2_1.png](https://backlog.com/git-tutorial/cn/img/post/intro/capture_intro1_2_1.png)



- 远程数据库：为了和多人共享而建立的数据库
- 本地数据库：为了方便自己使用而建立的本地数据库



![](https://backlog.com/git-tutorial/cn/img/post/intro/capture_intro1_2_2.png)

### 修改记录——提交

提交是以时间顺序保存到数据库中的。凭借该提交和最新的文件状态，就可以知道过去的修改记录以及内容。

![](https://backlog.com/git-tutorial/cn/img/post/intro/capture_intro1_3_1.png)

![](https://backlog.com/git-tutorial/cn/img/post/intro/capture_intro1_4_1.png)

凭借中间的索引，可以避免工作树中不必要的文件提交，还可以将文件修改内容的一部分加入索引区域并提交。

