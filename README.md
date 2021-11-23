These codes are written to test the main conjectures in [1] about the Galois groups of g_p(x) and f_p(x). These codes are written and run on Cocalc. 


## Calculations with g_p  [the file "computations_with_g"] 

(1) The function reduced_fekete(p) return the reduced Fekete polynomial associated with the prime p (see definition 3.2 in the article [1]). 

(2) Given p,q the function fekete_reduction(p, q) computes the factorization of g_p(x) modulo q. 

(3) The function irreducible(p,n) searches for q_1<n such that g_p(x) is irreducible modulo q_1. 

(4) The function cycle(p,n) searches for q_2<n such that g_p(x) modulo q_2 is a product of a linear polynomial and another irreducible polynomial. 

(5) The function transpostion(p,n) searches for q_3<n such that g_p(x) modulo q_3 is a product of a quadratic polynomial and distinct irreducible polynomials of odd degrees. 

(6) The function search(p,n) simultaneously search for the smallest triple (q_1, q_2, q_3).

## Calculations with f_p [the file "computations_with_f"] 

(1) The function fekete(p) returns the Fekete polynomial f_p. 

(2) The function fekete_reduction(p,q) computes the factorization of f_p(x) modulo q. 

(3) The functions irreducible(p,n), almost_cycle(p,n), two_cycle(p,n), four_cycle(p,n) search for the quadruple (q_1, q_2, q_3, q_4) that produces the precise cycle shapes (see Proposition 4.14 in the article [1] for details). 


## Some quick notes about the files in this repository.

(1) The file "computations_with_g.ipynb" returns the triple (q_1, q_2, q_3) for p<1000.

(2) The file "computations_with_f.ipynb" returns the quadruple (q_1, q_2, q_3, q_4) for p<632. 

## References 

[1] Jan Minac, Tung T. Nguyen, Nguyen Duy Tan, Fekete polynomials, quadratic residues, and arithmetic, available at https://arxiv.org/abs/2111.05256

 
