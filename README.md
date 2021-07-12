# WalletifAI
Detect income from a someones banking history

Attached document here provides 6 months bank transactions on one bank with different bank accounts e.g. checking, saving, credit, e.g.

We would like you to write a piece of code in Python that detects user incomes and income pay cycles. Note that user has multiple incomes e.g. paycheck and rent income. Also few useful information:

    1. keep in mind that negative amounts are deposited to the account which make the positive amounts to be expenses.
    2. Some transactions such as credit cards payments or refunds should not show up as income.
    3. Incomes should not be calculated per account, remember that this file represents 6-months transactions of someone's back account. It means they can have different accounts, e.g. checking, saving, credit, but income doesn't go to all of them.
    4. Amounts are in cents. For example, $3455 is $34.45
    5. Your final findings should not represent amounts higher than $6,000 per income.
    
Clarifications about memo:
1. WWW TRANSFER: Could be any sort of transfer, fro, checking to saving or vice versa.
2. WWW TRF DDA: Any sort of transfer between accounts, internally
3. WWW PAYMENT: could be a credit card payment
4. WWW3RD PTY DEP: I'm not sure what that is, shouldn't matter
