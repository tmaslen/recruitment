# Rage against the fruit machine

The aim of this exercise is to see how you work together with a colleague.  You will not be scored based on the completedness of this exercise.  We're looking at how you understand a problem, interpret requirements and work with others to build a solution.  You do not need to write and plan everything, but we do expect you to assertively drive the conversation with the developer that you are pairing with.

## The problem

Please pair for 1 hour to create a command line virtual fruit machine. To make things easier instead of symbols we are going to use characters: A, B, C, D, E. Implement a basic machine, along with the concept of a player who has a fixed amount of money to play the machine.

Each time a player plays our fruit machine we display four 'slots' each with a randomly selected character in each slot.

## Requirements:

 * The user starts by stating how much money they have.
 * Keep the user aware of how much money they have left.
 * A single play costs the user 20p.
 * The fruit machine starts with £20 in it
 * If the characters in each slot are the same then the player wins the jackpot which is £20.
 * If each slot has a different character then the machine should pay out £10.
 * If a given play results in two or more adjacent slots containing the same character then the machine should pay out a prize of 5 times the cost of a single play.
 * If the machine does not have enought money to pay a prize it should credit the player with a number of free plays equal to the difference between the full prize and the amount of money available. This does not affect a jackpot win.

Do think about:

 * Understanding the problem
 * Working together with your code partner
 * Communicating ideas and solutions with your code partner

Don't worry about:

 * Knowing everything (Google is your friend)
 * Unit testing (unless you've ran out of something to do)

The exercise is timeboxed to 1 hour.