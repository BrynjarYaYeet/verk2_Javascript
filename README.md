# verk2_Javascript

1. 
   ```javascript
   let eg = {
   nafn: "Brynjar"   
   kt: 2110012590   
   heimilisf: "Kvistavellir8"   
   heimas: 5812345   
   gsm: [7654321, 6942069]      
   };
   ```
2. 
   ```javascript
   for (let abc in uppl) {
   console.log(abc)
   }
   ```
   ```javascript
   for (let abc in uppl) {
   console.log(uppl[abc])
   }
   ```

3. 
   ```javascript
   uppl.adferd = function(){
   return "Ég heiti " + uppl.nafn +" og ég er 17 ára"      
   };
   
   
   uppl.adferd()
   ```
4. 
   ```javascript
   console.log(family.parents.fathers[1]["name"]);
   ```
5. 

6. 
      ```javascript
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
      ```
7. 

8. 

9. 

10. 
