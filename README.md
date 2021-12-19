'''

    Variables amount exchanges in Python with simple example:
        
        1)
            a = b
            b = a+b
            
        2)
            a , b = b , a+b
'''



a=1
b=2

a , b = b , a+b     # a = 2  ,   b = (a+b) = 2+1 = 3

print(a)
print(b)



print('=====================')



x=1
y=2

x= y               # x = 2
y= x+y             # y = 4    >>>>>>>>>   (x+y) = 2+2 = 4

print(x)
print(y)
