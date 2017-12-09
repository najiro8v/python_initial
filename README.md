# python_initial
practicas de python

def marios(x):
    if x<0:
        return -1
    elif x==1:
        y=2
        temp=2
    else:
        y=x
        temp=2
    if x>23:
        return -1
    for j in range(x):
        for i in reversed(range(y)):
            print(" ",end=" ")
        for i in range(temp):
            print("#",end=" ")
        print("")
        y=y-1
        temp=temp+1
    return
def main():
    print("ingrese la altura de su piramide")
    x=int(input())
    marios(x)
    print("\nfinal")
    return
if __name__==("__main__"):
    main()
