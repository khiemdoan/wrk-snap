# wrk - a HTTP benchmarking tool

wrk is a modern HTTP benchmarking tool capable of generating significant
load when run on a single multi-core CPU. It combines a multithreaded
design with scalable event notification systems such as epoll and kqueue.

An optional LuaJIT script can perform HTTP request generation, response
processing, and custom reporting. Details are available in SCRIPTING and
several examples are located in [scripts/](https://github.com/wg/wrk/tree/master/scripts/).

<p align="center"><b>This is the snap for <a href="https://github.com/wg/wrk">wrk</a>.</b> It works on Ubuntu, Fedora, Debian, and other major Linux distributions.</p>

<p align="center">Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with :gift_heart: by Khiem Doan</p>

## Install

```bash
$ sudo snap install wrk
```
