# BSEF15M534
#include<stdlib>
#include!usr/bin/python
print("WElcome To Python .....Priority sched is here ...!!!")
processes={}
priority=[]
a_time=[]
b_time=[]
n=input("Enter number of processes :  ")
for i in range (0,n):
	arrival=input("Enter arrival time of the processes :  ")
if(i==0):
	min=num
elif(min>arrival):
	min=arrival
a_time.append(arrival)
ctime=input("Enter CPU(burst) time of the processes : ")
b_time.append(ctime)
prior=input("Enter priority of the processes :  ")
priority.append(prior)
processes[priority[i]]=[i+1,a_time[i],b_time[i]]
print "arrival.t","	","Burst.t","	","priority"
for j in range(0,n):
	print a_time[j],"	",b_time[j],"	",priority[j]
	priority.sort()
	sum=min
if(sum>0):
	print"0------",sum,"Idle time"
for i in range(0,n):
	j=processes.get(priority[i])[2]
	print min,"		",sum," p",processes.get(priority[i])[0], "finished"
	min=sum





