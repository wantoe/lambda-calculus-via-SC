# lambda-calculus-compiler-via-SC
Lambda calculus compiler programme using supercombinators, implemented in HASKELL.

The direct implementation of beta-reduction is not very efficient. It repeatedly traverses the term to search for the next redex, to rename a variable, or to carry out a single substitution.
We will build a more efficient implementation using supercombinators, as used in the implementation of Haskell....
see CM50262-Coursework.pdf P.7 for more details

# How to use?
Source code is in "source code.hs" which requires text editor e.g. Notepad++ to edit. It can be compiled using WinGHCi.

# What I learnt?
- Haskell programming
- 2 ways of implementing beta reduction of lambda calculus terms 1) beta reduction with capture avoiding substitution  2) using supercombinator reuduction which is more efficient
