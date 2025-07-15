#strings
#store
a="topu turumu gaddapara"
print(a)





a="pavani's"
b="bestfriend"
c="bhavya"
print(a+b+c)



b="topu turumu gaddapara"
print(b[2])
print(len(b))
c=b.upper()
print(b.upper())
print(c)
d=c.lower()
print(d)
e=c.capitalize()     #capitalize
print(e)
f=c.title()
print(f)



a=" hello , worl,d"
print(a)
print(a.strip()) #strip
print(a.replace("world","pavani")) #replace
print(a.split(","))





a="hello, world, hello"
print(a.count("hello")) #count
print(a.find("world")) #find




a="123456"
print (a.isdigit())
print(a.isnumeric())
b="hello"
print(b.isalpha())
c="hello123"
print(c.isalnum())




a="abc1230"
print(a[::-1]) #reverse



#palindrome
a="abcba"
print(a==a[::-1])



#remove dup from string
a="hello worold"
print(" ".join(sorted(set(a),key=a.index)))



#find the largest word in a string
a="hello all toooopu turum gaddaparaaaaaaas"
print(max(a.split( ),key=len))



#no of words in a string
a="kumari is a thikka fellow"
print(len(a.split()))



#find string contain word start with given letter
a="hello world"
print(a.startswith("hello"))
print(a.endswith("world"))



# converting string in to list
a="hello world"
print(list(a))




a="hello world"
print(list(a))
print(set(a))



#format
name="pavani"
age=20
print(f"my name is {name} and in {age} years old")




#print ascii values in given strings
a="hello world"
ascii=[ord(char) for char in a]
print(ascii)











nt(number,'instance of int?', result)
