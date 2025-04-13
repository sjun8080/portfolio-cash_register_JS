This JavaScript-based app simulates a basic cash register system. It calculates and returns the correct change based on the price of an item, cash received, and the current contents of the cash drawer.

How It Works

Enter a price and amount paid.

Click Purchase to see:

The correct change due using the largest denominations first.

The status of the register: OPEN, CLOSED, or INSUFFICIENT_FUNDS.

 Example Statuses

OPEN: Enough money to return change; drawer still has cash left.

CLOSED: Exact change returned; drawer is now empty.

INSUFFICIENT_FUNDS: Not enough money in the drawer to return correct change.

Features

Calculates change down to the penny

Handles rounding issues with .toFixed(2)

Real-time drawer update with each transaction

Status messages displayed clearly to the user

 Learning Highlights

DOM manipulation and event listeners

Floating-point precision handling in JS

Array iteration with .reduce(), .map(), .push(), and more

Conditional logic for financial transaction
