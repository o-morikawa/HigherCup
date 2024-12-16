# HigherCup

This is a Mathematica code for computing higher cup products by Steenrod.
Our notation is as follows.
```mathematica
A^{(p)} ⌣_i B^{(q)} ⌣_j C^{(r)}
= Cup[A[p], B[q], C[r]][{i, j}]
```
(Error for wrong numbers of forms and cups.)
Associativity is supported in the appropriate way; an overall factor will be factorized.
The exterior derivative is implemented as $d=$```Del``` as the usual Mathematica code;
here $d$ can act on forms or ```Cup```, which mixes some other forms and higher cups appropriately,
it is insurely nilpotent and satisfies homomorphism.
The Leibniz rule holds.
