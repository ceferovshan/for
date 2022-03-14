# for
a = [] b = [] for i in list(range (30,40)):     
if i%2 ==0:        
a.append(i)     
if i%3 ==0:     
b.append(i) 
else:    
print(a)
print(b)
a= [i**2 for i in range(10)]
print (a)
print(list(enumerate(a)))
