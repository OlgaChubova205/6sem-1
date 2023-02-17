index = input ("Ввиите номер: ")
print(index)
a=0
while a != "Все верно":
    while index.isdigit():
        while len(index) != 10:
            indexa = input ("Неверная длина, введите номер: ")
            while index[0] == "0":
                print("Нельзя начать с 0")
        print("Все верно")
        a = "Все верно"
    else:
        index = input("Оставьте цифры, введите номер: ")  
