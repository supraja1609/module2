# module2
MAINTAIN EFFICIENT PROCESS UTILIZATION ON WINDOWS
    
    
1.Task manager:

![taskmanager](https://user-images.githubusercontent.com/83391098/118987460-e7821c80-b99d-11eb-887f-813530d151a8.png)


to view the apps running behind we can use taskmanager app we can find it by searching in search bar


2.Task details:

![taskdetails](https://user-images.githubusercontent.com/83391098/118988404-c968ec00-b99e-11eb-8656-7ab708ef16db.png)

task details tab is used to see the status of apps which are runnning


3.Get process:

![getprocess](https://user-images.githubusercontent.com/83391098/118988733-15b42c00-b99f-11eb-842d-f22edbda68df.png)

We can get the details which apps are all running in windows by using WINDOWS POWER SHELL by using the command get-process

4.Get-process select:

![getprocess(select)](https://user-images.githubusercontent.com/83391098/118989153-6e83c480-b99f-11eb-8dd2-c8ca5e827d7a.png)

To get the top three apps which are running by using the command Get-Process | Sort CPU -descending | Select -first 3 -Property  ID,ProcessName,CPU

5.Task kill

![taskkill](https://user-images.githubusercontent.com/83391098/118989800-f1a51a80-b99f-11eb-90b7-0fd308067c30.png)

To kill the task which is running we can use the command killtask /pid (pid  number) PID is nothing but process ID we can see the process id in task details tab

6.Multi taskkill:

![multitaskkill](https://user-images.githubusercontent.com/83391098/118990317-64ae9100-b9a0-11eb-9c6e-2e21517023a4.png)

We can also kill multiple task which is running by using the command killtask /pid () /pid()

