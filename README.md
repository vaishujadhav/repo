import random
jackpot=random.randint(1,100)
guess = int(input('guess kar lavkar'))
counter = 1
while guess !=jackpot:
  if guess<jackpot:
    print('naah aah .....guess higher')
 else:
    print('not bad not bad .....guess lower')
  guess = int(input('parat guess kr '))
  counter +=1
 else:
  print('are waah ekdam barobar')
  print('yevde attempt getale pn',counter)
