## Experiment No: 1d – Conditional Statements- Checking

## AIM  
To Write a Python program to print the account balance after withdrawal.
savingsbalance=5000
## ALGORITHM  
1. Start
2. Set savingAmt = 5000
3. Get input from the user for withdrawAmt (convert input to integer)
4. Calculate bal = savingAmt - withdrawAmt
5. If withdrawAmt > 5000, then:Print "Insufficient balance"
6. Else:Print "Account Balance:" followed by bal
7. End

## PROGRAM
```python
savingAmt=5000
withdrawAmt=int(input())
bal=savingAmt-withdrawAmt

if withdrawAmt>5000 :
	print ("Insufficient balance")
else:
    print("Account Balance:",bal)
	
```

## OUTPUT
![Screenshot 2025-04-26 143654](https://github.com/user-attachments/assets/f8bc7b9d-163a-444e-a4ee-a72988fc0ca1)


## RESULT
Thus the python program to print the account balance after withdrawal has been implemented and executed successfully.
