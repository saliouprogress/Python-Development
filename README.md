# Python-Project-Biggineer
#Learning Python from the ground up
t = [1,2,3,4,5,6,7,8,9]
empty = []
for nested in range(len(t)):
    empty.append(sum(t[0:nested+1]))
#print(empty) 

a = ['mon','ton','son',[ 'ma','ta','sa'], 'mes','tes','ses']
b = []

for cap in range(len(a)):
  	#if len(a[cap]) < 2:
     b.append(a[cap].capitalize())
     '''   
    	else:
      		c = a[cap]
            	print(c)
        	d = []
            	for subcap in range(len(c)):
                	d.append(c[subcap].capitalize())
                  	
        	#b[cap] =d 
      '''
print(b)
