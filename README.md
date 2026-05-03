# Missing-number-from-array
nums = list(map(int,input("Enter distinct numbers : ").split()))
n = len(nums)
for i in range(n + 1):
    if i not in nums:
        print("Missing number is:", i)
        break
