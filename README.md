# RohithKarraInterview

1. Usage: ansible-playbook interview-playbook.yml
Note1: No need to give the inventory path as this playbook is written for running on the localhost which we declared in the playbook.
Note2: This playbook is written and tested on the linux box. So, the expected output is for MacOS but can find the linux variant here.
For LINUX: uname -a
For MacOS: sysctl kern.version | cut -d " " -f 3-     

2. The expected Output should be:
cat my-template.txt
My custom variable is test1234
My operating system is Linux 0df58febde1c.mylabserver.com 3.10.0-1160.2.2.el7.x86_64 #1 SMP Sat Oct 17 05:06:47 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux

3. Provided a single playbook architecture too for this task for your reference.
Usage: ansible-playbook singleplaybook.yml
