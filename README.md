﻿# wrk-load-testing-module
The wg/wrk extension tool provides continuous load testing in range of connection. Easy to find out the bottleneck and increase your web application performance. Using together with Jenkins are available via http call(curl to API). Understand your web application load characteristic in each number of connection.

* Latency
* Data-Transfer/Second
* Socket Error
* Non-2xx Response

### Require
* > 512 MB of RAM
* [wg/wrk](https://github.com/wg/wrk)
* [golang version > 1.5](https://golang.org/)

### Available
* Linux

### Install Instruction
* Install Golang
* Install wrk
```
git clone https://github.com/wg/wrk.git
cd wrk
make
```
can't wait ?
```
sudo apt-get install wrk
```
* Installation
```
go get github.com/tspn/wrk-load-testing-module
```

### Mode
* Test by case
* Realtime Test
* Soaking Test
* Estimate Function Capacity


