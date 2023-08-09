# 1827. Minimum Operations to Make the Array Increasing

You are given an integer array nums (0-indexed). </br>
In one operation, you can choose an element of the array and increment it by 1. </br>

For example, if nums = [1,2,3], you can choose to increment nums[1] to make nums = [1,3,3]. </br>
Return the minimum number of operations needed to make nums strictly increasing. </br>

An array nums is strictly increasing if nums[i] < nums[i+1] </br>
for all 0 <= i < nums.length - 1. An array of length 1 is trivially strictly increasing. </br>

## Example 1:

Input: nums = [1,1,1] </br>
Output: 3 </br>
Explanation: You can do the following operations: </br>
1) Increment nums[2], so nums becomes [1,1,2]. </br>
2) Increment nums[1], so nums becomes [1,2,2]. </br>
3) Increment nums[2], so nums becomes [1,2,3]. </br>

## Example 2:

Input: nums = [1,5,2,4,1] </br>
Output: 14 </br>

## Example 3:

Input: nums = [8] </br>
Output: 0 </br>

## Constraints:

1 <= nums.length <= 5000 </br>
1 <= nums[i] <= 104 </br>
