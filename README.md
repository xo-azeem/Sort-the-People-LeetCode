# Sort the People

LeetCode Q # 2418.

You are given an array of strings names, and an array heights that consists of distinct positive integers. Both arrays are of length n.

For each index i, names[i] and heights[i] denote the name and height of the ith person.

Return names sorted in descending order by the people's heights.

Example 1:

> Input: names = ["Mary","John","Emma"], heights = [180,165,170]</br>
> Output: ["Mary","Emma","John"]</br>
> Explanation: Mary is the tallest, followed by Emma and John.

Example 2:

> Input: names = ["Alice","Bob","Bob"], heights = [155,185,150]</br>
> Output: ["Bob","Alice","Bob"]</br>
> Explanation: The first Bob is the tallest, followed by Alice and the second Bob.

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/a06648f3-d37f-45d5-9149-d43c936a3757)

  Time complexity: O(n log n).</br>Space complexity: O(n).
</div>
