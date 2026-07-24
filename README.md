
students = []
def add_student():
    roll = input("Enter Roll Number: ")
    name = input("Enter Name: ")
    age = input("Enter Age: ")
def view_students():
    if len(students) == 0:
        print("No student records found.\n")
    else:
        print("\nStudent Records")
        print("-" * 30)
        for s in students:
            print(f"Roll: {s['Roll']}")
            print(f"Name: {s['Name']}")
            print(f"Age: {s['Age']}")
            print("-" * 30)
def search_student():
    roll = input("Enter Roll Number to Search: ")
def delete_student():
    roll = input("Enter Roll Number to Delete:")
while True:
    print("\n===== Student Management System =====")
    print("1. Add Student")
    print("2. View Students")
    print("3. Search Student")
    print("4. Delete Student")
    print("5. Exit")
