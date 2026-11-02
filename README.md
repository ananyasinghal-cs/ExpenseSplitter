# ExpenseSplitter
A Java-based application for tracking and splitting shared group expenses.

## Project Goal
ExpenseSplitter helps groups manage shared expenses by recording who paid, calculating each person's share, and keeping track of who owes whom.

## MVP Scope
- Add and remove group members.
- Record expenses with a description, amount, payer, and participants.
- Split expenses equally among selected participants.
- Calculate each person's total share and balance.
- Display who owes money and who is owed money.
- Save and load group members and expense records using CSV files.

## Future Plans
- Allow custom expense splits using specific amounts or percentages.
- Support multiple groups for different trips or occasions.
- Allow users to edit previously recorded expenses.
- Simplify settlements by minimizing the number of payments between people.
- Export or share final expense summaries.

## Tech Stack
- Language: Java
- Packages and classes: `java.math.BigDecimal`, `java.util`, and `java.nio.file`
- Data Storage: CSV files
- Data Entry: Manual input through a command-line interface
- Version Control: Git and GitHub
