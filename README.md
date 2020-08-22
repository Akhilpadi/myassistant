# myassistant

import pyttsx3
import os

# pyttsx3.speak("Welcome its ur personal assistant ")
print("\n")
print("Welcome its your personal assistant how can i help you today!!")
print("\n")
print("i can help you with openning certain software application like : *for example, you can ask me to start chrome\n \n \n")        
                                                 
while True:
	print("so lets get started  : "  , end='')
	p = input()

	# print(p)
	# os.system(p)

	if ("run" in p)  and (("chrome" in p) or("start" in p)):
	  os.system("start chrome")

	elif (("run" in p) or  ("execute" in p) or ("start" in p)) and  (("notepad" in p) or ("editor" in p)):
	  os.system("notepad")

	elif (("run" in p) or ("start" in p)) and ("player" in p) and ("media" in p) or ("windows" in p):
	  os.system("start wmplayer")

        elif ("run"	in 	p) and ("calculator"	in 	p) or (	"calc"	in	 p):
         os.system("start calc")  
                                 
	elif ("exit" in p)  or ("quit" in p):
	  break

	else :
           print("\n")
           print("sorry am beginner, u should alwyas use specific words like run or start etc")
