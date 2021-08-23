# Table of contents

* [旨在快速讲解docker的一些易错点和基础](README.md)
* [1.容器和vm](1.container-and-vm/README.md)
  * [cgroup和namespaces](1.container-and-vm/1.1cgroup-and-namespaces.md)
  * [安装docker](1.container-and-vm/1.2.install-docker.md)
  * [Hello World](1.container-and-vm/1.3.hello-world.md)
  * [为什么docker搞了个镜像的东西](1.container-and-vm/1.4.why-docker-create-docker-images.md)
  * [容器 vs VM](1.container-and-vm/1.5.container-vs-vm.md)
* [2.docker镜像](2.docker-image/README.md)
  * [镜像是分层的](2.docker-image/2.1.images-layers.md)
  * [容器是单独一层读写层](2.docker-image/2.2.container-is-a-single-layer.md)
  * [构建Docker镜像](2.docker-image/2.3.create-docker-images.md)
  * [Dockerfile](2.docker-image/dockerfile/README.md)
    * [FROM](2.docker-image/dockerfile/from.md)
    * [MAINTAINER](2.docker-image/dockerfile/maintainer.md)
    * [ENV](2.docker-image/dockerfile/env.md)
    * [ARG](2.docker-image/dockerfile/arg.md)
    * [RUN](2.docker-image/dockerfile/run.md)
    * [COPY](2.docker-image/dockerfile/copy.md)
    * [ADD](2.docker-image/dockerfile/add.md)
    * [WORKDIR](2.docker-image/dockerfile/workdir.md)
    * [USER](2.docker-image/dockerfile/user.md)
    * [ONBUILD](2.docker-image/dockerfile/onbuild.md)
    * [EXPOSE](2.docker-image/dockerfile/expose.md)
    * [CMD--与进程前后台和容器存活的关系](2.docker-image/dockerfile/cmd.md)
    * [ENTRYPOINT](2.docker-image/dockerfile/entrypoint.md)
    * [VOLUME](2.docker-image/dockerfile/volume.md)
    * [STOPSIGNAL--与信号转发](2.docker-image/dockerfile/stopsignal.md)
    * [exec与entrypoint使用脚本](2.docker-image/dockerfile/exec-and-entrypoint.md)
    * [使用 buildx 构建多平台 Docker 镜像](2.docker-image/dockerfile/shi-yong-buildx-gou-jian-duo-ping-tai-docker-jing-xiang.md)
    * [特权构建镜像](2.docker-image/dockerfile/te-quan-gou-jian-jing-xiang.md)
  * [如何构建标准且人性化镜像](2.docker-image/great-images.md)
* [3.容器无法运行排错](3.container-cannot-run.md)
* [4.运行中的问题](4.errors-while-running.md)
* [5.数据持久化](5.how-to-keep-data.md)
* [6.容器网络](6.container-network/README.md)
  * [bridge](6.container-network/bridge.md)
  * [host](6.container-network/host.md)
  * [container](6.container-network/container.md)
  * [none](6.container-network/none.md)
  * [init层与过时的--link](6.container-network/guo-shi-de-link-yu-init-ceng.md)
  * [容器互联](6.container-network/container-network-interconnected.md)
* [7.编排利器docker-compose](docker-compose.md)
* [8.一些使用和配置问题](some-conf-in-use.md)
