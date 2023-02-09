# from-bits-to-brouwer
a book on practical mathematics in dependent type theory

## research

>>>
Set Type The set type looks very much like the definition of a subset in ZFC. We write it as
{x : A|P(x)}, and its elements are those members of the type A for which we have evidence that
the predicate P holds. The important feature of the set type is that the evidence is “hidden” in the
21
sense that in order to claim that an element a of the type A belongs to {x : A|P(x)}, we must prove
P(a). From the proof we can extract evidence pa that a has the required property. However, that
evidence is not stored with the type. One reason for hiding the evidence is a matter of efficiency
in presenting evidence. By hiding this evidence, we are saying that it will not be needed in further
computation. If we wanted to keep the evidence, we would use the product type, x : A × P(x)
whose elements are pairs, pair(a; p) where a belongs to A and p belongs to P(a).
>>>
