# suse-turnserver-rpm
 turnserver适配suse系统，编译出rpm使用



源码来自：[coturn/rfc5766-turn-server: Import of https://code.google.com/p/rfc5766-turn-server/ (github.com)](https://github.com/coturn/rfc5766-turn-server)



该源码自带spec无法在suse下编译成功，修改spec以适配suse系统编译。

1. rpmbuild创建好目录

2. 将turnserver-3.2.5.9.tar.gz放到SOURCES下
3. 将turnserver-3.2.5.9.tar.gz压缩包中的rpm/turnserver.spec拷贝到SPECS下
4. 执行rpmbuild -bb ./SPECS/turnserver.spec编译

