# dadu
class Student1:
    college = "ABC University"

    def __init__(self, name):
        self.name = name

    def __str__(self):
        return f"Name: {self.name}, College: {self.college}"

s1 = Student1("krishna")
print(s1.name, s1.college)
print(Student1("lmn"))
