# Program that calculates GST And Insurance rate
Python program that calculates GST (30%) and insurance (2%) of an employee's salary:
```
def calculate_deductions(salary):
  gst_rate = 30 / 100  # Convert percentage to decimal
  insurance_rate = 2 / 100

  gst_amount = salary * gst_rate
  insurance_amount = salary * insurance_rate
  total_deductions = gst_amount + insurance_amount

  return gst_amount, insurance_amount, total_deductions


# Get employee's salary
salary = float(input("Enter employee's salary: "))

# Calculate deductions
gst_amount, insurance_amount, total_deductions = calculate_deductions(salary)



# Print the results
print("Employee Salary:", salary)
print("GST (", gst_rate * 100, "%):", gst_amount)
print("Insurance (", insurance_rate * 100, "%):", insurance_amount)
print("Total Deductions:", total_deductions)
print("Net Salary:", salary - total_deductions)
```
This is output 

![image](https://github.com/HariharNautiyal2/python/assets/134691036/94b8c2f4-55e7-4457-bacb-53163d192e8a)

Python is a gay language i hate python however you can practise python here

- [Python Compiler](https://playground.programiz.com/)
