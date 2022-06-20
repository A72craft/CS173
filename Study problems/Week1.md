# Logic 
## problem 1

Let D be dinosaurs, a(x) be x eat meat, b(x) be x has sharp teeth, c(x) be x is huge

The claim will be $\forall x \in D$, $a \implies b \land \lnot c$

which is $\forall x \in D$, $(\lnot a \lor b) \land (\lnot a \lor \lnot c)$

##### Negation

$\exists x \in D$, a$\land (\lnot b \lor c)$

There exists a dinosaur D where D eats meat but D does not have sharp teeth or D is huge

##### contrapositive 

$\forall x \in D$, $\lnot b \lor  c \implies \lnot a$

For all dinosaur D, if D does not have sharp teeth or D is huge, then D does not eat meat

## problem 2b

For (p$\implies$q)$\land$r:

($\lnot$p$\lor$q)$\land$r

For (p$\land$q)$\implies$r

$\lnot$(p$\land$q)$\lor$r

if p, q, r are false

($\lnot$p$\lor$q)$\land$r will be false

$\lnot$(p$\land$q)$\lor$r will be true

It is clear that these two are not the same

# Proof

## problem 1

Let x and $\frac {y+1} 3$ be rational, and x $\not=$ 0 

By the definition of rational numbers, x = $\frac a b$, and  $\frac {y+1} 3$ = $\frac c 3$, where a, b, c are integers.

Since y = c - 1, and integer minus 1 must still be an integer, y is an integer, which can be expressed with $\frac y 1$

$\frac 1 x$ = $\frac b a$, since b and a are integers, $\frac 1 x$ must be rational

$\frac 1 x$ + y = $\frac b a$ + $\frac y 1$ = $\frac {b+ay} a$. Since a, b, y are integers, $\frac {b+ay} a$ must be rational

Thus, $\frac 1 x$ + y is rational

## problem 3

Let x, y be real numbers, and x ⊘ y = 2(x + y)

Consider x = 1, y = 1, z = 0

(x ⊘ y) ⊘ z = 2*((4)+0) = 8

x ⊘ ( y ⊘ z) = 2*(1+(2)) = 6

Thus (x ⊘ y) ⊘ z $\not=$ x ⊘ (y ⊘ z)

## problem 4 

Let p, r, t be real numbers where t$\geq$r

t$\geq$r

Multiply it by 2$p^2$ we got 

2$p^2$t $\geq$ 2$p^2$r 

Add 2ptr to both sides we got

2$p^2$t + 2ptr $\geq$ 2$p^2$r + 2prt

Take the 2pt and 2pr out we got

(2pt)(p + r)$\geq$(2pr)(p + t)

divide it by (p + t)(p + r) we got 

$\frac {2pt}{p+t}$ $\geq$ $\frac {2pr}{p+r}$

By the definition of F(p, r) = $\frac {2pr}{p+r}$, F(p, t)≥F(p, r)

# Number Theory

## problem 1

|x|y|r|
|-|-|-|
|6409|42823|6409|
|42823|6409|4369|
|6409|4369|2040|
|4369|2040|289|
|2040|289|17|
|289|17|0|
|17|0|N/A|

Therefore gcd(6409, 42823) = 17 

## problem 2

The definition of divides is that for integer p, q  p|q is pn = q for some int n

Let p, q, r  be integers, where p|3q and 3q|r 

So by the definition, pn = 3q and 3qm = r for ints n and m

Add both sides together, pn + 3qm = 3q + r

since pn = 3q, the equation can be written as pn + pnm = 3q +r

p(n + nm) = 3q + r

since the sum and product of ints are ints,(n + nm) is an int

Thus the above can be written as p | 3q + r

Thus p|3q + r is true















