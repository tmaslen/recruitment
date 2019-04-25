# Supermarket sweep

The aim of this exercise is to see how you work together with a colleague.  You will not be scored based on the completedness of this exercise.  We're looking at how you understand a problem, interpret requirements and work with others to build a solution.  You do not need to write and plan everything, but we do expect you to assertively drive the conversation with the developer that you are pairing with.

## The problem

Create a checkout object that calculates the total price of a number of items. 

In a normal supermarket, things are identified using Stock Keeping Units, or SKUs. In our store, we'll use individual letters of the alphabet (A, B, C, and so on). Our goods are priced individually. In addition, some items are multipriced: buy n of them, and they'll cost you y pence. For example, item 'A' might cost 50 pence individually, but this week we have a special offer: buy three 'A's and they’ll cost you £1.30.

## Requirements:

This week's prices are:

| Item     | Unit Price | Special Price |
|----------|------------|---------------|
| Apple    | 50         | 3 for 130     |
| Broccoli | 30         | 2 for 45      |
| Cabbage  | 20         |               | 
| Date     | 15         |               |

 * Our checkout accepts items in any order, so that if we scan a B, an A, and another B, we'll recognize the two B's and price them at 45p (for a total price so far of 95p).
 * Because the pricing changes frequently, we need to be able to pass in a set of pricing rules each time we start handling a checkout transaction.

 Do think about:

 * Understanding the problem
 * Working together with your code partner
 * Communicating ideas and solutions with your code partner

Don't worry about:

 * Knowing everything (Google is your friend)
 * Unit testing (unless you've ran out of something to do or you want to drive the session via TDD).

The exercise is timeboxed to 1 hour.