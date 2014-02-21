## About cvlc-streaming
Simple bash script to help with cvlc streaming. The idea is to take local multicast
stream and transcode it. The output is HTTP stream.

## Checking out the source

* $ mkdir /path/to/src
* $ cd /path/to/src
* $ git clone https://github.com/zdr1976/cvlc-streaming.git

## Usage
You can use cvlcs as show below

```
Usage: ./cvlcs [-CDtsf] [-c <channel number>] [-p <port>] [-b <rate>] [-a <rate>]
    -C  List available tv channels
    -D  Do not perform de-interlacing
    -t  Transcode stream to h264
    -s  Scale stream to half size
    -f  Full stream (All audioi languages, teletext, ..)
    -c  TV channel number (default=1)
    -p  Listening streaming port (default=3389)
    -b  video bitrate kb/s (default=1024)
    -a  audio bitrate kb/s (default=128)
```
