# verk2_Javascript

1. 

2. 

3. 

4. 

5. 

6. 
      ´´´ javascript
      var savingsAccount = {
    balance: 1000,
    interestRatePercent: 1,
    deposit: function addMoney(amount) {
        if (amount > 0) {
            savingsAccount.balance += amount;
        }
    },
    withdraw: function removeMoney(amount) {
        var verifyBalance = savingsAccount.balance - amount;
        if (amount > 0 && verifyBalance >= 0) {
            savingsAccount.balance -= amount;
        }
    },
    
    summary: function printAccountSummary() {
        return "Welcome! \n Your balance is currently $" + savingsAccount.balance + " and your interest rate is " + savingsAccount.interestRatePercent+ "%"
    }
    
};
´´´
7. 

8. 

9. 

10. 
