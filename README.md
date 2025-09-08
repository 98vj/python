
#Implicit Type Conversion
x = 5
y = 2.5
z = x + y      # int + float → float automatically
print("x + y =", z)
print("Type of z:", type(z))  # <class 'float'>



#Explicit Type Conversion**")
# Float to int
a = 3.9
b = int(a)
print("int(3.9) =", b)
print("Type of b:", type(b)) 

# Int to float
c = 10
d = float(c)
print("float(10) =", d)
print("Type of d:", type(d))   # <class 'float'>

#Number to string
num = 100
num_str = str(num)
print("str(100) =", num_str)
print("Type of num_str:", type(num_str))  # <class 'str'>

