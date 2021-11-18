These codes are written to test the main conjecture in [1] about the Galois group of g_p(x). We wrote the following functions 

(1) Reduced Fekete polynomials (see definition 3.2 in the article [1]). 

(2) Given p,q the function fekete_reduction(p, q) computes the factorization of g_p(x) modulo q. 

(3) The function irreducible(p,n) searches for q_1<n such that g_p(x) is irreducible modulo q_1. 

(4) The function cycle(p,n) searches for q_2<n such that g_p(x) modulo q_2 is a product of a linear polynomial and another irreducible polynomial. 

(5) The function transpostion(p,n) searches for q_3<n such that g_p(x) modulo q_3 is a product of a quadratic polynomial and distince irreducible polynomials of odd degrees. 

(6) The function search(p,n) simultaneously search for the smallest triple $(q_1, q_2, q_3)$

[1] Jan Minac, Tung T. Nguyen, Nguyen Duy Tan, Fekete polynomials, quadratic residues, and arithmetic, available at https://arxiv.org/abs/2111.05256

 
