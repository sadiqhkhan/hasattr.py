# hasattr.py
#Check if the Class or method have the attr 
class Stud:
    'sadiq is good boy'
    def __init__(self,roll_num,grade):
        self.roll_no = roll_num
        self.grade = grade

    def display(self):
        print("roll NO:",self.roll_no, "grade",self.grade)


if __name__ == "__main__":
    s = Stud(34,'s')
    s.age = 17
    print(hasattr(s,'age'))
    s.display()
    print(Stud.__doc__)
    print(type(s))
