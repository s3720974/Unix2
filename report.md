<h1>Report of Data stored in kernel_performance_data <h1/>

<p>
The first few seconds or minutes temperature of the  Raspberry Pi is on the usual average temperature which is around the 55C-65C range this is probably due to the first parts of the script being the downloading and installing the dependencies for the kernel and moving/downloading config/script files which does not need a lot of CPU resources
</p>

<p>
We can see this the CPU temperature increase to the 80C range after a few minutes which will stay till the end the graph as compiling and building the Kernel requires a lot CPU usage, majority of the time it stayed.
</p>
    
<p>
The slight decrease in temperature on the 4000 seconds mark is probably after the kernel finishes compiling. This will later increase again after a few seconds as it will need more resources to build the kernel.
</p>

<h2>Conclusion</h2>

<p>
To make the graph or information more accurate and a bit more readable, we can increase the sleep duration on the monitoring script to lessen the cluster of data, another adjustment that can be made is turning seconds to minutes.
</p>