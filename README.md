# max-value
#without using max()
n=int(input())
a=list(map(int,input().split()))
largest=0
for i in range(n):
  if a[i] > largest: 
            largest = a[i] 
print(largest)

#with using max()
n=int(input())
a=list(map(int,input().split()))
print(max(a))
