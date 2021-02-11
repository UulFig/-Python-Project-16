# -Python-Project-16
#16 A random person should pay the bill

import random

names_string = input("Give me everybody's names, separated by a comma. ")
names = names_string.split(", ")

num_names = len(names)

rng = random.randint(0,num_names - 1)
pay = names[rng]
print(f"Click clack ! {pay.title()} should pay!")
