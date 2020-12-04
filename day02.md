### 01-开源相关的概念-了解开源和闭源的概念（1分钟

- 开源，开放源代码
- 闭源，不开放源代码

### 02-开源相关的概念-开源许可协议（3分钟

- GPL，具有传染性，不允许修改后和衍生的代码作为闭源的商业发布和销售
- MIT，限制最少的协议，修改的代码中需要包含原作者的许可信息
  - jQuery
  - Node.js

### 03-开源相关的概念-为什么要拥抱开源（2分钟

- 更多的控制权
- 学习更容易
- 真正的安全

### 04-开源相关的概念-了解什么是开源项目托管平台（2分钟

- 免费存放开源项目源代码的网站
  - github
  - gitlab
  - gitee

### 05-开源相关的概念-什么是GitHub（5分钟

- 世界最大的开源项目托管平台

### 06-github-注册GitHub账号（4分钟

- 注册账号
  - Sign up

### 07-github-新建空白远程仓库（4分钟

- New respositroy
- 填写信息
- Create

### 08-github-远程仓库的两种访问方式（3分钟

- HTTPS
  - 零配置，需要重复输入账号密码
- SSH
  - 额外配置，成功后，不需要重复输入账号密码

### 09-github-基于HTTPS将本地仓库上传到GitHub（6分钟

- HTTPS路径复制
- git remote add ……
- git push -u origin master

### 10-github-了解git push命令的作用（4分钟

- git push，将本地仓库的最新代码推送到远程仓库

### 11-github-生成SSH Key（4分钟

- 加密传输
  - id_rsa
  - id_rsa.pub
- ssh-keygen -t rsa -b 4096 -C "邮箱"
- 用户下有 ssh 目录

### 12-github-配置SSH Key（4分钟

- setting - SSH and …… - New SSH Key

### 13-github-检测SSH Key是否配置成功（2分钟

- ssh -T git@github.com
- yes
- Hi ……

### 14-github-基于SSH将本地仓库上传GitHub（6分钟

- git remote ……
- git push ……

### 15-github-将远程仓库克隆到本地（4分钟

- git clone ……

### 16-分支-了解分支的概念以及分支的作用（4分钟

- 平行宇宙
- 合并
- 多人协作开发

### 17-分支-master主分支（2分钟

- 默认创建的 master 主分支

### 18-分支-功能分支（3分钟

- 开发新功能的分支，从master主分支上分出来的

### 19-分支-查看分支列表（2分钟

- git branch

### 20-分支-创建新分支（4分钟

- git branch [名字]

### 21-分支-切换分支（3分钟

- git checkout [名字]

### 22-分支-快速创建和切换分支（4分钟

- git checkout -b [名字]

### 23-分支-合并分支（8分钟

- git checkout master
- git merge login

### 24-分支-删除分支（3分钟

- git branch -d [名字]

### 25-分支-遇到冲突时的分支合并（9分钟

- 手动解决

### 26-分支-将本地分支推送到远程分支（5分钟

- git push -u ……

### 27-分支-查看远程分支列表（2分钟

- git remote show [远程仓库名字]

### 28-分支-跟踪分支（6分钟

- 从远程下载分支

  - git checkout [远程分支名字]

  - git checkout -b reg origin/register

### 29-分支-拉去远程分支最新代码（4分钟

- git pull

### 30-分支-删除远程分支（6分钟

- git push [远程仓库名字] --delete [远程分支名字]

### 31-总结（2分钟

- GitHub
  - 配置SSH
  - 本地仓库上传Github
- 分支
  - 创建分支：git checkout -b 新分支名字
  - 第一次上传远程分支：git push -u origin 新分支名字
  - 切换分支：git checkout 分支名字
  - 查看分支：git branch

