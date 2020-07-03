myT = (2, 3, 5, 7, 9, 6, 0)
myDict = {}
key = 1
for i in myT:
    myDict[key] = i
    key += 1
print("Tuple: ", myT)
print("Tuple to Dict.: ", myDict)