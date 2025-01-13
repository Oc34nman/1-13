# 1-13

def Numbers(a):
    return 2*3.14*a

result = Numbers(5)
print("the circumference is:", result)
#---------------------------------------
def num(a):
    if a %2 == 0:
        return True
    else:
        return False
   
result = num(8)
print ("this number is:", result)
#---------------------------------------
def Frog(num):
    for n in range(num):
        print("ribbit", end = " ")
    print()
   
   
Frog(12)
