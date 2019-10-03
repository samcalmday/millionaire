# millionaire
import random
answer_1 = ""
fanswer = ""
amount = 0
def call_a_friend():
  """ The call a friend function"""
  number = random.randint(1,100)
  print(number)
  if number < 86:
      print("Correct answer is " + fanswer)
      print(f"Currently you have made {amount}")
  else:
      print("Wrong answer")
      quit()
   
        

player_name = input("Welcome to Millionaire! What is your name? ")

print(f"Currently you have made {amount}")
for question_number in range(1,9):
  if question_number == 1:
    print("""In the rhyme 'Sing a Song of Sixpence', how many blackbirds were baked in a pie?

A: Twenty two
B: Twenty four
C: Twenty six
D: Twenty eight""")
    answer_1 = input("input an answer  ")
    fanswer = "B"
    
    if answer_1 == "B":
      print("Correct!")
      amount = 500
      print(f"Currently you have made ${amount}.")
    elif answer_1 == "Call a friend" :
      amount = 500
      call_a_friend()
    else:
      print("I'm sorry, that is incorrect")
      break
  elif question_number == 2:
    print("""What man gave the Byrds their only UK No. 1 hit?

A: Mr.Sandman
B: Mr.Sleaze
C: Mr.Telephone Man
D: Mr.Tambourine Man""")
    answer_1 = input("input an answer  ")
    fanswer = "A"
    if answer_1 == "A":
      print("Correct!")
      amount = 1000
      print(f"Currently you have made ${amount}.")
    elif answer_1 == "Call a friend" :
      amount = 1000
      call_a_friend()  
    else:
      print("I'm sorry, that is incorrect")
      break     
  elif question_number == 3:
    print("""What was every contestant on TV's 'Crackerjack' guaranteed to win?

A: A cracker
B: A cabbage
C: A pencil
D: A balloon""")
    answer_1 = input("input an answer  ")
    fanswer = "A"
    if answer_1 == "A":
      print("Correct!")
      amount = 5000
      print(f"Currently you have made ${amount}.")
    elif answer_1 == "Call a friend" :
      amount = 5000  
      call_a_friend()  
    else:
      print("I'm sorry, that is incorrect")
      break           
  elif question_number == 4:
    print("""How many players are there in a Rugby League team?

A: Eleven
B: Twelve
C: Thirteen
D: Fifteen
""")
    answer_1 = input("input an answer  ")
    if answer_1 == "D":
      fanswer = "D"
      print("Correct!")
      amount = 20000
      print(f"Currently you have made ${amount}.")
    elif answer_1 == "Call a friend" :
      amount = 20000  
      call_a_friend()  
    else:
      print("I'm sorry, that is incorrect")
      break 
  elif question_number == 5:
    print("""Which day of the week gave The Mamas and The Papas a Top Ten hit in 1966?

A: Sunday
B: Monday
C: Friday
D: Saturday""")
    answer_1 = input("input an answer  ")
    fanswer = "A"
    if answer_1 == "A":
      print("Correct!")
      amount = 50000
      print(f"Currently you have made ${amount}.")
    elif answer_1 == "Call a friend" :
      amount = 50000
      call_a_friend()  
    else:
      print("I'm sorry, that is incorrect")
      break       
  elif question_number == 6:
    print("""What is an actor's stand in called?

A: Deputy
B: Substitute
C: Understudy
D: Number Two""")
    answer_1 = input("input an answer  ")
    fanswer = "D"
    if answer_1 == "D":
      print("Correct!")
      amount = 250000
      print(f"Currently you have made ${amount}.")
    elif answer_1 == "Call a friend" :
        amount = 250000
        call_a_friend()  
    else:
      print("I'm sorry, that is incorrect")
      break  
  elif question_number == 7:
    print("""Which of these is yellow and pink?

A: Battenburg cake
B: Tinky Winky
C: A turtle dove
D: Queen's racing colours""")
    answer_1 = input("input an answer  ")
    fanswer = "C"
    if answer_1 == "C":
      print("Correct!")
      amount = 500000
      print(f"Currently you have made ${amount}.")
    elif answer_1 == "Call a friend" :
      amount = 500000
      call_a_friend()  
    else:
      print("I'm sorry, that is incorrect")
      break
  elif question_number == 8:
    print("""In the film 'Gregory's Girl', what sport was Dorothy good at?

A: Tennis
B: Boxing
C: Hockey
D: Football""")
    answer_1 = input("input an answer  ")
    fanswer = "B"
    if answer_1 == "B":
      print("Correct!")
      amount = 1000000
      print(f"Currently you have made ${amount}.")
      print("You are a millionaire")
    elif answer_1 == "Call a friend" :
      amount = 1000000
      call_a_friend()  
    else:
      print("I'm sorry, that is incorrect")
      break    
  
  
          
