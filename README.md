class bank():
    def __init__self(self,balance):
        self.__balance=balance
    def deposite(self,amount):
        self.__balance+=amount
    def withdraw(self,amount):
        if amount>self.__balance:
            print("In sufficient balance")
        else:
            self.__balance-=amount
    def getbal(self):
        return self.__balance
obj=bank(10000)
obj.deposite(500)
print(obj.getbal())
obj.withdraw(5016)
print(obj.getbal())
