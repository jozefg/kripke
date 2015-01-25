## kripke
A formalization of Kripke semantics in Twelf. This code is split into

 - kripke.elf
   The formulation of Kripke semantics over the preorder that we need
   for box and diamond.
 - modal-logic.elf
   The normal formulation of modal logic.
 - equivalent.elf
   The translation procedure along with the soundness and completeness
   proofs for translating modal-logic.elf into Kripke semantics.
