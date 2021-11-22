# Shape, Size and Data Type of an Array

### Create a NumPy Array

Import NumPy and create a NumPy array

![](https://lh3.googleusercontent.com/hLW2zK1bn4tcxFofRu1nUtCrBjOBQKWHZzIVqIRbxgBDN-7aubQKnJfAVaMIPI3ET6j-dMd-QR1Phn-yRx9JSFDwzFCrwKyhC-EkZ48WsG6jxf2OQbsDj4XbGaWai2mJPZ3uv8UP7hw)

### Size of an Array

NumPy array has an attribute called size that tells you the total number of elements in the array

You can check the size of a NumPy array using the ‘.size’ method. This method will return you total number elements present in the array

![](https://lh4.googleusercontent.com/3WNIAe8iN5DvV77LLty-8pBOkNhp8Pz\_SN-wEA9U9OkIDJNYZKZ4OX7Yks2dvrIbw0SyysHEu2Ls5pZY0EfWHVXsBJDz07AmcPHlitYOzJYtHK5ut7lKk4ooWQ\_N7NJnPUXGTIfqyM0)

### Data Types of Array

You can check type of data present in the NumPy array using ‘.dtype’ method. The data type of array ‘arr’ is ‘int’ (integer). Here, ‘32’ is related to memory allocation.

![](https://lh5.googleusercontent.com/NV0DEfFcZf2HX950wAz1rifdald8r\_VojeOMH1BwqyW0jqJCb8X2dRY-dwgPswS-LY9J77I2IGHbeOETWvq8dDu-QUljofkqumllSo81BIhDOsGPn-env-pDQIsGY7SWPUYwjh\_NN7Q)

Note: If you have a 64 bit computer, dtype might be displayed as int64 and if you have 32 bit, it might be displayed as int32

### Shape of an Array

An array has an attribute called shape that tells you the number of items along each axis.

If we have an array that has two axis, the shape attribute will tell you total number of rows and columns in that array

The shape attribute/method of NumPy returns a tuple of integers that represents the number of items along each axis.

Consider the given array ![](https://lh6.googleusercontent.com/1nL6X7FSNMeZ5g35vbLjPTzBUYCd5mFhjExSoCfqsgSR5EcQrP8nSNAZiJ94x3qJqtQ9ltaKiY7MrB6Am80bqzaNlSk99ZGpvbDQ6kZzbmPFo9GNka612cmVnXM6TJkc6-1aYhsbdRE)

You can check the shape of a NumPy array using a method ‘.shape’. In array ‘arr’, there are 4 rows and 3 columns.

![](https://lh5.googleusercontent.com/QCGsgjKcW-CDr88Mi\_XAVJSdTczP2V2mbLE1cvaCsp8F59e3-aP2I0UCftoO98if8zz4ncQx3cM8jeG0-BFNji9r2XsRT\_V9N9\_WwGU3h4ZTDbQJ9zqwHpmNOGDkFsdJnhAVGx\_b-kY)

### Dimension of an Array

Consider the given array ![](https://lh6.googleusercontent.com/1nL6X7FSNMeZ5g35vbLjPTzBUYCd5mFhjExSoCfqsgSR5EcQrP8nSNAZiJ94x3qJqtQ9ltaKiY7MrB6Am80bqzaNlSk99ZGpvbDQ6kZzbmPFo9GNka612cmVnXM6TJkc6-1aYhsbdRE)

An array has an attribute called dimension that tells you the number of axis in the array.

You can check the number of dimensions of a NumPy array using ‘.ndim’ method. The array ‘arr’ is 2 dimensional (i.e. the array has two axis)

![](https://lh4.googleusercontent.com/OXUKSEcuXDak6IFt5C11jImsKuBIJWrH1AJUsiL6XTIHgSrFaJbk0gh9O4Y5chraRQeYbHuHoNmm3foP1idjGYrcntbVEhjxjqUe7nE4WLi4ks3EPeMNccxeQc4E-NB21diEqcHseRk)

### type() function and dtype method

Everything in Python is an object.

Suppose you have an object, if you want to know what type of object is that, you will use type() function to know about it.

Now you know the object is a NumPy ndarray. If you want to know the type of data present in that array, you will use method ‘.dtype’. This is also called type of NumPy array.

![](https://lh3.googleusercontent.com/pk7Pmzanwprj1ej5S\_oQ6wo978-7d7TfDvjtRfb1\_WxWNrzwLGxxmcs4YCJXArVVWzu1fp5jrnR3eloZTnd07CwpruBthPfLUDhdEis5HQy9dKXUi02S\_uc6gn\_3kUm1RAjcJ94B-R0)

### Caution: dtype method on Python Lists

This is to be taken care that Python Lists don’t support ‘.dtype’ method or any other methods supported by a NumPy array

![](https://lh5.googleusercontent.com/zgdUhBLJ8aVYCjKg2X4yQUrpYuKupqBLsKo8J0Bsz3yclvM4mDacstT4S4J4iFFT473xxwg9Iz4TIQN5Pj7zLpAmqfBMM21SvZksjIBd92q5WwOwRkCZ3yOl4ZVRkSNFiJsYN16OATU)
