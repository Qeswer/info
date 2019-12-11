#Lab_4
def first(x):
    chisla = list(map(int,input('введите числа ').split()))
    print(chisla)
    n = True
    for i in range(len(chisla)-1):
        if chisla[i+1] <= chisla[i]:
            n = False
            break
    if n == True:
        text = 'Последовтельность возрастающая'   
    else:
        text = 'последовательность не возрастающая'
    print("Дана последовательность действительных чисел a1, a2, ... ,an. Выяснить, будет ли она возрастающей.","\nдана последовательность",chisla,"\nответ",text,"\n")
first(3)
def second(x):
    chisla = list(map(int,input("введите числа ").split()))
    mass = chisla
    minA = chisla[0]; sumA = 0; minID = 0
    n = len(chisla)
    print(chisla)
    for i in range(1, n):
        if minA >= chisla[i]:
            minA = chisla[i]
            minID = i
        sumA += chisla[i]
    print("Минимальный элемент: ", minA)
    print("ID элемента: ", minID)
    sumA = sumA/len(chisla)
    print("Среднее арифметическое все чисел:", sumA)
    chisla[minID] = round(sumA,0)
    chisla[minID] = int(chisla[minID])
    print('\nответ',chisla)
second(2)
def third(x):
    chisla = list(map(int,input('введите числа ').split()))
    n=len(chisla)
    print(chisla, "\n")
    strA = str("0")
    test1 = 0; test2 = 0
    for i in range(len(chisla)):
        for k in range(len(chisla)):
            if i != k and abs(x - ((chisla[i]+chisla[k])/2)) < n:
                n = abs(x - ((chisla[i]+chisla[k])/2))
                test1 = chisla[i]; test2 = chisla[k]
                strA = str(chisla[i]) + str(" + ") + str(chisla[k])
                print(x, " - ", (chisla[i]+chisla[k])/2, " = ", abs(x - ((chisla[i]+chisla[k])/2)))
                print(strA, "среднее арифметическое: ", ((test1+test2)/2), "\n")
third(int(input('введите число ')))
input()
