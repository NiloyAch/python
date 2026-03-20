age = 45
interest_rate = 2.5
print(interest_rate)
name = "niloy"
print(name)
is_single = True
is_sleeping = False
print(age+interest_rate)

print(type(age))
print(type(interest_rate))

print(type(is_single))
print(type(name))

print('Kodom ali' + ' ' +'kacha badam')
text = f"kdom ali {age} living in {interest_rate}"
print(text)



############
num1 = 45
num2 = 5
print(num1+num2)
print(num1-num2)
print(num1*num2)
print(num1/num2)
print(10/3)
print(10%3)
print(10//3) #purno vag fol

power = num1**num2    #power calculation
print(power)



###########

    # num = 1
    #while num<=10:
    #   print(num)
    #   num = num+1

"""
num = 1
while num<=10:
    num = num+1
    if num==5:
        continue
    print(num)
    
"""
""" 
num = 1
while num<=10:
    num = num+1
    if num%2==1:
        continue
    print(num)

"""

""" 
numbers = [5,10,15,20,25]
sum = 0
for num in numbers:
    #print(num)
    sum = sum+num
    if sum>20:
        print("Bigger values")
        print(sum)    
    

""" 

#text = "Niloy"
#for char  in text:
#    print(char)



#for i in range(1,10,2):      # range(inclusive,exclusive,step)
 #   print(i)


arr = [10,20,30,40,50,60]

for index , value in enumerate(arr):
    print("Index:" ,index, "Value:" ,value)



