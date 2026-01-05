#ASSIGNMENT:1
# task 1
a=int(input("1st Enter a number: "))
b=int(input("2nd Enter a number: "))
sum=a+b
sub=a-b
multi=a*b
div=a/b
print("Sum:",sum)
print("Subtraction:",sub)
print("Multiplication:",multi)
print("Division:",div)
# task 2
c=str(input("Enter your first name: "))
d=str(input("Enter your last name: "))
full_name="hello "+c+" "+d+ " wellcome to python programming"
print("Full Name:",full_name)
#ASSIGNMENT:2
# task 1
e=int(input("enter any number: "))
if e%2==0:
     print(e,"is even number")
else:
    print(e,"is odd number") 
# task 2
add=0
for i in range (1,50):
    add= add+i
print("Sum of first 50 natural number is:",add)
