1. promise

2.因为 NodeJs 执行是单线程的，如果执行 CPU 密集的任务就会阻塞后续代码，且单线程无法充分利用 CPU 多核资源。而异步 I/O 是多线程的，在工作线程上执行，不会阻塞执行线程。当然 NodeJS 也可以通过 child_process 等方式，启用多进程或多线程来处理 CPU 密集型的任务，但相比其它成熟的方案并没有任何优势。

3.

4.karma、jasmine
  mocha

5.

6.