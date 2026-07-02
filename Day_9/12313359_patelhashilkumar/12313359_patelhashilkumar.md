# Search in Rotated Sorted Arra
Link - https://neetcode.io/problems/find-target-in-rotated-sorted-array/question?list=neetcode150
```python
class Solution:
    def search(self, nums: List[int], target: int) -> int:
        for i in range(len(nums)):
            if nums[i] == target:
                return i
        return -1
```

# Find Minimum in Rotated Sorted Array
Link - https://neetcode.io/problems/find-minimum-in-rotated-sorted-array/question?list=neetcode150
```python
class Solution:
    def findMin(self, nums: List[int]) -> int:
        for i in range(len(nums)):
            return min(nums)
```