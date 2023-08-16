- The operating environment is magma.
- Due to the limitations of the Magma version and the limited knowledge of Magma by program writers, these programs are not flexible for all parameters. But these programs basically cover the typical case of all results.
- In addition to the readme file, there are a total of 7 magma program files. Readers can identify the program they want by the file name.

## Algorithm "Verification Construction III"
### function CsB3(t)

Input: a positive integer t. 

Output: a constant weight code B_t^3 in Construction III.1(1) with w=2 and D=2.

### function CsA3(t)

Input: positive integer t.

Output: a constant weight code A_t^3 in Construction III.1(2) with w=2 and D=2.

### function DisCk(B)

Input: a code B.

Output: 1, if the minimum distance of B is greater than D; 0, otherwise.

### function WeiCk(B)

Input: a code B.

Output: an integer s greater than 1, if B has constant weight s; 0, otherwise.

### function SizCkb(t,Bt3)
Input: a positive integer t and code Bt3.

Output: 1, if the results about the size of B_t^3 in Theorem III.1 are correct; 0, otherwise.

### function SizCka(t,At3)
Input: a positive integer t and code At3.

Output: 1, if the results about the size of A_t^3 in Theorem III.1 are correct; 0, otherwise.

## Algorithm "Verification Construction IV.1"

### function CsBt4(t)
Input: a positive integer t.

Output: a constant weight code Bt4 in Construction IV.1 with w=3 and D=2.

### function DisCk(B)
Input: a code B. 

Output: 1, if the minimum distance of B is greater than D; 0, otherwise.

### function SizCk(t,Bt4)
Input: a positive integer t and code Bt4.

Output: 1, if the results about the size of Bt4 in Theorem IV.1 are correct; 0, otherwise.

### function WeiCk(B)
Input: a code B.

Output: an integer s greater than 1, if B has constant weight s; 0, otherwise.

## Algorithm "Verification Construction IV.2"
It is similar to **Algorithm "Verification Construction IV.1"**.

## Algorithm "Verification Construction IV.3"
### function CsAt5(t)
Input: a positive integer t.

Output: a constant weight code At5 in Construction IV.3 with w=4 and D=2.

### function DisCk(B)
Input: a code B.

Output: 1, if the minimum distance of B is greater than D; 0, otherwise.

### function SizCk(t,At5)
Input: a positive integer t and code At5. 

Output: 1, if the results about the size of At5 in Theorem IV.3 are correct; 0, otherwise.

### function WeiCk(B)
Input: a code B.

Output: an integer s greater than 1, if B has constant weight s; 0, otherwise.

## Algorithm "Verification Construction V.1"

### function Atw(t,w)
Input: integers t,w,D. 

Output: a constant weight code Atw in Construction V.1.

### function DisCk(B)
Input: a code B. 

Output: 1, if the minimum distance of B is greater than D; 0, otherwise.

### function SizCk(t,Atws)
Input: a positive integer t and code Atws. 

Output: 1, if the results about the size of Atws in Theorem V.2 are correct; 0, otherwise.

### function WeiCk(B)
Input: a code B.

Output: an integer s greater than 1, if B has constant weight s; 0, otherwise.

## Implementation Algorithm 1 for w=5
### function FINDCODE(w,t)
Input: integers w and t such that w=5 and t>=3.

Output: a constant weight code Btw(Y) in Algoithm 1 with w=5 and D=2.

### function DisCk(B)
Input: a code B.

Output: 1, if the minimum distance of B is greater than D; 0, otherwise.

### function WeiCk(B)
Input: a code B.

Output: an integer s greater than 1, if B has constant weight s; 0, otherwise.

## Implementation Algorithm 1 for w=6 and 7
**These two cases are similar to the case of w=5.**




