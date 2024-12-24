<details>

  <summary>
    <h2>Techie Delight</h2>
  </summary>
  <br>
  
  ### Data Structures and Algorithm Problems

  #### 1. Find a pair with the given sum in an array

```python
# Source: https://www.techiedelight.com/find-pair-with-given-sum-array/

import random

# Fix this code. It should only find a pair with sum, not sum and sub

counter1, counter2, array, randomLen, par = 0, 0, [], [], []

goal = random.randint(1, 30)

for Counter in range(15):

    randomLen.append(random.randint(1, 15))

    if randomLen[Counter] in array:

        continue

    else:

        array.append(randomLen[Counter])

while counter1 != len(array):

    if array[counter1] == array[counter2]:

        counter1 += 1

        continue

    elif array[counter1] + array[counter2] == goal or array[counter1] - array[counter2] == goal:

        if array[counter2] and array[counter1] not in par:

            par.append(array[counter1])

            par.append(array[counter2])

        else:

            pass

    if counter1 == len(array)-1:

        counter2 += 1

        counter1 = 0

        continue

    else:

        counter1 += 1

print("The Bullseye-Array", array)

print()

print("The Goal is", goal)

print()

if len(par) > 1:

    print("The pairs that matchs:", par)

elif len(par) == 1:

    print("The only one pair that matchs:", par)

```

  #### 2. Check if a subarray with 0 sum exists or not

```python
# Source: https://www.techiedelight.com/check-subarray-with-0-sum-exists-not/

import random

counter, arrLen, zeroSum, zeroSum1, zeroSum2, subArr0, subArr1, subArr2, masterArr = 0, 15, 0, 0, 0, [], [], [], []

while counter != arrLen//3:

    subArr0.append(random.randint(-30, 30))

    subArr1.append(random.randint(-30, 30))

    subArr2.append(random.randint(-30, 30))

    counter += 1

    if counter == arrLen//3:

        masterArr.append(subArr0)

        masterArr.append(subArr1)

        masterArr.append(subArr2)

        for Counter1 in range(len(masterArr[0])):

            zeroSum += masterArr[0][Counter1]

        for Counter2 in range(len(masterArr[1])):

            zeroSum1 += masterArr[1][Counter2]

        for Counter3 in range(len(masterArr[2])):

            zeroSum2 += masterArr[2][Counter3]

print(masterArr)

print()

if zeroSum == 0:

    print("The Subarray", masterArr[0], "is sum 0")

elif zeroSum1 == 0:

    print("The Subarray", masterArr[1], "is sum 0")

elif zeroSum2 == 0:

    print("The Subarray", masterArr[2], "is sum 0")

elif zeroSum == 0 and zeroSum1 == 0 and zeroSum2 == 0:

    print("All the Subarrays are sum 0")

elif zeroSum + zeroSum1 + zeroSum2 == 0:

    print("The Array is sum 0")

else:

    print("There's no 0 sum")
```

  #### 3. Print all subarrays with 0 sum

```python

```

  #### 4. Sort binary array in linear time

```python
# Source https://www.techiedelight.com/sort-binary-array-linear-time/

import random

array, exchange, counter1 = [], [], 0

for counter in range(0, random.randint(5, 30)):

    array.append(random.randrange(0, 2))

print("The original Array is: ", array)

while counter1 != len(array)-1:

    if array[counter1] > 0:

        exchange.append(array.pop(counter1))

        counter1 = 0

    else:

        counter1 += 1

        continue

while True:

    array.append(exchange.pop(0))

    if len(exchange) == 0:

        break

print("The new Array sorted in Binary: ", array)
```

  #### 5. Find maximum length subarray having a given sum

```python
# Source https://www.techiedelight.com/find-maximum-length-sub-array-having-given-sum/

## Fix this code. Isn't working as supposed to be

import random

counter1, counter2, sum, array, randomLen, subArray = 0, 1, 0, [], [], []

goal = random.randint(1, 30)

for counter in range(15):

    randomLen.append(random.randint(1, 15))

    if randomLen[counter] in array:

        continue

    else:

        array.append(randomLen[counter])

sum = array[counter1]

subArray.append(array[counter1])

while counter1 != len(array) - 1:

    if sum + array[counter2] <= goal:

        subArray.append(array[counter2])

        sum += array[counter2]

# if Sum != Goal and Array[Counter2 + 1] + Sum > Goal:

# Sum -= Array[Counter2]

    counter2 += 1

    if counter2 == len(array):

        counter1 += 1

        counter2 = counter1 + 1

        print(subArray)

        sum = array[counter1]

        subArray.append("|")

        if array[counter1] <= goal:

            subArray.append(array[counter1])

print()
print(array)
print(goal)
print(subArray)

# 24
# 2, 6, 10, 9, 11, 15, 12, 13
```

</details>
