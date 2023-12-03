# hello-world
利用github创建的第一个repository仓库，仓库的名字是hello-world
这是一个.md的自述文件，文件名称为readme
这个文件主要是用来介绍这个repository仓库的
usrp
import uhd
import numpy as np
usrp=uhd.usrp.MultiUSRP()
uhd.
samples=usrp.recv_num_samps(10000,2400e6,1e6,[0],50)
#while(1):
a=1
for i in samples[0]:
    print(i)
print(len(samples[0]))
