# Assignment-2

 
import random
 
maxTickets = int(input("Enter the maximum tickets"))
 
participants = [] 
 
for temp in range(maxTickets):
  st = "Ënter the participant name - "+ str(temp + 1) 
  name = input(st)
  participants.append(name)
 
print("All our participants - ",participants)
 
n = random.randint(0,maxTickets-1)
 
print("Winner of the lottery - ",participants[n])

Output: 
Enter the maximum tickets3
Ënter the participant name - 1Lippy
Ënter the participant name - 2Laddu
Ënter the participant name - 3Lucky
All our participants -  ['Lippy', 'Laddu', 'Lucky']
Winner of the lottery -  Lippy
