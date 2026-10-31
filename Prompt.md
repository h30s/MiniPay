### Task 1 – Rename

Rename calculateWalletBalance to calcBalance 
everywhere in the project, including imports,
exports, tests, documentation and comments.

Do not change behavior. Run relevant tests
and TypeScript checks.


### Task 2 – Fix the money calculation bug

Users report that adding an expense increases
their wallet balance instead of decreasing it.

Example:
Starting balance: ₹1,000
Expense: ₹200
Incorrect balance: ₹1,200
Expected balance: ₹800

Find the root cause, fix it, and add regression
tests. Do not delete or weaken existing tests.
Run relevant tests and report actual results.


### Task 3 – Add an API

Add GET /api/transactions/summary.

Return:
- Total income
- Total expenses
- Remaining wallet balance

Support monthly date filtering and follow
existing route/controller/service patterns.

Add appropriate tests and handle empty data.


### Task 4 – Write tests

Write comprehensive tests for
src/services/transactionService.ts.

Cover:
- Adding income
- Adding expenses
- Invalid amounts
- Missing transactions
- Deleting transactions
- Wallet balance recalculation

Follow existing test conventions.
Do not weaken existing tests.

Run the tests and report actual results.


### Task 5 – Refactor

Refactor src/controllers/transactionController.ts
into smaller, focused modules.

Preserve all existing API behavior,
response formats, validation and error handling.

Do not delete or weaken existing tests.
Run the complete test suite and TypeScript checks.