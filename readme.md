# Getting the Ubuntu Call
It's snipped from the Ubuntu 13.10 AMD64 installer.  Pretty cool, huh?

```sh
head -c 473500 ubuntu-13.10-desktop-amd64.iso | tail -c 27000 > ubuntu.pcm
avconv -f s16le -ar 9.001k -ac 2 -i ubuntu.pcm ubuntu.wav
```

<!-- vim: set ft=markdown : -->
