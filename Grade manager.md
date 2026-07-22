name = input("Enter your Name ")
total = int(input("Enter your marks out of 500 "))

percentage = (total/500)*100

if percentage >= 90:
    grade = "A+"
elif percentage >= 80:
    grade = "A"
elif percentage >= 70:
    grade = "B"
elif percentage >= 60:
    grade = "B-"
else:
    grade = "F"

print("\n----Student Report----")
print(f"Name: {name}")
print(f"Grade: {grade}")


if grade == "F":
    remarks = "Need improvement"
else:
    remarks = "You Passed!"
print(f"Remarks:{remarks}")
