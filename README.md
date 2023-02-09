# from-bits-to-brouwer

a book on practical mathematics in dependent type theory

## research

### Set Theory

> The set type looks very much like the definition of a subset in ZFC. We write it as
> {x : A|P(x)}, and its elements are those members of the type A for which we have evidence that
> the predicate P holds. The important feature of the set type is that the evidence is “hidden” in the
> sense that in order to claim that an element a of the type A belongs to {x : A|P(x)}, we must prove
> P(a). From the proof we can extract evidence pa that a has the required property. However, that
> evidence is not stored with the type. One reason for hiding the evidence is a matter of efficiency
> in presenting evidence. By hiding this evidence, we are saying that it will not be needed in further
> computation. If we wanted to keep the evidence, we would use the product type, x : A × P(x)
> whose elements are pairs, pair(a; p) where a belongs to A and p belongs to P(a). (Robert Constable, Two Lectures on Constructive Type Theory)

> “A set is not an entity which has an ideal existence: a set exists only when
> it has been defined. To define a set we prescribe, at least implicitly, what we
> (the constructing intelligence) must do in order to construct an element of the
> set, and what we must do to show that two elements are equal” (Errett Bishop,
> Foundations of Constructive Analysis)

* Decidability in Intuitionistic Type Theory is functionally decidable

* Building up a toolbox for Martin-Lof’s type theory Part I. Set Theory

* The Generalised Type-Theoretic Interpretation of Constructive Set Theory

* Is ZF a hack? Comparing the complexity of some (formalist interpretations of) foundational systems for mathematics

* On relating type theories and set theories

* Introduction to Homotopy Type Theory by Egbert Rĳke 12.3 Sets

* Sets in Types, Types in Sets

* The forget-restore principle: a paradigmatic example

### Type Checking

* Checking Dependent Types with Normalization by Evaluation: A Tutorial

* On a Strongly Normalizing STG Machine With an Application to Dependent Type Checking

* Intrinsically-Typed Definitional Interpreters à la Carte
