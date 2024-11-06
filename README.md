# Testing-Verification-Bank-Account

We are using this Bank Account in Java for testing Preconditions contracts

for runnig the JUnit Test over the project oyu need to click Right button over the project and select Run As,
then open Run Configuration, then switch to the Arguments tab and check if your Virtual Machine(VM) Arguments has this -->
**
-ea
-javaagent:cofoja.asm.jar
**
After that you are eligable to Run the JUnit test without having Test Failures

****Additional Descrtiption****

Class Account is an implementation of a bank account. Instances of Account contain a single
variable, balance, to record amount of money in the account. Methods allow the balance
to be altered by withdrawing or depositing funds, and making a transfer from one account to
another.
Tests, defined in AccountTest.java, check the pre-condition part of contracts by running
tests that falsify preconditions. When a pre-condition is checked and evaluates to false, a
PreconditionError exception is thrown, and the test cases expect this with assertThrows.
