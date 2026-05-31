# LeetCode-HackerRank
# 1. Two Sum

## Problem
Given an array of integers `nums` and an integer `target`, return the indices of the two numbers such that they add up to `target`.

## Approach
Use a Hash Map (Dictionary) to store previously seen numbers and their indices.

For each number:
1. Calculate the complement (`target - num`)
2. Check if the complement already exists in the dictionary
3. If yes, return the indices
4. Otherwise, store the current number and index
