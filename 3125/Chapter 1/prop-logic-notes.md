* if and only if is SYMMETRIC  Q <-> P is equivalent to P <-> Q
* remember 'vacuously true' for if statement logic tables

* truth tables
    * numbers of rows = 2 ^ n
    * where n is number of letters in statement
    * q ^ p  has 4 rows

* contra positive
* converse
* De Morgan
* associative 
* distributive



* negate conditional with implication plus demorgan: 
x -> y 
not x or y, implication of 1.
negate(not x or y) = not(not x or y)
x and not y, demorgan



### Inference rules
* Modus ponens (MP): (A → B), A .... then B
* Modus tollens (MT): (A → B), ¬B .... then ¬A
* Contrapositive (CP): (A → B) ⟶ (¬B → ¬A)

* Hypothetical syllogism (HS): (A → B), (B → C) ⟶ (A → C)
* Disjunctive syllogism (DS): (A v B), ¬A ⟶ B
* Disjunctive syllogism (DS): (A v B), ¬B ⟶ A
* Constructive dilemma (CD): ((A → B) & (C → D)), (A v C) ⟶ (B v D)
* Destructive dilemma (DD): ((A → B) & (C → D)), (¬B v ¬D) ⟶ (¬A v ¬C)
* Bidirectional dilemma (BD): ((A → B) & (C → D)), (A v ¬D) ⟶ (B v ¬C)


### Combinine
* Addition (OI): A ⟶ (A v B)
* Or-elimination (OE): (A v A) ⟶ A
* Simplification (AE): (A & B) ⟶ A
* Simplification (AE): (A & B) ⟶ B
* Conjunction: A, B ⟶ (A & B)

### Inversion
Original statement: D(x)→J(x)
Converse: J(x)→D(x)
Inverse: ¬D(x)→¬J(x)
Contrapositive: ¬J(x)→¬D(x)


### Equivalence rules
* Material implication (MI): (A → B) ⟷ (¬A v B)
* Implication Negation -> ¬(A → B) ⟷ (A & ¬B)
* De Morgan-and (DMA): ¬(A & B) ⟷ (¬A v ¬B)
* De Morgan-or (DMO): ¬(A v B) ⟷ (¬A & ¬B)
* Commutation-and (CA): (A & B) ⟷ (B & A)
* Commutation-or (CO): (A v B) ⟷ (B v A)
* Association-and (AA): ((A & B) & C) ⟷ (A & (B & C))
* Association-or (AO): ((A v B) v C) ⟷ (A v (B v C))
* Distribution-and (DA): (A & (B v C)) ⟷ ((A & B) v (A & C))
* Distribution-or (DO): (A v (B & C)) ⟷ ((A v B) & (A v C))
* Double negation (NN): A ⟷ ¬¬A
* Transposition (TR): (A → B) ⟷ (¬B → ¬A)
* Exportation (EX): ((A & B) → C) ⟷ (A → (B → C))





### Quantifiers
Some -> at least one   
    * there exists an object, at least one, not all
    
All -> every one
    * Negation is = some

For all objects, the object is a fox.





### Predicate logic
existential -> at least one
universal -> all
All <blanks> are <something>. ->  universal(x)(A(x) -> B(x) )
There is a <blank> that is <something>. -> existential(x) (A(x) and B(x))
