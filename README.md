- The operating environment is magma.
- Due to the limitations of the Magma version and the limited knowledge of Magma by program writers, these programs are not flexible for all parameters. But these programs basically cover the typical case of all results.
- In addition to the readme file, there are a total of 7 magma program files. Readers can identify the program they want by the file name.

## Algorithm "Verification Construction III.1"
### function $CsA3(t)$

Functionality: Used to obtain a constant weight code $A_t^{w+1}=A_3^3$ in Construction III.1(1).

Input: a positive integer $t$. 

Output: a constant weight code $A_t^{w+1}=A_3^3$ in Construction III.1(1) with length $w+1=3$, minimum distance $D=2$ and constant weight $2t$.


### function $DisCk(A)$

Functionality: Used for checking the minimum distance of code $A$.

Input: a code $A$.

Output: $1$, if the minimum distance of $A$ is $D=2$; $0$, otherwise.


### function $WeiCk(A)$

Functionality: Used for checking the constant weight of $A$.

Input: a code $A$.

Output: $2t$, if $A$ has constant weight $2t$; $0$, otherwise.


### function $SizCkb(t,At3)$

Functionality: Used for checking the size of $At3$.

Input: a positive integer $t$ and code $A_t^{w+1}=A_t^3$.

Output: $1$, if the results about the size of $A_t^3$ in Theorem III.1 are correct; $0$, otherwise.


### function $CsB3(t)$

Functionality: Used to obtain a constant weight code $B_t^{w+1}=B_3^3$ in Construction III.1(2).

Input: positive integer $t$.

Output: a constant weight code $B_t^{w+1}=B_3^3$ in Construction III.1(2) with length $w+1=3$, minimum distance $D=2$ and constant weight $2t+1$.


### function $DisCk(B)$

Functionality: Used for checking the minimum distance of code $B$.

Input: a code $B$.

Output: $1$, if the minimum distance of $B$ is $D=2$; $0$, otherwise.


### function $WeiCk(B)$

Functionality: Used for checking the constant weight of $B$.

Input: a code $B$.

Output: $2t+1$, if $B$ has constant weight $2t+1$; $0$, otherwise.


### function $SizCkb(t,Bt3)$

Functionality: Used for checking the size of $Bt3$.

Input: a positive integer $t$ and code $B_t^{w+1}=B_t^3$.

Output: $1$, if the results about the size of $B_t^3$ in Theorem III.1 are correct; $0$, otherwise.



## Algorithm "Verification Construction IV.1"

### function $CsAt4(t)$

Functionality: Used to obtain a constant weight code $A_t^{w+1}=A_t^4$ in Construction IV.1.

Input: a positive integer $t\geq3$.

Output: a constant weight code $A_t^{w+1}=A_t^4$ in Construction IV.1 with length $w+1=4$, distance $D=2$ and constant weight $Dt=2t$.


### function $DisCk(A)$

Functionality: Used for checking the minimum distance of code $A$.

Input: a code $A$. 

Output: $1$, if the minimum distance of $A$ is $D=2$; $0$, otherwise.


### function $SizCk(t,At4)$

Functionality: Used for checking the size of $At4$.

Input: a positive integer $t\geq3$ and code $A_t^4$.

Output: $1$, if the results about the size of $A_t^4$ in Theorem IV.1 are correct; $0$, otherwise.


### function $WeiCk(A)$

Functionality: Used for checking the constant weight of $A$.

Input: a code $A$.

Output: $2t$, if A has constant weight $Dt=2t$; $0$, otherwise.




## Algorithm "Verification Construction IV.2"
It is similar to **Algorithm "Verification Construction IV.1"**.



## Algorithm "Verification Construction IV.3"
### function $CsBt5(t)$

Functionality: Used to obtain a constant weight code $B_t^{w+1}=B_t^5$ in Construction IV.3.

Input: a positive integer $t\geq1$.

Output: a constant weight code $B_t^{w+1}=B_t^5$ in Construction IV.3 with length $w+1=5$, distance $D=2$ and constant weight $2t+1$.


### function $DisCk(B)$

Functionality: Used for checking the minimum distance of code $B$.

Input: a code $B$.

Output: $1$, if the minimum distance of $B$ is $D=2$; $0$, otherwise.


### function $SizCk(t,Bt5)$

Functionality: Used for checking the size of $Bt5$.

Input: a positive integer $t$ and code $B_t^{w+1}=B_t^5$. 

Output: $1$, if the results about the size of $B_t^5$ in Theorem IV.3 are correct; $0$, otherwise.


### function $WeiCk(B)$

Functionality: Used for checking the constant weight of $B$.

Input: a code $B$.

Output: $2t+1$, if B has constant weight $2t+1$; $0$, otherwise.



## Algorithm "Verification Construction V.1"

### function $Btw(t,w,D)$

Functionality: Used to obtain a constant weight code $B_t^{w+1}$ in Construction V.1.

Input: positive integers $t=3$, $w=5$ and even $D\geq 4$. 

Output: a constant weight code $B_t^{w+1}$ in Construction V.1 with length $w+1=6$, distance $D$ and constant weight $3D+D/2$..

### function $DisCk(B)$

Functionality: Used for checking the minimum distance of code $B$.

Input: a code $B$. 

Output: $1$, if the minimum distance of $B$ is $D=4$; $0$, otherwise.

### function $SizCk(t,Btws)$

Functionality: Used for checking the size of $Btws$.

Input: a positive integer $t$ and code $B_t^{w+1}$. 

Output: $1$, if the results about the size of $Btws$ in Theorem V.2 are correct; $0$, otherwise.

### function $WeiCk(B)$

Functionality: Used for checking the constant weight of $B$.

Input: a code $B$.

Output: $3D+D/2$, if $B$ has constant weight $3D+D/2$; $0$, otherwise.

## Implementation Algorithm 1 for $w=5$
### function $FINDCODE(w,t)$

Functionality: Used to obtain a constant weight code $A_t^{w+1}(Y)$ in Algorithm 1.

Input: integers $w$ and $t$ such that $w=5$ and $t>=3$.

Output: a constant weight code $A_t^{w+1}(Y)$ with length $w+1=5$, distance $D=2$ and constant weight $2t$. 

### function $DisCk(A)$

Functionality: Used for checking the minimum distance of code $A$.

Input: a code $A$.

Output: $1$, if the minimum distance of $A$ is $D=2$; $0$, otherwise.

### function $WeiCk(A)$

Functionality: Used for checking the constant weight of $A$.

Input: a code $A$.

Output: $2t$, if $A$ has constant weight $2t$; $0$, otherwise.

## Implementation Algorithm 1 for $w=6$ and $7$
**These two cases are similar to the case of $w=5$.**




