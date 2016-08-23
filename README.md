# kevent
实现事件驱动的超简洁代码库

这个并非原创，代码来之libev，我只是花时间把
libev的核心功能, event和timer两个模块, 独立出来，加一些简单的包装
供大家学习事件驱动的核心思想

再次感谢libev

# 编译
使用cmake

$ cd core

$ mkdir build

$ cd build

$ cmake -DCMAKE_BUILD_TYPE=Release ..

会在build目录生成 libevnet_core.so

通过修改cmake参数生成 libevnet_core.a

有问题请联系zwyyao@gmail.com

后续会开发一个基于kevent的rpc框架，敬请期待
