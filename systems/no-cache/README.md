Design of this system looks like the following ![alt-text](http://pages.cs.wisc.edu/~david/courses/cs752/Spring2015/gem5-tutorial/_images/simple_config.png) 

To run this, the command to run from the gem5 directory would be like the following `build/X86/gem5.opt configs/systems/no_cache_simple.py` assuming this file is located at configs/**systems/no_cache_simple.py**. To adjust the binary which runs, you need to point line 36 (`process.cmd = ['tests/test-progs/hello/bin/x86/linux/hello']`) to the appropriate binary location.