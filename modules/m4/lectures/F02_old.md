---
layout: instructions
title: Modul 4 - Listor och lexikon
code: m4
---

# Mer om listor och nästlade listor

## Dagens exempelkod

### Exempel 1

{% highlight python linenos %}
# Skapa en lista med studenter
students = ["Johanna", "Anton", "Eva", "Linda", "Johanna"]

# Skriv ut antal studenter i listan
print(len(students))

# Lägger till en ny student
students.append("Kalle")

# Skriv ut antal studenter i listan
print(len(students))

# Räknar hur många studenter som heter "Anton"
print(students.count("Anton"))


# Frågar användaren efter studenter
new_students = input("Ange nya studenter, separera med ,: ")

# För varje student (skapar en lista av studenter genom
# att separerar användarens input med ","
for new_student in new_students.split(","):
    students.append(new_student)

# Skriver ut listan med studenter

# Lägger till fler studenter
new_students = input("Ange nya studenter, separera med ,: ")
for new_student in new_students.split(","):
    students.append(new_student)

# Skriver ut studenterna
print(students)

{% endhighlight %}

### Exempel 2

{% highlight python linenos %}
def print_bus(bus):
    '''Print a visual representation of a bus

    Args:
        bus: list
    '''
    print("\nBussen\n")

    # För varje rad av säten i bussen
    for row in bus:
        # För varje säte på en rad
        for seat in row:
            if seat:
                # Om sätet är bokat (True)
                print("[X]", end="")
            else:
                # Om sätet inte är bokat (False)
                print("[ ]", end="")
        print("\n-------------")

# Skapar en buss med 24 rader, 4 säten per rad
bus = [[False]*4 for i in range(24)]
# Skriver ut bussen
print_bus(bus)

# Markerar rad: 3, säte 0, som bokad
bus[3][0] = True

# Skriver ut bussen
print_bus(bus)

# Frågar användaren vilket säte som ska bokas
user_booking = input("Booka en plats, genom att ange rad/säte: ").split("/")
# Bokar sätet genom att ange:
# Rad: int(user_booking[0]) Det som användaren anger innan "/"
# Säte: int(user_booking[1]) Det som användaren anger efter "/"
bus[int(user_booking[0])][int(user_booking[1])] = True

# Skriver ut bussen
print_bus(bus)

# Frågar användaren efter rad
user_row = int(input("Vilken rad vill du sitta på: "))-1
# Frågar användaren efter säte
user_seat = int(input("Vilken plats vill du sitta på: "))-1
# Markerar valt säte som upptaget
bus[user_row][user_seat] = True
# Skriver ut bussen
print_bus(bus)
{% endhighlight %}
