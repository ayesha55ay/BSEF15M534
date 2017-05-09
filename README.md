print("This is my first priority scheduling program in python")
processes={}
a_time=[]
b_time[]
priority=[]

n=input("Enter no of processes : ")
for i in range(0,n):
arrival=input("Enter arrival time of the processes :  ")
if(i==0):
initial=arrival
elif(initial>arrival):
initial=arrival
a_time.append(arrival)
ctime=input("Enter burst time of the processes :  ")
b_time=append(ctime)
prior=input("Enter priority of the processes :  ")
priority.append(prior)
processes[priority[i]]=[i+1,a_time[i],b_time[i]]
print "arrival.t","	","Burst.t","	","priority"
for j in range(0,n):
print a_time[j],"	",b_time[j],"	",priority[j]
priority.sort()
sum=initial
if(sum>0):
print"0------",sum,"Idle time"
for i in range(0,n):
j=processes.get(priority[i])[2]
print initial,"		",sum," p",processes.get(priority[i])[0], "finished"
initial=sum



