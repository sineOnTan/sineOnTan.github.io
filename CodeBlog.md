# [Account links](https://sineontan.github.io/Coding)

# __Coding Questions__



## 26/08/2025

Leetcode question [3000. Maximum Area of Longest Diagonal Rectangle](https://leetcode.com/problems/maximum-area-of-longest-diagonal-rectangle/description/?envType=daily-question&envId=2025-08-26)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3000.cpp)
  <details>
    <summary>Editorial</summary>
    Eval the max value and swap if it is greater
  </details>

## 24/08/2025

Leetcode question [1493. Longest Subarray of 1's After Deleting One Element](https://leetcode.com/problems/longest-subarray-of-1s-after-deleting-one-element/description/?envType=daily-question&envId=2025-08-24)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1493.cpp)
  <details>
    <summary>Editorial</summary>
    Predecessors and successors counting. Edge case encountered where the index 0 or last element is deleted. Also made errors in my own code on how it should work.
  </details>

Codeforces Contest [2134](https://codeforces.com/contest/2134)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2134/A.cpp)
     <details>
      <summary>Editorial</summary>
      Modulus check on the numbers and coverage check.
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2134/B.cpp)
     <details>
      <summary>Editorial</summary>
      Was a modulus check in mod k + 1. Each addition decreases the remainder of mod k + 1 by 1.
 - C
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2134/C.cpp)
     <details>
      <summary>Editorial</summary>
      2 things are important. The predecessor and successor at event indices.
      Greedy so you make the predecessor legal when compared to the current and then the successor legal when comparing the current by the succ and pred.

Codeforces Contest [2133](https://codeforces.com/contest/2133)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2133/A.cpp)
     <details>
      <summary>Editorial</summary>
      Check if two numbers are the same.
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2133/B.cpp)
     <details>
      <summary>Editorial</summary>
      Sort decreasing then sum every odd number.
 - C
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2133/C.cpp)
     <details>
      <summary>Editorial</summary>
      Weird question which required topological ordering, path lengths then adjacency checks.
      First find the longest paths, then check for valid next nodes with length minus 1.

Codeforces Contest [2034](https://codeforces.com/contest/2034)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2034/A.cpp)
   - https://www.youtube.com/watch?v=XZSsTcJzayc
     <details>
      <summary>Editorial</summary>
      This is a question to find the LCM of the two numbers.
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2034/B.cpp)
   - https://www.youtube.com/watch?v=k5cUNLMUClQ
     <details>
      <summary>Editorial</summary>
      Need a check on whether the last x where 0 which could be done iteratively then solve from there

## 25/05/2025

