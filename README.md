# 14-02-22-ass-1
#find number of digits in a given number
n=int(input('enter number:'))
count=0
while(n>0):
    count=count+1
    n=n//10
print('The number of the digits are:',count)

output:
enter number:04527
The number of the digits are: 4
