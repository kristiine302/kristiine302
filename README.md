b = "Ieva"

c = 6,2 

d = True

print(a)

print(b)

print(c)

print(d)

# 2.uzd


skaitlis1 = int(input("Ievadi pirmo skaitli: "))

skaitlis2 = int(input("Ievadi otro skaitli: "))

print("Summa ir:", skaitlis1 + skaitlis2)

print("Starpība ir:", abs(skaitlis2 - skaitlis1))

print("Sareizinājums ir:", skaitlis1 * skaitlis2)

print("Dalījums ir:", skaitlis1 / skaitlis2)

# 3.uzd

a = int(input("Ievadi skaitli: "))

if a > 0:

print("Skaitlis ir pozitīvs")

if a == 0:

print("Skaitlis ir nulle")

else:

print("Skaitlis ir negatīvs")

# 4.uzd

x = int(input("Ievadi skaitli x: "))

y = int(input("Ievadi skaitli y:"))

print(math.pow(4 * x, y + 3) + 15 * y)

print((math.pow(5 * y, x) - 144 * x + 2) / math.pow(x + y, 2))

print((2 + x - 2 * x * y) / (y / (x + y)))

# 5.uzd

atz = int(input("Ievadi atzīmi: "))

if atz == 0:

print("F")

elif 1 <= atz <= 2:

print("E")

elif 3 <= atz <= 4:

print("D")

elif 5 <= atz <= 6:

print("C")

elif 7 <= atz <= 8:

print("B")

elif 9 <= atz <= 10:

print("A")

# 5.1.uzd

else:

print("Nepareiza atzīme")
