# torrent

[![NPM](https://nodei.co/npm/torrent.png?global=true)](https://nodei.co/npm/torrent/)

Download torrents from the command line

## usage

```
torrent <magnet link OR path to .torrent file>
```

e.g. to download ubuntu 14.04 ISO

```
torrent "magnet:?xt=urn:btih:4d753474429d817b80ff9e0c441ca660ec5d2450&dn=Ubuntu+14.04+64+bit&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A80&tr=udp%3A%2F%2Ftracker.publicbt.com%3A80&tr=udp%3A%2F%2Ftracker.istole.it%3A6969&tr=udp%3A%2F%2Fopen.demonii.com%3A1337"
```

or via .torrent file:

```
torrent ubuntu-14.04.iso.torrent
```

it will print progress:

```
$ torrent ubuntu-14.04.iso.torrent
1 file(s) in torrent
ubuntu-14.04.iso
Connected to 35/37 peers
Downloaded 5.47 MB (1.09 MB/s) with 0 hotswaps
Uploaded 0 B (0 B/s)
```