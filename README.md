# Collections
Contains interesting code collected from the web.

Assembly
=========

<a href="https://github.com/chenx/Collections/tree/master/Assembly/bootchess">BootChess</a>
-------------
The smallest chess game (2015, by Olivier Poudade), in 487 bytes, uses 512 bytes of memory, breaks 32-year-old record of the 1K ZX Chess (1982, by David Horne, Sinclair ZX81, 672 bytes, uses 1KB memory). Capable of running on Windows, Linux, OS X, and BSD. 

More readings:  
[1] http://www.geek.com/games/computer-chess-created-in-487-bytes-breaks-32-year-old-record-1614445/  
[2] http://mashable.com/2015/01/30/play-it-better-tiny-chess-game/  
[3] <a href="http://olivier.poudade.free.fr/">Olivier Poudade's Assembly language page</a>  

Download link: http://olivier.poudade.free.fr/src/BootChess.asm

C
=========

<a href="https://github.com/chenx/Collections/tree/master/C/webbench-1.5">Webbench</a>
-----------
A simple website stress testing tool. It uses fork to simulate multiple clients to connect to a website for stress testing. Max is over 30,000 simutaneous connections. Written is less than 600 lines of C. 

Download link: http://home.tiscali.cz/~cz210552/webbench.html

<a href="https://github.com/chenx/Collections/tree/master/C/tinyhttpd-0.1.0">Tinyhttpd</a>
-----------------
A super light-weighted Http Server. Only 502 lines of C (including comments, and a simple client). Reading this helps to understand the very essense of a Http Server. 

Download link: http://sourceforge.net/projects/tinyhttpd/

<a href="https://github.com/chenx/Collections/tree/master/C/cJSON">cJSON</a>
-------------------
A light-weighted JSON encoder/decoder in C. About 500 lines of C. Function is not so strong, but small and fast, easy to understand, well maintained. 

A Github site: https://github.com/kbranigan/cJSON  
Download link: http://sourceforge.net/projects/cjson/

<a href="https://github.com/chenx/Collections/tree/master/C/cmockery-0.1.2">CMockery</a>
-------------------------
A light-weighted C unit test framework. Independ from other open source package. Non-invasive for the code to be tested. Less than 3000 lines of C. Avoid complex compiler feature, so compatible with older versions of compilers. Does not require tested code to conform to C99 standard, thus useful to embed applications.

A Github site: https://github.com/lpabon/cmockery2  
Download link: http://code.google.com/p/cmockery/downloads/list

Libev
----------
Libev is an open source event-driven programmng library, based on epoll, kqueue etc. It is highly effecient, and combines IO event, timer and signal into the framework of event processing. It is based on Reactor pattern, and is a good resource to learn about event-driven programming. Version 4.15 has about 8000 lines of C.

Download link: http://software.schmorp.de/pkg/libev.html

Memcached
---------------
Memcached is a highly efficient distributed memory cache system. It is used in dynamic web applications to alleviate database load. It is based on key-value hashmap. Version 1.4.7 has about 10,000 lines of code in C.

Github site: https://github.com/memcached  
Download link: http://memcached.org/

Lua
----------
Lua is written in 100% ANSI C. Version 5.1.4 has about 15,000 lines of code, or about 10,000 lines without blank and comment lines.

Github site: https://github.com/LuaDist/lua  
Download link: http://www.lua.org/

SQLite
------------

SQLite is an open source embed relational database. It is self-contained, requries zero setting, supports transactions. Highly portable, easy to use, compact, effecient, reliable. It has about 25,000 lines of code.

A Github site: https://github.com/smparkes/sqlite  
Download link: http://www.sqlite.org

UNIX v6
-----------
The kernel of UNIX v6 has about 10,000 lines of code, including device drivers. In comparison, recent Linux kernel has more than 10 million lines of code. 

A Github site: https://github.com/hephaex/unix-v6  
Download link: http://minnie.tuhs.org/cgi-bin/utree.pl?file=V6

NetBSD
---------------------
NetBSD is a free, highly portable UNIX-like operating system. It claims portable to the most number of systems, from 64bit alpha to hand-held/mobile and embed devices. The NetBSD project slogan is: "Of course it runs NetBSD". 

A Github site: https://github.com/ebijun/NetBSD  
Download link: http://www.netbsd.org/



References:
=============

<ul>
<li><a href="http://my.oschina.net/zhoukuo/blog/335788#OSC_h3_2">最值得阅读学习的 10 个 C 语言开源项目代码</a></li>
</ul>
