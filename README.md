# Lovely_Assingment
Assingment_5
# task 1
Student_name = {"lovely":100 , "kim":99 , "john":90 , "Alice":22}

user_input = input("enter the student's name :")


if user_input in Student_name:
    Student_name[user_input] = Student_name[user_input]
    print(user_input, f"  marks : {Student_name[user_input]}")

else:
    print("Student name is not found")



# task 2

original = [1,2,3,4,5,6,7,8,9,10]
print("original:",original)
print( "Extracted First five element of list :", original[0:5])
original1 = original[:5]
original1.reverse()
print("Reverse Extracted Element of list :",original1)
