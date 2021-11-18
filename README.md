These codes are written to test the main conjecture in [1] about the Galois group of g_p(x). These codes are written and run on Cocalc. 


## The codes have the following functions 

(1) The function reduced_fekete(p) return the reduced Fekete polynomial associated with the prime p (see definition 3.2 in the article [1]). 

(2) Given p,q the function fekete_reduction(p, q) computes the factorization of g_p(x) modulo q. 

(3) The function irreducible(p,n) searches for q_1<n such that g_p(x) is irreducible modulo q_1. 

(4) The function cycle(p,n) searches for q_2<n such that g_p(x) modulo q_2 is a product of a linear polynomial and another irreducible polynomial. 

(5) The function transpostion(p,n) searches for q_3<n such that g_p(x) modulo q_3 is a product of a quadratic polynomial and distinct irreducible polynomials of odd degrees. 

(6) The function search(p,n) simultaneously search for the smallest triple (q_1, q_2, q_3).

## Some quick notes about the files in this repository.

(1) The file through_search returns the triple (q_1, q_2, q_3) for p<1000.

## References 

[1] Jan Minac, Tung T. Nguyen, Nguyen Duy Tan, Fekete polynomials, quadratic residues, and arithmetic, available at https://arxiv.org/abs/2111.05256

 
