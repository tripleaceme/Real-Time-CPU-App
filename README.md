# Real Time CPU App
 Monitor you Computer Memory Usage in Real-Time

How annoying can it be for you to always open Task Manager before
you can know the your cpu usage flow. If you are someone like me that use my
laptop on a daily, I want to see which software uses more cpu resource.

To get your cpu usage, open task manager, switch to the performance tab.
You will see the overall performance of your CPU usage.
Something like the image below.

picture b
For a more detailed breakdown of your CPU usage, right click on the visual
and change graph to 'LOGICAL PROCESSOR'
Depending on the number of your cpu cores which in this case mine is 2,
so changing to Logical processor will split the graph into 4. You will be 
different depending on the number of cores. 

Now you can see the performance of each CPU Cores. 

The problem i have with this is that it's small and i can't keep my task
manager running because I want my CPU Usage Statistics.

Why not develop mine using python and one of the library (Matplotlib)

Here is how it works:


Blue color means the software has been running for less than 1000secs
blue screen image

Red color means the software has been running for more than 1000secs
red screen image

What's the Difference between this and the task manager performance tab
1. This software gives you the stats of 1000secs usage compare to the 60secs of 
task manager
2. Better view and color to differenciate the running time

Upgrade:
To allow spliting of the performance screen based on the number of cores.

Here is the Github repo link if you want to contribute to the project.
click here

Download and see the real time usage of your cpu in a better view
click here