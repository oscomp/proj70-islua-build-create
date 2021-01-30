# proj70-islua-build-create

实现在容器内构建isula-build

### *描述* 

 目前isula-build 的构建是在主机侧直接使用golang进行构建，需要提供Dockerfile，采用`isula-build ctr-img build`进行构建

### *难度* 

易

### *导师* 

 @jingxiaolu

*联系方式*  lujingxiao@huawei.com

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

