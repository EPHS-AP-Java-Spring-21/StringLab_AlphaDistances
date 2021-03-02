# StringLab_AlphaDistances

### Overview
Cryptologists are always looking for ways to analyze secret codes so that they have more practice at decoding information about their opponents.

### Problem
Given two words of equal length find the alphabet distance between letters in each word. The alphabet distance between 2 letters x and y is defined by assigning ‘A’ = 1, ‘B’ = 2, ... ‘Z’ = 26. Then the distance is y – x if y ≥ x, and (y + 26) – x if y < x. For instance the alphabet distance between ‘B’ and ‘D’ is 4 – 2 = 2, while the distance between ‘D’ and ‘B’ is (2 + 26) – 4 = 24.

### Sample Solutions
* AAAA ABCD 
* ABCD AAAA 
* DARK LOKI 
* STRONG THANOS 
* DEADLY ULTIMO

### Sample Output
* Distances: 0 1 2 3 
* Distances: 0 25 24 23 
* Distances: 8 14 19 24 
* Distances: 1 14 9 25 1 12 
* Distances: 17 7 19 5 1 16
