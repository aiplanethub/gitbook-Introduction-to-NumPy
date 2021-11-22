# Positive Indexing

### Rows and Columns Indexes in an Array

![](<../.gitbook/assets/image (3).png>)

![](<../.gitbook/assets/image (4).png>)

* Conclusion If you want to get 4th element from an array, you should extract the element that is present at index 3.
* Generalizing If you want to get the nth element from an array, you should extract element that is present at index (n-1).

### Positive Single Indexing in an Array

Say you have an array with elements: 10, 20, 30, 40 in it. You want to get the 3rd element from the array. Use square brackets \[] and pass the index number (2 in this case) in that square brackets as you used to do for Python lists.

![](https://lh5.googleusercontent.com/YcFOAEhkiCvGQ5g-PQwgi7IKLVqTY2qJHWZGwCfcvqKMAJjn-5ySQpxi217x5CFntfUCpqsKKK8XkvE5z0eiIsbZzlKehemtI53Czt89rduj2S0qQ2oNVIOLL85PwBNwi4yTht9yMcA)

Did you get to know the dimension of the array? No? The dimension of the array is 1.

How you used to extract an element from a nested list in Python? Remember? No? Cool. No worries. You will remember once you jump to below part.

### Positive Single Indexing in Python Nested List

The below snippet will help you remember how to get one element from a Python nested list.

![](https://lh3.googleusercontent.com/6SGIHAJTD-XtQajJ\_lNji\_pwnrYmnn5HVFALm30VblJgDTEmvA-fJkuvDiW4\_mn5vjMqVCyxT8VdS9Th0R\_BLbV5CXNifdURYkJZVMa01o6ehVxNjte-bJEKOxlynb9FNemm5Ab2-8I)

### Positive Single Indexing in a NumPy Array

The array here is of dimension 2. You can compare Python nested list and a NumPy 2 - D array.

In NumPy 2 - D array, when you pass a single index in the square bracket, it will give you the entire row present at that index.

You can pass comma - separated values in the square bracket to get one element from a particular row and a particular column.

![](https://lh3.googleusercontent.com/Mat\_3e-Tpy017lPOLA7w-A8Y\_G7k7keO2DqO7ijB75Pt6fTdtNmUnYhE83u1zoJ6usa2KsMWIB75Usy0ANxUQk-LcsNhzGQZMWQIE-DNeQTGey99kBBSZC4jDP5JWtJXITyZTsoQR8E)

In the snippet shown here, num\_arr\[0, 0] will get you the element present at row indexed at 0 and column indexed at 0. Try num\_arr\[0]\[0] in your Notebook

### Positive Index Intervals in a NumPy Array

You can use semicolon (:) while indexing to get slices of elements from NumPy array.

In the snippet, num\_arr\[0, 0:2] will get you the row indexed at 0 and the columns indexed from 0 (inclusive) to 2 (exclusive).

This is also known as slicing an array.

![](https://lh5.googleusercontent.com/CGpkT1aAQoAfZ76xJkyljMljN-4Ko3gjALaIQd5TceqhkvoEgh0nILEYppWafNS9fqGqdfN\_O3GtEU6BKrK3eBZ6uBuYoA\_sFq7QszQyE5e7uNGJkDoTHEVVDZd08g81Wf9qQbFW6ME)

You can slice rows and columns as shown in the snippet.

![](https://lh4.googleusercontent.com/7ug39VCJoM8be69YgEUp\_EUKim7AFULKrgGPdZqcEV28r\_3dQIsnKthn8tn4PHUatJY\_Ya6HJr83opcVB87GuyOOk3lCQVJtKP-O1SGogKy0eDzvEa1GAFYFTctDiOPRHfQgeN7EOGw)

In the snippet, num\_arr\[1:3, 2:4] will get you the rows starting from index 1 to rows ending at index 3 (exclusive, means excluding 3) i.e. row 1 and row 2, columns starting from index 2 and ending at index 4 (exclusive) i.e. column 2 and column 3.

![](https://lh6.googleusercontent.com/1\_6CE1N\_rPpO1TKQwE4lON9Spd0dUH16WpSDneG184Vtg2AZMLvE93kCXpTsCrWMaJHAkUxkyUCYMH8Px3\_i1fb6suIQ7NWZc83LxL1fGOCXJQPyqwDRVAWzdSbKCTQ6YtwAbnQv6CQ)
