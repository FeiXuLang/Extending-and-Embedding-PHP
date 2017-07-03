# 1.1 一切从SAPI开始

PHP有 **4** 种常见的运行模式

* CGI
* Fast-CGI
* Apache
* CLI

***PS：需要注意的是CGI与Fast-CGI的区别***




Though it may look very different, the CLI binary actually behaves just the same way. A php command, entered at
the system prompt starts up the "command line sapi," which acts like a miniweb server designed to service a single
request. When the script is done running, this miniPHP-web server shuts down and returns control to the shell.


尽管从形式上看起来很不一样，但任何的PHP进程都是从SAPI开始的。
SAPI可以看做一个迷你版的web服务器
一个php命令，



参考文章：

* [php的4种常见运行方式](http://www.jb51.net/article/62554.htm)




