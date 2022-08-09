- 👋 Hi, I’m @AnandKumarKarn
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
AnandKumarKarn/AnandKumarKarn is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Cus1 = {'Accno':1001, 'Name': 'Ramesh', 'Balance':50000}
Cus2 = {'Accno':1002, 'Name': 'lamesh', 'Balance':50000}
Cus3 = {'Accno':1003, 'Name': 'samesh', 'Balance':50000}
Cus4 = {'Accno':1004, 'Name': 'mamesh', 'Balance':50000}
Cus5 = {'Accno':1005, 'Name': 'kamesh', 'Balance':50000}

Account_number = int(input('Enter Your Account Number : '))
if Account_number == Cus1['Accno']:
    print(Cus1['Name'],Cus1['Balance'])

    print('1. Withdraw')
    print('2. Deposit')
    print('3. Balance')
    
    option = int(input('Enter Your Option : '))
    if option == 1:
        print('Enter Withdraw Amount')
        Withdraw_Amt = int(input())
        if Withdraw_Amt <= Cus1['Balance']:
            print('withdraw Amount successfull : Rs.',Withdraw_Amt)
            print('Balance Amount : ',Cus1['Balance']-Withdraw_Amt)
        else:
            print('Insufficient Amount')

    elif option == 2:
        print('Enter Deposit Amount : ')
        Deposit = int(input())
        Balance_Amount = Deposit+ Cus1['Balance']
        print('Balance_Amount : ',Balance_Amount)

    elif option == 3:
        print(Cus1['Balance'])
    else:
        print('invalid............')

if Account_number == Cus2['Accno']:
    print(Cus2['Name'],Cus2['Balance'])

    print('1. Withdraw')
    print('2. Deposit')
    print('3. Balance')
    
    option = int(input('Enter Your Option : '))
    if option == 1:
        print('Enter Withdraw Amount')
        Withdraw_Amt = int(input())
        if Withdraw_Amt <= Cus2['Balance']:
            print('withdraw Amount successfull : Rs.',Withdraw_Amt)
            print('Balance Amount : ',Cus2['Balance']-Withdraw_Amt)
        else:
            print('Insufficient Amount')

    elif option == 2:
        print('Enter Deposit Amount')
        Deposit = int(input())
        Balance_Amount = Deposit+ Cus2['Balance']
        print('Balance_Amount : ',Balance_Amount)
    elif option == 3:
        print('Enter Balance Amount')
    else:
        print('invalid............')

if Account_number == Cus3['Accno']:
    print(Cus3['Name'],Cus3['Balance'])

    print('1. Withdraw')
    print('2. Deposit')
    print('3. Balance')
    
    option = int(input('Enter Your Option : '))
    if option == 1:
        print('Enter Withdraw Amount')
        Withdraw_Amt = int(input())
        if Withdraw_Amt <= Cus3['Balance']:
            print('withdraw Amount successfull : Rs.',Withdraw_Amt)
            print('Balance Amount : ',Cus3['Balance']-Withdraw_Amt)
        else:
            print('Insufficient Amount')

    elif option == 2:
        print('Enter Deposit Amount')
        Deposit = int(input())
        Balance_Amount = Deposit+ Cus3['Balance']
        print('Balance_Amount : ',Balance_Amount)
    elif option == 3:
        print('Enter Balance Amount')
    else:
        print('invalid............')

if Account_number == Cus4['Accno']:
    print(Cus4['Name'],Cus4['Balance'])

    print('1. Withdraw')
    print('2. Deposit')
    print('3. Balance')
    
    option = int(input('Enter Your Option : '))
    if option == 1:
        print('Enter Withdraw Amount')
        Withdraw_Amt = int(input())
        if Withdraw_Amt <= Cus4['Balance']:
            print('withdraw Amount successfull : Rs.',Withdraw_Amt)
            print('Balance Amount : ',Cus4['Balance']-Withdraw_Amt)
        else:
            print('Insufficient Amount')

    elif option == 2:
        print('Enter Deposit Amount')
        Deposit = int(input())
        Balance_Amount = Deposit+ Cus4['Balance']
        print('Balance_Amount : ',Balance_Amount)
    elif option == 3:
        print('Enter Balance Amount')
    else:
        print('invalid............')

if Account_number == Cus5['Accno']:
    print(Cus5['Name'],Cus5['Balance'])

    print('1. Withdraw')
    print('2. Deposit')
    print('3. Balance')
    
    option = int(input('Enter Your Option : '))
    if option == 1:
        print('Enter Withdraw Amount')
        Withdraw_Amt = int(input())
        if Withdraw_Amt <= Cus5['Balance']:
            print('withdraw Amount successfull : Rs.',Withdraw_Amt)
            print('Balance Amount : ',Cus5['Balance']-Withdraw_Amt)
        else:
            print('Insufficient Amount')

    elif option == 2:
        print('Enter Deposit Amount')
        Deposit = int(input())
        Balance_Amount = Deposit+ Cus5['Balance']
        print('Balance_Amount : ',Balance_Amount)
    elif option == 3:
        print('Enter Balance Amount')
    else:
        print('invalid............')
