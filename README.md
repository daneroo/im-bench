# im-bench

We would like to gather a set of simple baseline benchmarks.

First up, measuring raw file-io throughput for sequetial access, to benchamark SSD drive speed.


## ADATA-S510

### Thunderbolt:

    node-io.js 16G W:355MB/s R:214MB/s
    AJA-SystemTest Disk Read/Write (16G) W: 296MB/s R:298MB/s
    XBench W:200MB/s R:188MB/s
    BlackMagick Disk Speed W:105MB/s R:180MB/s

### infoZone  usb3-sata-6G:

    node-io.js 16G W:271MB/s R:260MB/s
    AJA-SystemTest Disk Read/Write (16G) W: 242MB/s R:242MB/s
    XBench W:189MB/s R:186MB/s
    BlackMagick Disk Speed W:105MB/s R:134MB/s


### BYTECC USB3 (SATA II):