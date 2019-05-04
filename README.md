# EnFuzzer

Tool for ensemble fuzzing, it works across most Linux distributions. So far, Enfuzzer has passed all the testcases and worked well on ubuntu, archlinux, centos, debian, fedora, gentoo and opensuse.

The latest version of enfuzzer was moved to http://wingtecher.com/Enfuzz/.

![image](https://github.com/131250106/enfuzzer/blob/master/example/image/step1.PNG)

The detail use of Enfuzz Server can be found in https://github.com/131250106/enfuzzer/tree/master/example.


## CVE list

| CVE ID | Projects  | CVE type |
| :------------ |:---------------:|:---------------:|
|[CVE-2018-11097](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11097)	|   cstring	      |Memory leak      |
|[CVE-2018-11212](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11212)	|   libjpeg	      |Divide-by-zero error      |
|[CVE-2018-11213](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11213)	|   libjpeg	      |Segmentation fault      |
|[CVE-2018-11214](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11214)	|   libjpeg	      |Segmentation fault      |
|[CVE-2018-11363](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11363)	|   PDFGen	      |Heap buffer overflow      |
|[CVE-2018-11364](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11364)	|   ReadStat	    |Memory leak      |
|[CVE-2018-11365](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11365)	|   ReadStat	    |Infinite loop      |
|[CVE-2018-11468](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11468)	|   discount	    |Heap buffer overflow      |
|[CVE-2018-11503](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11503)	|   discount	    |Heap buffer overflow      |
|[CVE-2018-11504](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11504)	|   discount	    |Heap buffer overflow      |
|[CVE-2018-11536](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11536)	|   md4c  	      |Heap buffer overflow      |
|[CVE-2018-11545](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11545)	|   md4c  	      |Heap buffer overflow      |
|[CVE-2018-11546](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11546)	|   md4c  	      |Heap buffer overflow      |
|[CVE-2018-11547](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11547)	|   md4c  	      |Heap buffer overflow      |
|[CVE-2018-11813](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-11813)	|   libjpeg       |	Large loop               |
|[CVE-2018-12064](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-12064)	|   tinyexr  	    |Heap buffer overflow      |
|[CVE-2018-12092](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-12092)	|   tinyexr  	    |Heap buffer overflow      |
|[CVE-2018-12093](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-12093)	|   tinyexr  	    |Memory leak      |
|[CVE-2018-12108](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-12108)	|   lepton  	    |SIGFPE           |
|[CVE-2018-12109](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-12109)	|   FLIF    	    |Heap buffer overflow      |
|[CVE-2018-12495](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-12495)	|   tinyexr       |Heap buffer overflow      |
|[CVE-2018-12503](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-12503)	|   tinyexr       |Heap buffer overflow      |
|[CVE-2018-12504](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-12504)	|   tinyexr  	    |Assert failure      |
|[CVE-2018-12687](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-12687)	|   tinyexr  	    |Assert failure      |
|[CVE-2018-12688](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-12688)	|   tinyexr  	    |Segmentation fault      |
|[CVE-2018-13030](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13030)	|  jpeg-compressor|Stack buffer overflow      |
|[CVE-2018-13037](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13037)	|  jpeg-compressor|Stack buffer overflow      |
|[CVE-2018-13419](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13419)	|  libsndfile     |Memory leak      |
|[CVE-2018-13420](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13420)	|  gperftools     |Buffer overflow            |
|[CVE-2018-13421](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13421)	|  fast-cpp-csv-parser|Buffer overflow      |
|[CVE-2018-13794](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13794)|cat-image|Buffer overflow|
|[CVE-2018-13795](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13795)|gravity|Endless loop|
|[CVE-2018-13833](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13833)|cmft|Stack buffer overflow|
|[CVE-2018-13843](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13843)|htslib|Memory Leak|
|[CVE-2018-13844](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13844)|htslib|Memory Leak|
|[CVE-2018-13845](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13845)|htslib|Buffer overflow|
|[CVE-2018-13846](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13846)|Bento4|Buffer overread|
|[CVE-2018-13847](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13847)|Bento4|SEGV|
|[CVE-2018-13848](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13848)|Bento4|SEGV|
|[CVE-2018-13996](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13996)|genann|Stack buffer overflow|
|[CVE-2018-13997](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-13997)|genann|SEGV|
|[CVE-2018-14047](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14047)|pngwriter|SEGV|
|[CVE-2018-14048](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14048)|libpng|SEGV|
|[CVE-2018-14049](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14049)|libwav|SEGV|
|[CVE-2018-14050](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14050)|libwav|SEGV|
|[CVE-2018-14051](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14051)|libwav|infinite loop|
|[CVE-2018-14052](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14052)|libwav|SEGV|
|[CVE-2018-14072](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14072)|libsixel|Memory leak|
|[CVE-2018-14073](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14073)|libsixel|Memory leak|
|[CVE-2018-14521](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14521)|aubio|SEGV signal|
|[CVE-2018-14522](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14522)|aubio|SEGV signal|
|[CVE-2018-14523](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14523)|aubio|Global buffer overflow|
|[CVE-2018-14531](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14531)|Bento4|Buffer Overflow|
|[CVE-2018-14532](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14532)|Bento4|Buffer Overflow|
|[CVE-2018-14549](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14549)|libwav|SEGV|
|[CVE-2018-14550](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14550)|libpng|Stack buffer overflow|
|[CVE-2018-14562](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14562)|THULAC|SEGV|
|[CVE-2018-14563](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14563)|THULAC|alloc-dealloc-mismatch|
|[CVE-2018-14564](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14564)|THULAC|SEGV|
|[CVE-2018-14565](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14565)|THULAC|Heap buffer overflow|
|[CVE-2018-14584](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14584)|Bento4|Buffer overflow|
|[CVE-2018-14585](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14585)|Bento4|Buffer overflow|
|[CVE-2018-14586](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14586)|Bento4|SEGV|
|[CVE-2018-14587](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14587)|Bento4|Buffer overflow|
|[CVE-2018-14588](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14588)|Bento4|SEGV|
|[CVE-2018-14589](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14589)|Bento4|Heap buffer overflow|
|[CVE-2018-14590](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14590)|Bento4|SEGV|
|[CVE-2018-14736](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14736)|pbc|Buffer overflow|
|[CVE-2018-14737](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14737)|pbc|SEGV|
|[CVE-2018-14738](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14738)|pbc|SEGV|
|[CVE-2018-14739](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14739)|pbc|SEGV|
|[CVE-2018-14740](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14740)|pbc|SEGV|
|[CVE-2018-14741](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14741)|pbc|SEGV|
|[CVE-2018-14742](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14742)|pbc|SEGV|
|[CVE-2018-14743](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14743)|pbc|SEGV|
|[CVE-2018-14744](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14744)|pbc|Use after free|
|[CVE-2018-14944](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14944)|jpeg_encoder|SEGV|
|[CVE-2018-14945](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14945)|jpeg_encoder|heap buffer overflow|
|[CVE-2018-14946](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14946)|pdf2json|Alloc_dealloc_mismatch|
|[CVE-2018-14947](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14947)|pdf2json|Alloc_dealloc_mismatch|
|[CVE-2018-14948](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-14948)|sound|Alloc-dealloc-mismatch|
|[CVE-2018-16781](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-16781)|ffjpeg|FPE signal|
|[CVE-2018-16782](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-16782)|imageworsener overflow|
|[CVE-2018-17042](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-17042)|dbf2txt|infinite loop	|
|[CVE-2018-17043](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-17043)|doc2txt|heap buffer overflow	|
|[CVE-2018-17072](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-17072)|json|buffer over-read	|
|[CVE-2018-17073](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-17073)|bitmap|NULL pointer dereference|
|[CVE-2018-17093](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-17093)|xar|NULL pointer dereference	|
|[CVE-2018-17094](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-17094)|xar|SEGV|
|[CVE-2018-17095](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-17095)|xar|Heap buffer overflow|
|[CVE-2018-17338](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-17338)|pdfalto|heap buffer overflow	|
|[CVE-2018-17427](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-17427)|simdcomp|heap buffer overflow	|
|[CVE-2018-17854](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-17854)|simdcomp|heap buffer overflow	|
|[CVE-2018-18581](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-18581)|LuPng|heap buffer overflow	|
|[CVE-2018-18582](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-18582)|LuPng|heap buffer overflow	|
|[CVE-2018-18583](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-18583)|LuPng|heap buffer overflow	|
|[CVE-2018-18834](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-18834)|libiec61850|heap buffer overflow	|
|[CVE-2018-18937](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-18937)|libiec61850|SEGV	|
|[CVE-2018-19093](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-19093)|libiec61850|SEGV	|
|[CVE-2018-19121](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-19121)|libiec61850|SEGV	|
|[CVE-2018-19122](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-19122)|libiec61850|SEGV	|
|[CVE-2018-19184](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-19184)|geth|SEGVh|
|[CVE-2018-19185](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-19185)|aleth|Failure of transaction		|
|[CVE-2018-19330](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-19330)|mxml|detected memory leaks	|
|[CVE-2018-19764](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-19764)|mxml|stack buffer overflow		|
|[CVE-2018-20004](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-20004)|mxml|heap-use-after-free		|
|[CVE-2018-7705](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-7705)|linux-kernel_3.10|memory leak			|
|[CVE-2018-7706](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-7706)|linux-kernel_3.10|memory leak			|
|[CVE-2018-7707](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-7707)|linux-kernel_3.10|memory leak			|
|[CVE-2018-7708](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-7708)|linux-kernel_3.10|memory leak			|
|[CVE-2018-7709](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-7709)|linux-kernel_4.20|invalid free		|	

## Install
To install our EnFuzzer, you can just execute in shell:
```sh
./install
```

Arch Linux and Ubuntu 16.04 are tested, but it should work on other Linux distributions. Please configure the `PATH` environment variable in your shell first, to include `/opt/enfuzzer/`.

Execute in shell:

```sh
export PATH="/opt/enfuzzer:$PATH"
```


Or you can directly insert the content above in configuration files such as `~/.bashrc`.


### Configure and Build

Enfuzzer also provide a easy used interface for building process, you can build your project by execute in shell:
```sh
Enfuzzer build -gz xxx.tar.gz
```
then it will automatically build three binary — one pure binary with no instrumentation for Radamsa; one binary built with afl-gcc for AFL; one binary built with sanitizer for libFuzzer.

You can also build your project manually. 
The build stage of target application for afl-fuzz is easy and totally the same as AFL, which can be completed with afl-gcc.
The build stage of target application for libfuzzer is easy too, which can be completed with libfuzzer.a.
The build stage for pure binary with no instrumentation is the same as normal build stage of target application.

For efficient fuzzing, you can build target application with ASAN or other Sanitizer. You can complete it easily with our another tool [SAFL](https://github.com/hghwng/tools-date)

### Start fuzzing

#### Seeds preparation

After building target application, you can use EnFuzzer for fuzzing. Before it, you need to create a seed directory for seeds preparation.
```sh
❯ mkdir in & cp -r ../seed in
❯ ll
[*]       app*
[*]       in/
```

#### Direct invocation

You need to have `tmux` installed (`sudo apt-get install tmux`), then execute:

```sh
EnFuzzer ./app 
```

![image](https://github.com/131250106/enfuzzer/blob/master/example/image/result.png)


