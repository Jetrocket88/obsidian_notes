[[Digital Electronics]]

## Flashcards
#flashcards/eee/digital_electronics 

What is the canonical form of a function?
?
The fully expanded form of a function
For example:
$$
f = B + A\bar{C}\\[13pt]
f = \bar{A}B\bar{C} + \bar{A}BC + A\bar{B}\bar{C} + AB\bar{C} + ABC
$$

What are the two properties about the canonical form?
?
The form is unique for each boolean function
All terms and expressions contain all variables

What are the two examples of the canonical form that we care about?
?
Sum of Products (SoP)
Product of Sums (PoS)

What are the terms in the SoP expression referred to as?
?
Minterms


What are the terms in the PoS expression referred to as?
?
Maxterms

Each term in SoP represents {} in the truth table, and each term in PoS represents {} in the truth table?
?
1, 0


How do we find the PoS from the truth table?
?
1. Find the all the terms where the function output was 0
2. Find the DeMorgan's inverse of these terms
3. Multiply those terms together

How do we convert between SoP and PoS?
?
1. First convert to the short form equivalent
2. Replace the indexes with the indexes that are missing
3. (Optionally) Convert back to long form from shorthand 


What is one of the strange properties of K-maps that we must take into consideration while solving? 
?
That we can wrap around the edges

Up to how many variables are K-maps useful?
?
4