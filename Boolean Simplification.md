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
<!--SR:!2026-11-10,5,230-->

What are the two properties about the canonical form?
?
The form is unique for each boolean function
All terms and expressions contain all variables
<!--SR:!2026-11-10,5,230-->

What are the two examples of the canonical form that we care about?
?
Sum of Products (SoP)
Product of Sums (PoS)
<!--SR:!2026-11-13,8,250-->

What are the terms in the SoP expression referred to as?
?
Minterms
<!--SR:!2026-11-13,8,250-->


What are the terms in the PoS expression referred to as?
?
Maxterms
<!--SR:!2026-11-14,9,250-->

Each term in SoP represents {} in the truth table, and each term in PoS represents {} in the truth table?
?
1, 0
<!--SR:!2026-11-14,9,250-->


How do we find the PoS from the truth table?
?
1. Find the all the terms where the function output was 0
2. Find the DeMorgan's inverse of these terms
3. Multiply those terms together
<!--SR:!2026-11-07,2,230-->

How do we convert between SoP and PoS?
?
1. First convert to the short form equivalent
2. Replace the indexes with the indexes that are missing
3. (Optionally) Convert back to long form from shorthand
<!--SR:!2026-11-14,9,250--> 


What is one of the strange properties of K-maps that we must take into consideration while solving?
?
That we can wrap around the edges
<!--SR:!2026-11-13,8,250-->

Up to how many variables are K-maps useful?
?
4
<!--SR:!2026-11-15,10,270-->