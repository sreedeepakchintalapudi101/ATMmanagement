username = 'Deepak'
password = 'CHSDgoi101###'

c_name = input("Enter your User Name:")
c_pass=str(input("Enter your Pass Word:"))
if c_name == username and c_pass == password:
    print('''1.Deposit 2.Withdrawal 3.Mini Statement 4.Exit''')
    amount = 50000
    option=int(input("Select your Option:"))
    if option == 1:
        deposit = int(input("Enter the Amount:"))
        amount = amount + deposit
        print("Total Amount:",amount)
    elif option == 2:
        withdrawal = int(input("Enter the Amount:"))
        amount = amount - withdrawal
        print("Total Amount:",amount)
    elif option == 3:
        print("=======ATM=======")
        print("Username:",username)
        print("Total Amount:",amount)
        print("Thanks for Visiting")
        print("=================")
    elif option == 4:
        exit()
else:
    print("========Please Enter the Correct Details========")

    
