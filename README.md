#######
xennet front hotfix 例子，主要是实时替换这alloc_rx_buffer这个函数

你可以根据这个方法，实时替换某个函数，这样
在有问题的时候，你就可以通过这种方法来打印一些信息，
或者FIX BUG。

说明：这种方法必须是linux 2.6.32以上内核才可以，本例子在
3.10.0-123.9.3.el7.x86_64 测试成功