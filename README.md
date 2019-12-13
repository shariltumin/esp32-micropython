# Micropython on esp32.

**LATEST** - The latest is under firmware/20191213 - MicroPython v1.11-665-gfb0141559-kaki5

The firmware include LittleFS.

You can use LittleFS instead of FatFS(default) by doing these in REPL:

```
>>> import os
>>> os.VfsLfs2.mkfs(bdev)

```


You can download [custommade.zip](https://github.com/shariltumin/esp32-cam-micropython/blob/master/custommade.zip) and read [this blog](https://kopimojo.blogspot.com/2019/12/custom-made-sometimes-it-is-nice-to-be.html) to build custom made firmware.


The [firmware](https://github.com/shariltumin/esp32-micropython/tree/master/firmware) was compiled without web-repl, upip, and help modules.

Read [my blog](https://kopimojo.blogspot.com/).
