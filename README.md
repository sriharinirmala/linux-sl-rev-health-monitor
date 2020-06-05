# linux-sl-rev-health-monitor
in this we are going to see about commnds like - sl,rev and how to monitor the health of the system using linux

SCRIPT2.sh: download this file and run it in your terminal ./script2.sh After executing the packages for sl will be installed and a train like structure will be moving in your terminal which is because of sl command. "sl" command is a fun command.

Script1.sh: it contains the the command "rev"(download this file) rev - is a command used to reverse the word that you enter. so after executing this(by typing this in your terminal ./script1.sh). it will prompt you to enter a word when you type a word and press enter the reverse of that word will be displayed.

"FACTOR": The factor command displays the factor of the entered number

"YES":Yes command just displays y in terminal until you cancel it

health.sh: first download this file and run it in your terminal by typing ./health.sh if it shows permission denied type chmod +x health.sh and then type ./health.sh in the linux terminal EXPLANATION of code in health.sh: vmstat - vmstat is a command which displays many information about the system which is useful for the monitoring of system

the vmstat 1200 – monitors every 24 hours and puts the data into the vmstat1.data

grep “swap”- the swap should always be zero if its not then some process has consumed massive memory. That will be monitored in this line

grep “r”- the running queue is constantly above process 1 it indicates the system is slow and some process is waiting to be executed. That will be monitored here.

Grep “cpu”- it indicates the cpu usage of the system. If the cpu usage is more it will be monitored and will alert in this line.
