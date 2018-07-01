import random
countAttempts = 0
number = random.randint(1,100)

print(" WELCOME TO GUESS NUMBER GAME @ PYTHON 3 ")
# WHEN YOU GIVE WRONG ANSWER AFTER 5 ATTEMPTS THE GAME WILL ALSO TELL THAT YOUR GUESS NUMBER WAS HOW MUCH WRONG
def guessNumber(guess,number):
	global countAttempts
	
		

	if guess == number :
		print("Congrats! , 'Your guess is absolutely correct :) ' WE GIVE YOU FIVE STARS ***** ENJOY ")
	
	else  :
		countAttempts += 1

		print(" Sorry  your guess is wrong :(")

		if (guess < number)  :

			print(" Your guess is less than number ")

			if guess + 10 < number:

				print(" Moreover it is far less than number ")

		if (guess > number) :

			print(" your guess is greater than number ")

			if guess - 10 > number :

				print(" Moreover it is far greater than number ")

		if countAttempts < 5:                                  # THE GAME WILL ALLOW FIVE ATTEMPTS FOR GUESSING A NUMBER
		   print(">>> try again!")

		   main()

		else:

			print(">>> Time up! you had only 5 attempts")

			print(">>> Game Over :(")

			print(">>> THE CORRECT NUMBER IS : " , number)
	
	
   
def main():
	

	guess    =    int( input("enter a number for guess number game:"))
	
	try:
		if guess > 100 or guess < 0:

			raise Exception  (" Your guess is out of the range ")

	except Exception as e :

		print(e)

	else:

		guessNumber(guess,number)
	
main()    
