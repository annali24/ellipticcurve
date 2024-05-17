#### Directed Reading Program 2024
##### Catherine Chen and Anna Li, mentored by Marcos Reyes

[Click here to access the Elliptic Curve Torsion Calculator](https://replit.com/@cchen935/Elliptical-Curve)

[Click here to view our poster](https://replit.com/@annajli/Elliptic-Curve-Calculator)

This year, our project focuses on researching the properties of Weierstrass Elliptic Curves and computing its torsion over the rationals. Weierstrass elliptic curves are represented in the form y² = x³ + Ax² + Bx + C, where A, B, and C are integers.


### How it Works

The calculator will ask you to input three integers for A, B, and C which represents the variables in the elliptical curve equation y² = x³ + Ax² + Bx + C. This is the affine version of the equation. 

**The Algorithm**

First, by utilizing Nagell Lutz's Theorem, we will calculate the discriminant and determine the multiples. These would be possible y-values of the equation. Then, we check if y² would divide the discriminant and take those values and plug it into the curve to see if we get an integer value for x. 

Secondly, we take the possible points we found and go through the process of generating all the rational points with addition defined under the group structure. 

Thirdly, we compute the order of these points to determine the order of the entire torsion group for the curve. Mazur's Theorem states that for a non singular rational cubic curve E(Q), the order is between 1 and 10 or is exactly 12, or Z2 X Z(2M), where M = 1, 2, 3, or 4. 

Thus, if the max number of rational points generated by a finite generator is is 2, 3, 5, 7, 9, or 10 then that would be the order. However, for groups of order 4, 8, 12, or 16, then we must check if the highest order of the individual elements in the torsion group. If the highest order of a group of order four is 2, then the order would be Z2 X Z2, if the highest order is 4, then the order would be Z4 X Z2, and if the highest order is 6, then the order would be Z6 X Z2, and so on.


#### References
1] Thomas W. Judson and Robert A. Beezer. Abstract Algebra: Theory and Applications. An-
nual edition 2022. Orthagonal Publishing L3c, 2022.

[2] Alvaro Lorenzo-Robledo. Elliptical Curves, Modular Forms, and Their L-functions. American
Mathematical Society, 2011.

[3] Joseph H. Silverman and John T. Tate. Rational Points on Elliptical Curves. 2nd edition.
Springer Cham, 2015.




 

