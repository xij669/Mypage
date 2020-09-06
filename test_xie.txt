numbers = [0,'a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']

i = 0

print('please input a number')
name = input()

while i <= 26:
   if int(name) == i:
         print(numbers[i])
         break
   else:
        i = i+1