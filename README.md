print("WELCOME TO MY COMPUTER QUIZ")

playing=input("do you want to play? ")

if playing.lower() != "yes":
    quit()

print("ok...let's play")
score=0

answer=input("what does CPU stand for ")
if answer.lower()=="central processing unit":
    print("correct")
    score +=1
else:
    print("incorrect") 

answer=input("what does GPU stand for ")
if answer.lower()=="graphics processing unit":
    print("correct")
    score +=1
else:
    print("incorrect") 

answer=input("what does RAM stand for ")
if answer.lower()=="random access memory":
    print("correct")
    score +=1
else:
    print("incorrect") 

answer=input("what does ALU stand for")
if answer.lower()=="arithmetic logical unit":
    print("correct")
    score +=1
else:
    print("incorrect") 

print("you got" + " " + str(score) + " " + "questions correct")
print("you got" + " " + str((score / 4) * 100) + "%")
