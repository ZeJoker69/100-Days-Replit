# 100-Days-Replit
My Beginner days
from getpass import getpass as input
print("""\033[31m
WELCOME ALL CHALLENGERS TO THE GREATEST R.P.S GAME
\033[0m""")
print("")
print("Select your moves [R, P, S]")
R = ("R")
P = ("P")
S = ("S")

player1 = input("Player 1, Your Move: ")
player2 = input("Player 2, Your Turn: ")
if player1 == R and player2 == P:
  print("Player 2 wins this round")
if player1 == R and player2 == S:
  print("Player 1 Wins")
if player1 == R and player2 == R:
  print("We have a Tie")
elif player1 == P and player2 == R:
  print("Player 1 Wins this battle")
if player1 == P and player2 == P:
  print ("A Tie, we must not come to again")
if player1 == P and player2 == S:
  print("Ah yes, Player 1 loses to a Sciccors")
elif player1 == S and player2 == R:
  print("Player 1 seems to have lost to Rock")
if player1 == S and player2 == P:
  print("Yup thats the stuff, Victory for Player 1")
if player1 == S and player2 == S:
  print("Pussies with a double S")
else:
  print("Game Over")
