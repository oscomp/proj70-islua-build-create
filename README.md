# proj70-islua-build-create

实现在容器内构建isula-build

### *描述* 

 目前isula-build 的构建是在主机侧直接使用golang进行构建，需要提供Dockerfile，采用`isula-build ctr-img build`进行构建

### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

 @jingxiaolu

*联系方式*  lujingxiao@huawei.com

### 难度

易

### License

- MulanPSL v2

### *项目产出标准*

- 编写用于构建 isula-build 的 Dockerfile，并推送至 isula-build 源码仓
- 集成至 isula-build 的 Makefile 里

### *技术要求*

1. Dockerfile 语法
2. Docker 制作镜像，推送镜像等基本操作

### *相关项目*

1. https://gitee.com/openeuler/isula-build

### *相关资料*


1. https://docs.docker.com/engine/reference/commandline/build/
2. https://github.com/moby/moby/blob/master/Dockerfile
3. https://github.com/moby/buildkit/blob/master/Dockerfile

