# 3.py
Write a program to find those numbers which are divisible by 7 and multiple of5, between 1500 and 2700 (both included).

n=[] 

for x in range(1500, 2701):

    if (x%7==0) and (x%5==0): -condition 
    
        n.append(str(x)) -appends 
        
print (','.join(n))
