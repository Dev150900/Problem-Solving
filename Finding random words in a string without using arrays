import random

string = 'It is a beautiful world to live in'
rand_tog = random.randint(0,1)
first_space = 0

for j in range(len(string)):
    if string[j] == ' ':
        first_space = j
        break
        
r = 0
while string[r] != ' ':
    r = random.randint(0,len(string)-1)
    

if r == first_space:
    if rand_tog == 0:
        print(string[:r])
    else:
        while string[r+1] != ' ':
            print(string[r+1],end='')
            r+=1
    
else:
    while string[r+1] != ' ':
        print(string[r+1],end='')
        r+=1
        if r == len(string)-1:
            break
    
