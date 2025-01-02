class Student:
    def _init_(self, name, roll_no, age, grade):
        self.name = name
        self.roll_no = roll_no
        self.age = age
        self.grade = grade

    def display_details(self):
        print("Student Details")
        print(f"Name: {self.name}")
        print(f"Roll Number: {self.roll_no}")
        print(f"Age: {self.age}")
        print(f"Grade: {self.grade}")

# Create a student object
student1 = Student("Menakavati P B", 35, 18, "A")

# Display the details of the student
student1.display_details()
