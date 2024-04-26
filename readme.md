# Generic Stabilizers for Actions of Algebraic Groups
## A resource for the computational search of generic stabilizers

Given the action of an algebraic group $G$ on a variety $Y$, one of the most fundamental ways to understand the action is to determine its generic behaviour, if it exists. Informally, there is a generic behaviour if there is an open dense subset of the variety where the action behaves the same on all elements.

More precisely, there is a generic stabilizer $S\leq G$ for the action of $G$ on $Y$, if there is a dense open subset $U$ of $Y$ such that for all $u\in U$ the stabilizer $G_u$ (the isotropy group of $u$) is $G$-conjugate to $S$.

## Using MAGMA

Magma is a computer algebra software that can be extremely helpful to execute computations for algebraic groups over finite fields. The name of the game is **guess the generic stabilizer** by computing stabilizers over small finite fields.

## In this resource, I share my strategies and code I have used to tackle this question.