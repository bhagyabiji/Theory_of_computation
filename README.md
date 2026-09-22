Theory of Computation
--------
Alphabet - An alphabet is a finite, non-empty set of symbols.
Example:
  Σ ={0,1}
  Here 0 and 1 are symbols.

String - finite sequence of symbols from an alphabet
for eg:-  Σ ={0,1}
  0 → string
  1 → string
  01 → string
  10110 → string
  001011 → string

Empty string - The empty string contains no symbols. It is represented by: ϵ

Language- language is a set of strings over an alphabet.
  For example: Σ={0,1}
     L = {0, 01, 101, 111}

If
  Σ={0,1}
then:
  Σ raise to0={ϵ}
  Σ raise to 1={a,b}
  Σ raise to 2={aa,ab,ba,bb}
  Σ raise to 2={aaa,aab,aba,abb,bbb,bab,baa,bba}

So Σ∗ contains all possible finite strings, including ϵ (epsilon).

  For an alphabet containing n symbols:
          ∣Σ^k∣=n^k


