### ---English Version---

# Big O (Time Complexity)

## **Time Complexity = Computational Efficiency**

## Understanding Time Complexity is Key to Improving Computational Efficiency

### Common Big O Classifications:

1. O(1) - Constant Time
**The execution speed remains the same regardless of the input size.Example: Accessing an element in an array by its index.**

2. $O(n)$ - Linear Time
**The execution speed grows proportionally with the size of the input $n$.Example: Simple search (Iterating through a list).**

3. $O(log n)$ - Logarithmic Time
**The search space is halved with each step of the algorithm.Example: Binary Search.**


---

### ---中文版---

# Big O (時間複雜度)

## **時間複雜度 = 計算效率**

## 了解時間複雜度才能知道如何增加計算的效率

### 基礎的 BigO :

1. O(1) 陣列讀取

**計算速度永遠一樣**

ex:

```python
im_list = ['1', '2', '3', '4', '5']
print(im_list[2])
```
結果 : '3'

2. O(n) 簡易搜尋

**速度隨n變化**

ex:

```python
im_list = ['1', '2', '3', '4', '5']
for i in im_list:
    if i == '3':
        print(i)
    else:
        print('not 3')
```

3. O(log n) 二分搜尋法

**每次搜尋都會排除一半可能性**

```python
Numbers = [5,17,33,41,55,61,80]
Find = 55
​
low = 0
high = len(Numbers) - 1
​
while low <= high:
    mid = (low + high) // 2
    if Numbers[mid] > Find:
        high = mid - 1
    elif Numbers[mid] < Find:
        low = mid + 1
    else:
        break
​
print(mid)
```
![alt text](../picture/image.png)

