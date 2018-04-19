## sourcetree 
### 准备工作
首先创建一个自己的分支出来，例如my-master
### 日常工作流程
假设主分支master 自己分支my-master
#### 上班第一件事就是从服务器拉取改动过的代码到本地合并
   * 检出master，抓取所有远端更新，然后选中最新节点合并
   * 检出自己分支，右击master，‘合并master到my-master‘(本地分支)这样合并代码就完成了
   * 确保已经切换至本地分支my-master然后开始工作
#### 下班最后一件事提交变更代码
  * 将需要提交的代码提交到本地分支my-master
  * 检出master,选择合并my-master到master
  * 将本地master合并到远端master,将不需要commit的文件或者需要解决冲突的文件丢弃(discard)掉
  * 没问题推送到远端
  * 检出my-master，选择master,合并master到my-master
#### 处理冲突
  ff

#### [参考文章](https://segmentfault.com/a/1190000005933855)
