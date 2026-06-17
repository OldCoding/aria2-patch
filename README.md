此为aria2和ariang的补丁
max-connection-per-server
    将最大线程数16 修改为1024

min-split-size
    最小文件分片大小从1m修改为64k

piece-length
    文件分片大小从1m修改为64k

把010-increase-max-connections-and-reduce-split-size.patch补丁放到feeds/packages/net/aria2/patches下

把Makefile放到feeds/packages/net/ariang下替换原有Makefile