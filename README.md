压缩包是本体
其中的redis的消费者组并没有自动创建，如果不手动创建可能会报错
redis运行以下代码创建
XGROUP CREATE stream.orders g1 0 MKSTREAM
