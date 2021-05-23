My HOMEWORK IS IN THIS FILE

Challenge 1:
def reverse(string):
    if len(string) == 0:
        return 
    temp = string[0]
    reverse(string[1])
    print (temp)

string = "Reverse these words"
reverse(string)

Challenge 2:

def returnList():
    list = [(1*2*3*4), (2*1*3*4), (3*1*2*4), (4*1*2*3)]
    for i in range(0,10):
        list.append(i)
    return list
a = returnList()
print a



not too sure about the last one...

