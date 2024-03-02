# python--evevn-odd
#approch--2--without range
'''n=int(input())
a=list(map(int,input().split()))
r=0
for i in a:
  if i%2==0 and i>r:
    r=i
print(r)'''  

#approch--3--elements are separeted only even numbers
'''n=int(input())
a=list(map(int,input().split()))
r =[]
for i in range(n):
  if a[i]%2==0:
    r.append(a[i])
print(max(r))'''

#without range -- separate only evev numbers which is highest
'''n=int(input())
a=list(map(int,input().split()))
r =[]
for i in a:
  if i%2==0:
    r.append(i)
print(max(r))'''
#approch--withrange
#elements are separeted only odd numbers which is highest
'''n=int(input())
a=list(map(int,input().split()))
r =[]
for i in a:
  if i%2!=0:
    r.append(i)
print(max(r))'''

#sum of max even number and max 0dd number
'''n=int(input())
a=list(map(int,input().split()))
r =[]
t=[]
for i in range(n):
  if a[i]%2==0:
    r.append(a[i])
  if a[i]%2!=0:
    t.append(a[i])
print(max(r))
print(max(t))'''
# sum of even+odd
'''n=int(input())
a=list(map(int,input().split()))
e=0
o=0
for i in a:
  if i%2==0 and i>e:
    e=i
  elif i>o:
    o=i
print(e+o)'''

#approch--3--
#sum largest even and largest odd values
'''n=int(input())
a=list(map(int,input().split()))
e=[]
o=[]
for i in a:
  if i%2==0:
    e.append(i)
  else:
    o.append(i)
print(sum(e))
print(sum(o))'''

#average of even elements
'''n=int(input())
a=list(map(int,input().split()))
e=[]
o=[]
for i in a:
  if i%2==0:
    e.append(i)
  else:
    o.append(i)
print(sum(e)//len(e))
print(sum(o)//len(o))'''
#avg of even elements
'''n=int(input())
a=list(map(int,input().split()))
e=0
o=0
for i in range(n):
  if a[i]%2==0 and a[i]>e:
    e=e+a[i]
    o=o+1
print(e//o)'''
