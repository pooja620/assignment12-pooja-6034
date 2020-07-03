myList = [(2, 3, 5, 6), (4, 5, 8, 9), (3, 5, 7, 8)]
myDict = {}
key = 1
for i in myList:
    myDict[key] = i
    key += 1
print("List of tuple: ", myList)
print("List of Tuple to Dictionary: ", myDict)