import sys, time, random

HP = 100
havePotion = False


def checkHP():
    if HP < 1:
        print("YOU DIED.")
        time.sleep(5)
        sys.exit()


def printHP():
    print("Your HP is " + str(HP))
    time.sleep(0.5)


def usePotion():
    if havePotion is True:
        randomHP = random.randint(10, 40)
        print("You gulp down your potion and restore " + str(randomHP) + "HP!")
        havePotion = False

    else:
        print("You don't have a potion!")


while True:
    choiceHelp = input("Would you like instructions on how to play? (y/n): ")

    if choiceHelp in ["y", "Y"]:
        print("""Type "HP" anytime to check your health.""")
        print("""Type "Use Potion" while in combat to drink a health potion.""")
        break

    elif choiceHelp in ["n", "N"]:
        print(" ")
        break

    else:
        continue

while True:                                         # Get name from user
    myName = input("What is your name?: ")

    if myName != "":
        break

    elif myName == "":
        continue

print("Your name is " + myName)
time.sleep(1)


while True:
    myGen = input("Are you a boy or a girl?: ")  # Get gender from user

    if myGen in ["boy", "Boy"]:
        print("You are a boy")
        time.sleep(1)
        break

    elif myGen in ["girl", "Girl"]:
        print("You are a girl")
        time.sleep(1)
        break

    elif myGen in ["hp", "HP"]:
        checkHP()
        continue

    else:
        continue

while True:
    myClass = input("You are about to embark on an epic quest! What class shall you be, a Knight or a Mage?: ")

    if myClass in ["knight", "Knight"]:
        print("You have selected Knight.")
        time.sleep(1)
        break

    elif myClass in ["mage", "Mage"]:
        print("You have selected Mage")
        time.sleep(1)
        break

    elif myGen in ["hp", "HP"]:
        checkHP()
        continue
    else:
        continue

while True:
    print("You come across an abandoned castle next to a lake, shall you investigate the interior? (y/n)")
    choiceOne = input()

    if choiceOne in ["n", "N"]:
        print("You leave the area")
        break

    elif choiceOne in ["y", "Y"]:
        print("You approach the entrance cautiously, opening the main entrance doors carefully and then entering.")
        time.sleep(3)
        print("Inside of the castle, you come across an evil skeleton!")
        time.sleep(3)
        print("It carries with it a rusty sword as well as a worn down shield.")
        time.sleep(3)
        print("The skeleton strikes your shoulder with its weapon!")
        HP = HP - 1
        checkHP()
        time.sleep(3)
        print("However upon doing so, the skeleton falls apart in front of you.")
        time.sleep(3)
        print("The inside of the castle is dark and eerily quiet.")
        time.sleep(3)
        break

    elif myGen in ["hp", "HP"]:
        checkHP()
        continue

    else:
        continue

while True:
    choiceTwo = input("There are two doors in front of you, one to your Left and your Right, which one shall you enter?: ")

    if choiceTwo in ["left", "Left"]:
        RNG = random.ranint(1, 2)
        if RNG ==
            print("inside of the room lies many crates, inside one you find a potion!")
            time.sleep(2)
            print("You take the potion")
            time.sleep(2)

        print("You slowly open the Left Door, only to find it to be completely empty, you procede to the Right Door; entering it.")
        time.sleep(3)
        break

    elif choiceTwo in ["right", "Right"]:
        print("You enter the Right Door.")
        time.sleep(2)
        break
    elif myGen in ["hp", "HP"]:
        print("Your HP is " + str(HP))
        time.sleep(0.5)
    elif myGen in ["hp", "HP"]:
        checkHP()
        continue
    else:
        continue

print("In it, you find youself standing amoungst a long dark corridor")
time.sleep(2)
print("You begin making your way")
time.sleep(2)

if myClass in ["knight", "Knight"]:
    print("You stumble upon a chest in the middle of the corridor, you open it, revealing some loot!")
    time.sleep(3)
    print("You have found an Iron Sheild as well as a worn Iron Mace!")
    time.sleep(2)
    print("You equip the gear")
    time.sleep(2)

elif myClass in ["mage", "Mage"]:
    print("You stumble upon a chest in the middle of the corridor, you open it, revealing some loot!")
    time.sleep(3)
    print("You have found an old spellbook as well as an Apprentice's Staff!")
    time.sleep(2)
    print("You equip the gear")
    time.sleep(2)
