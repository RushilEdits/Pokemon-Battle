import random

name_input = input("Hi! What's your name? ")

print(f"Nice to meet you, Pokemon trainer {name_input}! Let's have a Pokemon Battle!")

choices = ["charizard", "venusaur", "blastoise"]

player_choice = input("I've selected mine, select yours from, Charizard🔥, Blastoise🌊 or Venusaur🌱! ").lower().strip()

bot_choice = random.choice(choices)

print(f"Mine was {bot_choice}")

if player_choice == bot_choice:
  print("It's a tie, we both had same type of Pokemon!")

elif (player_choice == "charizard" and bot_choice == "venusaur") or (player_choice == "venusaur" and bot_choice == "blastoise") or (player_choice == "blastoise" and bot_choice == "charizard"):
  print("You win!")

else:
  print("I win!")
