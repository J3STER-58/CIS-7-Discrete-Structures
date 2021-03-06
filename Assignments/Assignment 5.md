### Part 1: 
  #### a) Show that the square root of 2 is irrational.
      - Suppose sqrt(2) is rational, meaning it can be the ratio of 2 integers p and q
      - sqrt(2) = p / q , where we can assume p and q have no common factors.
          - (If any common factors, we cancel in Num and Den)
      - Squaring both sides gives : 2 = p^2 / q^2
      - Implying : p^2 = 2(q^2), therefore p^2 is even and only true if p is even, then p^2 is divisible by 4. 
      - Hence q^2 and therefore q must be even, so p and q are both even.
      - Contradiction to no common factors: both divisible by 2.
      - Therefore sqrt(2) is irrational.
       
  #### b) If n = 25, 100, or 169, then n is a perfect square and is the sum of two perfect squares.
      - sqrt(25) = 5; Yes it is a perfect square. The sum of two perfect squares (a^2 + b^2) != 25
  
  #### c) The sum of two odd integers is even. Hint: By definition, even integers can be expressed as 2n,
     thus odd integers can be expressed as 2n + 1
      - Even = Odd + Odd
      - 2x = (2n + 1) + (2n + 1) 
      - 2x = 4n + 2
      - 2x = 2(2n + 1)
          - ( x = 2n + 1 )
          
      - 2x = 2x , Direct Proof
      
  #### d) The sum of an even integer and it's square is even: 2x
      - 2n + (2n)^2 = 2x
      - 2n + 4n^2 = 2x
      - 2(n + 2n^2) = 2x
          - ( x = n + 2n^2)
          
      - 2x = 2x , Direct Proof
      
  #### e) If n squared is odd, then n is odd
      - If n is even, then n^2 is even
      - n = 2k
      - n^2 = (2k)^2 = 4k^2
      - n^2 = 2(2k^2), Contraposition
      
      
### Part 2: 
 #### a) Prove by induction that 1 + 5 + 9 + ... + (4n-3) = n(2n-1)
      - Base case: n = 1
      - 1(2(1)-1) = 1
      - 1(2-1) = 1
      - 1(1) = 1
      - 1 = 1 : Base case is true
      - Assume n = k
      - (4(k+1)-3) = (k+1)(2(k+1)-1)
      - k(2k-1) + (4(k+1)-3) = (k+1)(2(k+1)-1)
      - ((2k^2)-k) + ((4k+4)-3) = (k+1)(2(k+1)-1)
      - 2k^2 + 3k + 1 = 2k^2 + 3k + 1
 
 #### b) Prove that for any positive integer number n, n^3 + 2n is divisible by 3
      - n^3 + 2n = 3m
      - Base Case: n = 1 ; 1=1
      - n = (k+1)
      - (k+1)^3 + 2(k+1) = 3m
      - k^3 + 3k^2 + 3k + 1 + 2k + 2 = 3m
      - K^3 + 3k + 3k^2 + 3k + 3 = 3m
      - 3m + 3k^2 + 3k + 3 = 3m
      - 3m + 3(k^2 + k + 1) = 3m
      - 3(m + k^2 + k + 1) = 3m
      - m + k^2 + k + 1 = some number m
      - 3m = 3m
 
 
 #### c) Prove that for n >= 1, 9^n − 1 is divisible by 8 for all non-negative integers 
    Hint: 4^(3+1) = 4 * 4^3 Hint: If 9^n - 1 = 8m, then 9^n = 8m + 1
      - 9^2n-1 = 8m
      - Base Case: n = 0 ; ture
      - n = K + 1
      - 9^(k+1) -1 + 9^((k+1)+1) -1 = 8m
      - 9^k * 9 - 1 + 9^k * 9^2 -1 = 8m
      - 9 * 9^k -1 + 9^2 * 9^k - 1 = 8m 
      - 9 * 8m + 9^2 * 8m = 8m
      - 8(9m + 9^2m) = 8m
      - 9m + 9^2m = some number m
      - 8m = 8m 


