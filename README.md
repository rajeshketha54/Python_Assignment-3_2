# Python_Assignment-3_2
def reverse(str):  
    rev=""                                   #Sample input: 1234abcd
    for x in str:
        rev=x+rev                            #Expected output: dcba4321
    print(rev)
reverse(input())                             #My output: dcba4321
        
