# Programming-with-Python


# str="Apple"
# leng=len(str)-1
# for i in range(leng,-1,-1):
#     print(str[i],end=" ")


# str="madam"
# i=0
# j=len(str)-1
# flag=0
# while(i<j):
#     if(str[i]!=str[j]):
#         flag+=1
#         break
#     i+=1
#     j-=1
# if(flag==0):
#     print(str,"palindrome")
# else:
#     print(str,"is not palindrome")


# str="qwertyuinbvfdsa"
# length=len(str)
# flag=0
# for i in range(0,length):
#     if(str[i]=='a'or str[i]=='e' or str[i]=='i' or str[i]=='o' or str[i]=='u'):
#         flag+=1
# print("Total no of vowels ",flag)
# print("Total no of Consonants ",length-flag)

# str="Ankit   Kumar"
# Ostr=""
# for i in range(0,len(str)):
#     if(str[i]!=' '):
#         Ostr+=str[i]
# print(Ostr)


# str = input("Enter a string: ")
# chars = list(str)
# unique = []

# for i in chars:
#     if i not in unique:
#         print(i, ":", chars.count(i))
#         unique.append(i)
