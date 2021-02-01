# Pokemon-Chooser
a = "Ignore"
b = "Join the fight"
c = "Try to stop the fight"
d = "Scare the people who are fighting away"
e = "Complain"
battle = ['YOU LOSE', 'YOU WIN']
print("Hi, this program is a pokemon carrier game. (There are some battles)")
print("Answer the question (be honest!)")
print("If there was a fight happening what would you do?")
print(f"a {a}")
print(f"b {b}")
print(f"c {c}")
print(f"d {d}")
print(f"e {e}")
choice = input("Enter your choice: ")
if choice == "a":
    print("Your pokemon patner is Bulbasaur") # You can write whatever pokemon you like.
    print("Type: grass/poison")
    print("Attacks: vine whip, power whip, tackle, sludge bomb and a couple more.")
elif choice == "b":
    print("Your pokemon patner is Charmander")
    print("Type: fire")
    print("Attacks: ember, flame charge, flame burst, flamethrower and a couple more.")
elif choice == "c":
    print("Your pokemon patner is Abra")
    print("Type: psychic")
    print("Attacks: zen headbutt, shadow ball, psyshock, charge beam and a couple more.")
elif choice == "d":
    print("Your pokemon patner is Gastly")
    print("Type: ghost/poison")
    print("Attacks: lick, sludge bomb, confuse ray, hypnosis and a couple more.")
elif choice == "e":
    print("Your pokemon patner is Whismur")
    print("Type: normal")
    print("Attacks: astonish, hyper voice, echoed voice, pound and a couple more")
