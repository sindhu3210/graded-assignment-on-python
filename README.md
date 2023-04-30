# graded-assignment-on-python

Question 1 - 

Description - Create a small command-line program in Python to calculate the total invoice amount for the below purchases - 

Book - Introduction to Python Programming : Rs 499.00

Book - Python Libraries Cookbook : Rs. 855.00

Book - Data Science in Python : Rs. 645.00


Taxes and additional charges are described as details - 

GST : 12%

Delivery Charges : Rs. 250.00

solution:
book1=499
book2=855
book3=645
tax=12
deliver_charge=250
amount=book1+book2+book3
tax=(amout*tax)//100
total=amount+tax+delivery_charge
print("Amount to be paid",total)

Question 2 - 

Description: Write a program in Python to print the number of unique letters in a string. Only new letters from the string should be counted and not duplicates.

                                  

Input : string1 = "India"

Output : uniqueLetters = i,n,d,a


Input : string1 = "Dedication"

Output : uniqueLetters = d,e,i,c,a,t,o,n

solution:
string=input()
list1=[*string]
new_list=[]
for i in range(len(list1)):
    if list1[i] not in new_list:
        new_list.append(list1[i])
print(new_list)
