# simplify_and_combine_like_radicals
Python program that simplifies and combine like radicals.
Program uses Prime Factorization to simplify radicals.

# Usage
A radical is represented by a list of 3 elements, the first element is the radical factor, the second element is the radicand, and the third element is the index.
For example, the radical 4 * sqrt(3) would be represented by the list [4, 3, 2],
notice that the index is 2 because we take the sqrt in the example.

Program currently simplifies radicals, the three cases it works on currently are,
where the radicand is a numeral, i.e. 100, or the radicand is a literal, i.e. 'x',
or the radicand is a numeral and literal combination, i.e. '9x'.

Program can simplifiy a bunch of radicals at the same time, this is done by storing all
the radicals you wish to simplify in a list of lists, for example:
radicals = [[4, 3, 2], [1, 75, 2], [1, 'x', 2]]

I am currently working on making the program combine like radicals.

# Installation
Clone the repo and run python3 main.py 
