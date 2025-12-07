1.

    a. 
    5 variable so 2 ^ 5 rows = 32


    b. 
    5 columns for each basic variable: p,q,r,s,t
    2 columns for the negations: not q, not r
    4 columns for partial expressions: p or not q, not r and s, ( not r and s) -> t
    1 column for the whole formula: (p or not q) iff [(not r and s) -> t]
    TOTAL: 12 columns


2.
    one penny, one nickel, one dime, one quarter and one half-dollar
    x = {1, 5, 10, 25, 50}, n = 5
    Total unique combinationss of the entire set is 2 ^ 5 = 32
    Any set with 10, 25, 50 is above or equal to 10 by default, so have to look at all sets of 1 and 5 none of which >= 10
    There are 2 ^ 2 = 4.
    32 - 4 = 28
    So the total is = 28


3. 
    The three equal sized partitions would be 12 items each
    So 12 ^ 12 = 144 * 3

4.
    a. Reflexivity. 
    By the definition of reflexivity: for any a thats an element of S on Q, a is also a relation of a. 
    Therefore according to the relation |a-b| < 1 then |a-a| < 1 and a is an integer. 
    And since|a-a| always equals 0, this relation is reflexive

    b. Symmetry.
    By the definition of symmetry: for any a and b that are elements of S on Q, then the relation |a-b| < 1 and |b-a| < 1.
    By definition of absolute value |a-b| = |b-a| therefore they will both always be the same.
    Therefore it is symmetric.


    c. Transitivity. 
    For any a, b, c that are elements of S on Q, if a R b and b R c, then a R c.
    Therefore, IF |a-b| < 1 AND |b-c| < 1 THEN |a-c| < 1
    If a is 0 and c is any number greater than one, this will be false even if |a-b| < 1.


    d.  Antisymmetric
    For any a and b that are elements of S on Q
    a=.5 and b = 0
    aRb < 1 is True
    bRa < 1 is True
    a = b is not true
    a=b must hold for all values in S.



5.  
    G: “Emily is a LIAR(L).”
    P: “Glenn is a SWEETIE(S).”
    E: “I am a SNEAKY BEAKY(SB).”

    possibilities:
    {E=L, G=S, P=SB}
    * This is TRUE 

    trials to get to true:
    {E=SB, G=L, P=S}
    * FALSE: because if E is sneaky beaky then Glenn is a liar which makes Parker also a liar
    {E=SB, G=S, P=L}
    * FALSE: That would make both parker and glenn wrong
    {E=L, G=SB, P=S}
    * FALSE: Cant be true because Parket is lying about Glenn
    {E=S, G=SB, P=L}
    * FALSE: bevause emily would be lying about herself




6.
    IF a^2 + b^2 = c^2  then  (a is even) and/or (b is even)
    Suppose, to the contrary, that if a^2 + b^2 = c^2  then  (a is odd) or (b is odd)

    Assume a^2 + b^2 = c^2 and both a and b are odd.
    Then we can write:
    a = 2m + 1
    b = 2n + 1
    for some integers m, n.

    Compute squares:
        a^2 = (2m+1)^2 = 4m^2 + 4m + 1
        b^2 = (2n+1)^2 = 4n^2 + 4n + 1
        a^2 + b^2 = 4m^2 + 4m + 4n^2 + 4n + 2
        factor out 2 and you get the form 2(2m^2 + 2m + 2n^2 + 2n + 1)


    The definition for an even number is 2(k) and this takes the form of that, which is an even number.
    Not reall


7.

    Vertices: 
    V = {v1, v2, v3, v4}

    Edges: 
    E = {v1v2, v2v3, v3v1, v1v4}f : (Z × Z) -> Z defined by: f(x, y) = max(x, y) − max(x^3, y^2) where max(a, b) returns the larger of a and b.


    v1=red, v2=green, v3=bluem v4=green

8.

f : (Z × Z) -> Z defined by: f(x, y) = max(x, y) − max(x^3, y^2) where max(a, b) returns the larger of a and b.

Definition 2.3 
A function f : X → Y is injective (or one-to-one) if, for all a and b in X, f(a) = f(b) implies that a = b. 
In this case we say that f is a one-to-one mapping from X to Y.

Definition 2.4 
A function f : X → Y is surjective (or onto) if, for all y ∈ Y, there exists an x ∈ X such that f(x) = y. 
In this case we say that f maps X onto Y.

f is not injective. For example:
  f(0,0)   = max(0,0) - max(0,0)   = 0 - 0 = 0
  f(-2,0)  = max(-2,0) - max((-2)^3,0) = 0 -0 = 0
Since (0,0) isnot equal to (-2,0) but f(0,0) = f(-2,0), f is not one-to-one.

f is not surjective because the domain is Z or all integers and the function as written, can never reach positive integers.