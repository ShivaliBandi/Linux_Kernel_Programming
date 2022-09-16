# Steps to run hello world program
# install:
# sudo apt-get update -y
# sudo apt-get install -y kmod
# sudo lsmod
# sudo cat /proc/modules
# sudo apt-get install kmod linux-headers-5.15.0-46-generic
# make
# modinfo HelloWorld.ko (you will get module information)
# sudo insmod HelloWorld.ko (for inserting module)
# tail /var/log/kern.log (to check whatever we wrote using printk as it will be in logfile instead of output screan because we are doing kernel programming we need to check logs)
# sudo rmmod HelloWorld (For removing module which was inserted by insmod command)
# tail /var/log/kern.log (Checking logs whether its successful or not)