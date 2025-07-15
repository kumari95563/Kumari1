class User(object):
def __init__(self, firstname):
self.firstname = firstname
@property
def name(self):
return self.firstname
class Animal(object):
pass
class Fox(Animal):
name = "Fox"
class Bear(Animal):
name = "Bear"
# Use the .name attribute (or property) regardless of the type
for a in [User("SampleOutput"), Fox(), Bear()]:
print(a.name)
numbers = [1, 2, 3]
result = isinstance(numbers, list)
print(numbers,'instance of list?', result)
result = isinstance(numbers, dict)
print(numbers,'instance of dict?', result)
result = isinstance(numbers, (dict, list))
print(numbers,'instance of dict or list?', result)
number = 5
result = isinstance(number, list)
print(number,'instance of list?', result)
result = isinstance(number, int)
print(number,'instance of int?', result)
