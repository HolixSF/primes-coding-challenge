# Funding Circle Prime Table Challenge

## Overview
Write a program that prints out a multiplication table of the first 10 prime numbers.

* The program must run from the command line and print one table to STDOUT.

* The first row and column of the table should have the 10 primes, with each cell

containing the product of the primes for the corresponding row and column.
## Usage
* Run the following to install dependencies
  `$ bundle install`

* To run the program with default table size
  `$ ./runner.rb`

* For optional usage pass [--help] flag
  `$ ./runner.rb --help`

## Testing
* Tests are ran using RSpec
  `$ rspec spec -fd --color`
