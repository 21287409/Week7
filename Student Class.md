class Student():
    def __init__(self, surname, firstName, stu_num, course):
        self.a=firstName
        self.b=surname
        self.c = stu_num
        self.d = course

    def showDetails(self):
        print("Name:", self.a)
        print("Surname:", self.b)
        print("Student Number:", self.c)
        print("Course:", self.d)

student1 = Student("Bob", "Smith", 23556981, "Computing")
student1.showDetails()

print()

student2 = Student("Garry", "Wall", 22597812, "Geography")
student2.showDetails()

print()

student3 = Student("Merry", "Pike", 55129948, "History")
student3.showDetails()
