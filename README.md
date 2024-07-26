# Write a program to print multiplication formate by user with the range of 10 or 20.
n=int(input("enter the number of table of mul choice : "))
m=int(input("enter the number of table conent :"))
print("multiplication table of ",n,"follows:")
print("*****")
for i in range (1, m+1):
  print(n, "X" , i, "=",n*i)
