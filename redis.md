Redis 是什么？
    可以直接对内存进项操作的软件。作用就是提高性能。
        1.    可以做持续化
            -    AOF    一段时间后把数据写入硬盘
            -    RDB    实时写入数据

        2.    相当于内存中的 大字典

        3.    单进程 单线程 的应用 但是性能很快的
    要使用链接池来提高效率。
    
redis 存储数据时， 数量上限和超时时间至少要有一个，否做存在恶意攻击。

redis的列表没有scan_iter 所以需要自定义生成器