Leetcode question [2131. Longest Palindrome by Concatenating Two Letter Words](https://leetcode.com/problems/longest-palindrome-by-concatenating-two-letter-words/description/?envType=daily-question&envId=2025-05-25)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2131.cpp)
  <details>
    <summary>Editorial</summary>
    Interesting question. One edge case to handle are duplicate letters in the pair which is doable by having a seperate case. Can sort the string to find duplicates. Had an error with my multiplication though.
  </details>

## 24/05/2025

Leetcode question [2942. Find Words Containing Character](https://leetcode.com/problems/find-words-containing-character/description/?envType=daily-question&envId=2025-05-24)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2942.cpp)
  <details>
    <summary>Editorial</summary>
    Simple question just use contains on the string or iterate through the string.
  </details>

## 23/05/2025

Leetcode question [3068. Find the Maximum Sum of Node Values](https://leetcode.com/problems/find-the-maximum-sum-of-node-values/description/?envType=daily-question&envId=2025-05-23)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3068.cpp)
  <details>
    <summary>Editorial</summary>
    Interesting question. First instinct was to DP but after realising that there are certain conditions such as having an even number of flips across the tree it becomes easier.
  </details>

## 22/05/2025

Leetcode question [3362. Zero Array Transformation III](https://leetcode.com/problems/zero-array-transformation-iii/description/?envType=daily-question&envId=2025-05-22)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3362.cpp)
  <details>
    <summary>Editorial</summary>
    The trick is to iterate on the numbers array. In doing so you ensure you find the minimum amount of queries possible for a given value with the maximum range. Usint pqs helps but you need to use checks to ensure whether it is possible.
  </details>

## 21/05/2025

Leetcode question [73. Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/description/?envType=daily-question&envId=2025-05-21)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/73.cpp)
  <details>
    <summary>Editorial</summary>
    Initial thought was if a value was 0, set all values in its column and row to 0 however this is too slow. i.e. multiple 0s in a row or column. To speed this up cache the 0 indexes and iterate through the cached 0s without duplicates and set those columns and rows to 0.
  </details>

## 20/05/2025

Leetcode question [3355. Zero Array Transformation I](https://leetcode.com/problems/zero-array-transformation-i/description/?envType=daily-question&envId=2025-05-20)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3355.cpp)
  <details>
    <summary>Editorial</summary>
    Question is a matter of caching the increment and decrement ranges and then doing 1 parse on the nums array.
  </details>

## 19/05/2025

Leetcode question [3024. Type of Triangle](https://leetcode.com/problems/type-of-triangle/description/?envType=daily-question&envId=2025-05-19)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3024.cpp)
  <details>
    <summary>Editorial</summary>
    Very easy question. Only tricky part is that if the sum of 2 lengths is less then the third it cannot be a triangle.
  </details>

Codeforces Contest [2109](https://codeforces.com/contest/2109)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2109/A.cpp)
     <details>
      <summary>Editorial</summary>
      There are 2 situations where it is not true. For every set of numbers, at least 1 person must lose and for each pair of people at least 1 person must win.
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2109/B.cpp)
     <details>
      <summary>Editorial</summary>
      In a 2D plane, we can either initially cut the x or y from the starting position. Initially thought of doing complex mathematics to do it but realised I could do them individually and compare the result.
 - C
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2109/C1.cpp)
     <details>
     <summary>Editorial</summary>
     Weird question........ Idk look at the official editorial.

## 18/05/2025

Leetcode question [1931. Painting a Grid With Three Different Colors](https://leetcode.com/problems/painting-a-grid-with-three-different-colors/description/?envType=daily-question&envId=2025-05-18)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1931.cpp)
  <details>
    <summary>Editorial</summary>
    DP with bitwise operations and masks. A little annoying to get the checks working and I did the DP wrong. One optimisation is caching the valid candidates for sets of 5 colours which was necessary as my code was slow. I guess you could also cache the valid combinations which will cut down the number of operations by a decent amount but this solution works.
  </details>

## 17/05/2025

Leetcode question [75. Sort Colors](https://leetcode.com/problems/sort-colors/description/?envType=daily-question&envId=2025-05-17)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/75.cpp)
  <details>
    <summary>Editorial</summary>
    Simplest solution is a counting sort as there are only 3 possible values.
  </details>

## 16/05/2025

Leetcode question [2901. Longest Unequal Adjacent Groups Subsequence II](https://leetcode.com/problems/longest-unequal-adjacent-groups-subsequence-ii/description/?envType=daily-question&envId=2025-05-16)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2901.cpp)

## 15/05/2025

Leetcode question [2900. Longest Unequal Adjacent Groups Subsequence I](https://leetcode.com/problems/longest-unequal-adjacent-groups-subsequence-i/description/?envType=daily-question&envId=2025-05-15)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2900.cpp)

## 13/05/2025

Leetcode question [3335. Total Characters in String After Transformations I](https://leetcode.com/problems/total-characters-in-string-after-transformations-i/description/?envType=daily-question&envId=2025-05-13)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3335.cpp)

## 12/05/2025

Leetcode question [2094. Finding 3-Digit Even Numbers](https://leetcode.com/problems/finding-3-digit-even-numbers/description/?envType=daily-question&envId=2025-05-12)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2094.cpp)

## 11/05/2025

Leetcode question [1550. Three Consecutive Odds](https://leetcode.com/problems/three-consecutive-odds/description/?envType=daily-question&envId=2025-05-11)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1550.cpp)

Codeforces Contest [2102](https://codeforces.com/contest/2102)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2102/A.cpp)
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2102/B.cpp)
 - C
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2102/C.cpp)

## 8/05/2025

Leetcode question [3342. Find Minimum Time to Reach Last Room II](https://leetcode.com/problems/find-minimum-time-to-reach-last-room-ii/description/?envType=daily-question&envId=2025-05-08)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3342.cpp)

## 7/05/2025

Leetcode question [3341. Find Minimum Time to Reach Last Room I](https://leetcode.com/problems/find-minimum-time-to-reach-last-room-i/description/?envType=daily-question&envId=2025-05-07)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3341.cpp)

## 6/05/2025

Leetcode question [1920. Build Array from Permutation](https://leetcode.com/problems/build-array-from-permutation/description/?envType=daily-question&envId=2025-05-06)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1920.cpp)

## 5/05/2025

Leetcode question [790. Domino and Tromino Tiling](https://leetcode.com/problems/domino-and-tromino-tiling/description/?envType=daily-question&envId=2025-05-05)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/790.cpp)

## 4/05/2025

Leetcode question [1128. Number of Equivalent Domino Pairs](https://leetcode.com/problems/number-of-equivalent-domino-pairs/description/?envType=daily-question&envId=2025-05-04)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1128.cpp)

Codeforces Contest [2103](https://codeforces.com/contest/2103)
 - A + B (21/04/2025)
 - C
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2103/C.cpp)
   - Personal notes in document.

## 3/05/2025

Leetcode question [1007. Minimum Domino Rotations For Equal Row](https://leetcode.com/problems/minimum-domino-rotations-for-equal-row/description/?envType=daily-question&envId=2025-05-03)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1007.cpp)

## 2/05/2025

Leetcode question [838. Push Dominoes](https://leetcode.com/problems/push-dominoes/description/?envType=daily-question&envId=2025-05-02)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/838.cpp)

## 30/04/2025

Leetcode question [1295. Find Numbers with Even Number of Digits](https://leetcode.com/problems/find-numbers-with-even-number-of-digits/description/?envType=daily-question&envId=2025-04-30)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1295.cpp)

## 27/04/2025

Leetcode question [3392. Count Subarrays of Length Three With a Condition](https://leetcode.com/problems/count-subarrays-of-length-three-with-a-condition/description/?envType=daily-question&envId=2025-04-27)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3392.cpp)

## 23/04/2025

Leetcode question [1399. Count Largest Group](https://leetcode.com/problems/count-largest-group/description/?envType=daily-question&envId=2025-04-23)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1399.cpp)

## 21/04/2025

Leetcode question [2145. Count the Hidden Sequences](https://leetcode.com/problems/count-the-hidden-sequences/description/?envType=daily-question&envId=2025-04-21)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2145.cpp)

Codeforces Contest [2103](https://codeforces.com/contest/2103)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2103/A.cpp)
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2103/B.cpp)

## 20/04/2025

Leetcode question [781. Rabbits in Forest](https://leetcode.com/problems/rabbits-in-forest/description/?envType=daily-question&envId=2025-04-20)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/781.cpp)

Codeforces Contest [2096](https://codeforces.com/contest/2096)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2096/A.cpp)
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2096/B.cpp)

## 17/04/2025

Leetcode question [2176. Count Equal and Divisible Pairs in an Array](https://leetcode.com/problems/count-equal-and-divisible-pairs-in-an-array/description/?envType=daily-question&envId=2025-04-17)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2176.cpp)

## 14/04/2025

Leetcode question [1534. Count Good Triplets](https://leetcode.com/problems/count-good-triplets/description/?envType=daily-question&envId=2025-04-14)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1534.cpp)

## 13/04/2025

Leetcode question [1922. Count Good Numbers](https://leetcode.com/problems/count-good-numbers/description/?envType=daily-question&envId=2025-04-13)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1922.cpp)

Codeforces Contest [2093](https://codeforces.com/contest/2093)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2093/A.cpp)
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2093/B.cpp)
 - C
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2093/C.cpp)

## 9/04/2025

Leetcode question [3375. Minimum Operations to Make Array Values Equal to K](https://leetcode.com/problems/minimum-operations-to-make-array-values-equal-to-k/description/?envType=daily-question&envId=2025-04-09)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3375.cpp)

## 8/04/2025

Leetcode question [3396. Minimum Number of Operations to Make Elements in Array Distinct](https://leetcode.com/problems/minimum-number-of-operations-to-make-elements-in-array-distinct/description/?envType=daily-question&envId=2025-04-08)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3396.cpp)

## 2/04/2025

Leetcode question [2873. Maximum Value of an Ordered Triplet I](https://leetcode.com/problems/maximum-value-of-an-ordered-triplet-i/description/?envType=daily-question&envId=2025-04-02)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2873.cpp)

## 1/04/2025

Leetcode question [2140. Solving Questions With Brainpower](https://leetcode.com/problems/solving-questions-with-brainpower/description/?source=submission-noac)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2140.cpp)

## 20/03/2025

Leetcode question [3108. Minimum Cost Walk in Weighted Graph](https://leetcode.com/problems/minimum-cost-walk-in-weighted-graph/description/?envType=daily-question&envId=2025-03-20)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3108.cpp)

## 19/03/2025

Leetcode question [3191. Minimum Operations to Make Binary Array Elements Equal to One I](https://leetcode.com/problems/minimum-operations-to-make-binary-array-elements-equal-to-one-i/description/?envType=daily-question&envId=2025-03-19)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3191.cpp)

## 17/03/2025

Leetcode question [2206. Divide Array Into Equal Pairs](https://leetcode.com/problems/divide-array-into-equal-pairs/description/?envType=daily-question&envId=2025-03-17)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2206.cpp)

## 16/03/2025

Leetcode question [2594. Minimum Time to Repair Cars](https://leetcode.com/problems/minimum-time-to-repair-cars/description/?envType=daily-question&envId=2025-03-16)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2594.cpp)

## 15/03/2025

Leetcode question [2560. House Robber IV](https://leetcode.com/problems/house-robber-iv/description/?envType=daily-question&envId=2025-03-15)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2560.cpp)

## 14/03/2025

Leetcode question [2226. Maximum Candies Allocated to K Children](https://leetcode.com/problems/maximum-candies-allocated-to-k-children/description/?envType=daily-question&envId=2025-03-14)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2226.cpp)

## 13/03/2025

Leetcode question [3356. Zero Array Transformation II](https://leetcode.com/problems/zero-array-transformation-ii/description/?envType=daily-question&envId=2025-03-13)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/3356.cpp)

## 12/03/2025

Leetcode question [2529. Maximum Count of Positive Integer and Negative Integer](https://leetcode.com/problems/maximum-count-of-positive-integer-and-negative-integer/description/?envType=daily-question&envId=2025-03-12)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2529.cpp)

## 11/03/2025

Leetcode question [1358. Number of Substrings Containing All Three Characters](https://leetcode.com/problems/number-of-substrings-containing-all-three-characters/description/?envType=daily-question&envId=2025-03-11)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/1358.cpp)

Codeforces Contest [2074](https://codeforces.com/contest/2074)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2074/A.cpp)
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2074/B.cpp)
 - C
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2074/C.cpp) 

## 05/03/2025

Leetcode question [2579. Count Total Number of Colored Cells](https://leetcode.com/problems/count-total-number-of-colored-cells/description/?envType=daily-question&envId=2025-03-05)
- [Solution](https://github.com/sineOnTan/leetcode/blob/main/2579.cpp)


## 04/03/2025

Leetcode question [1780. Check if Number is a Sum of Powers of Three](https://leetcode.com/problems/check-if-number-is-a-sum-of-powers-of-three/description/?envType=daily-question&envId=2025-03-04)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1780.cpp)

Codeforces Contest [2067](https://codeforces.com/contest/2067)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2067/A.cpp)
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2067/B.cpp)
 - C
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2067/C.cpp) 

## 13/02/2025

Leetcode question [3066. Minimum Operations to Exceed Threshold Value II](https://leetcode.com/problems/minimum-operations-to-exceed-threshold-value-ii/description/?envType=daily-question&envId=2025-02-13)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/3066.cpp)

## __11, 12: Preparation for IMC contest and participation in CPMSOC contest__

## 10/02/2025

Leetcode question [3174. Clear Digits](https://leetcode.com/problems/clear-digits/description/?envType=daily-question&envId=2025-02-10)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/3174.cpp)

## 09/02/2025

Leetcode question [2364. Count Number of Bad Pairs](https://leetcode.com/problems/count-number-of-bad-pairs/description/?envType=daily-question&envId=2025-02-09)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2364.cpp)

Codeforces Contest [2063](https://codeforces.com/contest/2063)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2063/C.cpp)

## 08/02/2025

Leetcode question [1249. Minimum Remove to Make Valid Parentheses](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/description/?envType=company&envId=facebook&favoriteSlug=facebook-thirty-days)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1249.cpp)
 - Note: Meta OA question

Leetcode question [2349. Design a Number Container System](https://leetcode.com/problems/design-a-number-container-system/description/?envType=daily-question&envId=2025-02-08)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2349.cpp)

## 07/02/2025

Leetcode question [3160. Find the Number of Distinct Colors Among the Balls](https://leetcode.com/problems/find-the-number-of-distinct-colors-among-the-balls/description/?envType=daily-question&envId=2025-02-07)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/3160.cpp)

## 06/02/2025

Leetcode question [1726. Tuple with Same Product](https://leetcode.com/problems/tuple-with-same-product/description/?envType=daily-question&envId=2025-02-06)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1726.cpp)

Codeforces Contest [2062](https://codeforces.com/contest/2062)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2062/A.cpp)
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2062/B.cpp)

## 05/02/2025

Leetcode question [1790. Check if One String Swap Can Make Strings Equal](https://leetcode.com/problems/check-if-one-string-swap-can-make-strings-equal/description/?envType=daily-question&envId=2025-02-05)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1790.cpp)

## 04/02/2025

Leetcode question [1800. Maximum Ascending Subarray Sum](https://leetcode.com/problems/maximum-ascending-subarray-sum/description/?envType=daily-question&envId=2025-02-04)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1800.cpp)

## 03/02/2025

Leetcode question [3105. Longest Strictly Increasing or Strictly Decreasing Subarray](https://leetcode.com/problems/longest-strictly-increasing-or-strictly-decreasing-subarray/description/?envType=daily-question&envId=2025-02-03)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/3105.cpp)
   
Codeforces Contest [2059](https://codeforces.com/contest/2059)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2059/A.cpp)

## 02/02/2025

Leetcode question [1752. Check if Array Is Sorted and Rotated](https://leetcode.com/problems/check-if-array-is-sorted-and-rotated/description/?envType=daily-question&envId=2025-02-02)
 - Notes: Suprisingly difficult
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1752.cpp)


## 15/1/2025

Leetcode question [2429. Minimize XOR](https://leetcode.com/problems/minimize-xor/description/?envType=daily-question&envId=2025-01-15)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2429.cpp)

## 14/1/2025

Leetcode question [2657. Find the Prefix Common Array of Two Arrays](https://leetcode.com/problems/find-the-prefix-common-array-of-two-arrays/description/?envType=daily-question&envId=2025-01-14)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2657.cpp)

## 13/1/2025

Leetcode question [3223. Minimum Length of String After Operations](https://leetcode.com/problems/minimum-length-of-string-after-operations/description/?envType=daily-question&envId=2025-01-13)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/3223.cpp)

## 12/1/2025

Leetcode question [2116. Check if a Parentheses String Can Be Valid](https://leetcode.com/problems/check-if-a-parentheses-string-can-be-valid/description/?envType=daily-question&envId=2025-01-12)
 - Kind of difficult and interesting question.
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2116.cpp)

## 11/1/2025

Leetcode question [1400. Construct K Palindrome Strings](https://leetcode.com/problems/construct-k-palindrome-strings/description/?envType=daily-question&envId=2025-01-11)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1400.cpp)

## 10/1/2025

Leetcode question [916. Word Subsets](https://leetcode.com/problems/word-subsets/description/?envType=daily-question&envId=2025-01-10)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/916.cpp)

## 9/1/2025

Leetcode question [2185. Counting Words With a Given Prefix](https://leetcode.com/problems/counting-words-with-a-given-prefix/description/?envType=daily-question&envId=2025-01-09)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2185.cpp)

Codeforces Contest [2057](https://codeforces.com/contest/2057)
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2057/B.cpp)

## 8/1/2025

Leetcode question [3042. Count Prefix and Suffix Pairs I](https://leetcode.com/problems/count-prefix-and-suffix-pairs-i/description/?envType=daily-question&envId=2025-01-08)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/3042.cpp)

## 7/1/2025

Leetcode question [1408. String Matching in an Array](https://leetcode.com/problems/string-matching-in-an-array/description/?envType=daily-question&envId=2025-01-07)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1408.cpp)

## 6/1/2025

Leetcode question [1769. Minimum Number of Operations to Move All Balls to Each Box](https://leetcode.com/problems/minimum-number-of-operations-to-move-all-balls-to-each-box/description/?envType=daily-question&envId=2025-01-06)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1769.cpp)

Codeforces Contest [2057](https://codeforces.com/contest/2057)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2057/A.cpp)

## 5/1/2025

Leetcode question [2381. Shifting Letters II](https://leetcode.com/problems/shifting-letters-ii/description/?envType=daily-question&envId=2025-01-05)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2381.cpp)
 - Interesting problem with char overflow

## 4/1/2025

Leetcode question [1930. Unique Length-3 Palindromic Subsequences](https://leetcode.com/problems/unique-length-3-palindromic-subsequences/description/?envType=daily-question&envId=2025-01-04)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1930.cpp)

## 3/1/2025

Leetcode question [2270. Number of Ways to Split Array](https://leetcode.com/problems/number-of-ways-to-split-array/description/?envType=daily-question&envId=2025-01-03)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2270.cpp)

Codeforces Contest [2024-2025 ICPC, NERC, Northern Eurasia Finals (Unrated, Online Mirror, ICPC Rules, Teams Preferred)](https://codeforces.com/contest/2052)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/2052/A.cpp)

## 2/1/2025

Leetcode question [2559. Count Vowel Strings in Ranges](https://leetcode.com/problems/count-vowel-strings-in-ranges/description/?envType=daily-question&envId=2025-01-02)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2559.cpp)

## 30/12/2024

Leetcode question [2466. Count Ways To Build Good Strings](https://leetcode.com/problems/count-ways-to-build-good-strings/description/?envType=daily-question&envId=2024-12-30)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2466.cpp)

## 27/12/2024

Leetcode question [1014. Best Sightseeing Pair](https://leetcode.com/problems/best-sightseeing-pair/description/?envType=daily-question&envId=2024-12-27)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/1014.cpp)

## 26/12/2024

Leetcode question [494. Target Sum](https://leetcode.com/problems/target-sum/description/?envType=daily-question&envId=2024-12-26)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/494.cpp)


## 25/12/2024

Leetcode question [515. Find Largest Value in Each Tree Row](https://leetcode.com/problems/find-largest-value-in-each-tree-row/description/?envType=daily-question&envId=2024-12-25)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/515.cpp)

## 23/12/2024

[Advent Of Code Day 4](https://adventofcode.com/2024/day/4)
 - [Solution A](https://github.com/sineOnTan/adventofcode/blob/master/4A.cpp)
 - [Solution B](https://github.com/sineOnTan/adventofcode/blob/master/4B.cpp)

## 22/12/2024

[Advent Of Code Day 3](https://adventofcode.com/2024/day/3)
 - [Solution A](https://github.com/sineOnTan/adventofcode/blob/master/3A.cpp)
 - [Solution B](https://github.com/sineOnTan/adventofcode/blob/master/3B.cpp)
 - Author's note: Look at 3B comments. A lot of subfiles were used to make the process easier

## 21/12/2024

Leetcode question [2872. Maximum Number of K-Divisible Components](https://leetcode.com/problems/maximum-number-of-k-divisible-components/description/?envType=daily-question&envId=2024-12-21)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2872.cpp)

## 20/12/2024

[Advent Of Code Day 19](https://adventofcode.com/2024/day/19)
 - [Solution A](https://github.com/sineOnTan/adventofcode/blob/master/19A.cpp)
 - [Solution B](https://github.com/sineOnTan/adventofcode/blob/master/19B.cpp)

[Advent Of Code Day 1](https://adventofcode.com/2024/day/1)
 - [Solution A](https://github.com/sineOnTan/adventofcode/blob/master/1A.cpp)
 - [Solution B](https://github.com/sineOnTan/adventofcode/blob/master/1B.cpp)

[Advent Of Code Day 2](https://adventofcode.com/2024/day/2)
 - [Solution A](https://github.com/sineOnTan/adventofcode/blob/master/2A.cpp)
 - [Solution B](https://github.com/sineOnTan/adventofcode/blob/master/2B.cpp)

## 19/12/2024

Leetcode question [769. Max Chunks To Make Sorted](https://leetcode.com/problems/max-chunks-to-make-sorted/description/?envType=daily-question&envId=2024-12-19)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/769.cpp)

## 17/12/2024

Leetcode question [3264. Final Array State After K Multiplication Operations I](https://leetcode.com/problems/final-array-state-after-k-multiplication-operations-i/description/?envType=daily-question&envId=2024-12-16)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/3264.cpp)

## 12/12/2024

Leetcode question [2558 - Take Gifts From the Richest Pile](https://leetcode.com/problems/take-gifts-from-the-richest-pile/description/?envType=daily-question&envId=2024-12-12)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2558.cpp)

[Advent Of Code Day 12](https://adventofcode.com/2024/day/12)
 - [Solution A](https://github.com/sineOnTan/adventofcode/blob/master/12A.cpp)

## 10/12/2024

Leetcode question [2981 - Find Longest Special Substring That Occurs Thrice II](https://leetcode.com/problems/find-longest-special-substring-that-occurs-thrice-i/description/?envType=daily-question&envId=2024-12-10)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2981.cpp)
   
## 09/12/2024

Leetcode question [3152 - Special Array II](https://leetcode.com/problems/special-array-ii/description/?envType=daily-question&envId=2024-12-09)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/3152.cpp)

Codeforces Contest [992](https://codeforces.com/contest/2040)
 - A
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/992/A.cpp)
 - B
   - [Solution](https://github.com/sineOnTan/codeforces/blob/main/992/B.cpp)

## 08/12/2024

Leetcode question [2054 - Two Best Non-Overlapping Events](https://leetcode.com/problems/two-best-non-overlapping-events/description/?envType=daily-question&envId=2024-12-08)
 - [Solution](https://github.com/sineOnTan/leetcode/blob/main/2054.cpp)
