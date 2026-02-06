

fjflds


---

### ---TW Version---

# Big O (時間複雜度)

## **時間複雜度 = 計算效率**

## 了解時間複雜度才能知道如何增加計算的效率

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