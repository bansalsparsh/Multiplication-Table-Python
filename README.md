# Multiplication-Table-Python

n = int(input("Enter number"))

class multiplication:
    attribute = n
    def function(self):
        for i in range(2, self.attribute+1):
            for j in range(1, 11):
                c = i*j
                print(i, "*", j, "=", c)
            print("\n")

m1 = multiplication()

m1.function()
