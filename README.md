# pmbw
Clone from http://panthema.net/2013/pmbw/

Parallel Memory Bandwidth Benchmark / Measurement

---

##Quick Start

    yum install gnuplot
        gnuplot-4.6.2-3.el7.x86_64.rpm
        gnuplot-common-4.6.2-3.el7.x86_64.rpm
        
    cd pmbw-0.6.2
    
    nice -n -2 ./pmbw -M 536870912 -S 0
    
    ./stats2gnuplot stats.txt | gnuplot

