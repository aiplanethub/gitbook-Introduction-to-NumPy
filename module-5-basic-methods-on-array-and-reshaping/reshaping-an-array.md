# Reshaping an Array

### Can you reshape an array?&#x20;

### YES!

* Using **np.reshape()** will change the shape of your array
* Also, there won’t be any changes in the original data other than the shape
* **Caution:** Whenever you use reshape() method, you need to make sure that the array you want to produce after reshaping needs to have the same number of elements as the original array.
* Suppose you have an array with 24 elements. If you want to reshape this array, you need to make sure that your new array also has a total of 24 elements. You can reshape this array into (8, 3) or (6, 4) or (12, 2) an so on as these array will also have total of 24 elements (8 x 3 = 24, 6 x 4 = 24, 12 x 2 = 24)
* Create an array with 24 elements in it.

![](https://lh5.googleusercontent.com/rewSapYjbTbkea0ufkiTeKSYO1UaTCWh2iO4wkE6uv0NiSOzK8Fg538EwjOVQ9ModzEb9fVYez81sex4wbAnBH6pRjZBLA-6JaeOOaCa8h\_ZilLpKWJyQNiea0c4ExXcIT5QqZ6Jotc)

* Use **np.reshape()** to change the shape of arrays as shown in the code snippet here.
* Array with shapes (8, 3), (6, 4) and (2, 12) have 24 elements in it.
* All of these three arrays have the same values that were present in the initial array **‘arr’**

![](https://lh6.googleusercontent.com/UB3WGE50UfAXoSOGO8tJ\_9fRVRZjpf7sO057YQNGkFXlrEmMUVGbQ1DdDVgJ-iwUA4PYaDW6OOK5OEzJy0kCme11ydCdq9fjb8S47\_OPHi9z0-NaDUSgiV-weTbE9uRQHqFgZWs9\_Qg)

### Reshaping a Python List

Using np.reshape() you can change the shape of a Python list but the returned object is of type numpy.ndarray.

![](https://lh6.googleusercontent.com/yHrVTN\_N3xoMLbilHy-MO6luTxupnt72uz4RYYyMSkkgbQpkO2qLARX56cwiICwuXbsndlW9GGXW0k5lyNYshBaI1FL0JmR0qJqg-RnbrZMtZsoBmaPr\_ot\_NzF09l2FrO\_nHbjxMg4)

### Using reshape() directly on Array

You can use reshape() method directly on the NumPy array

![](https://lh6.googleusercontent.com/XgXs9nV2Cin\_k8wy4lE2i6PACu97IXBHDk8zgub4XNAZuQuIHDc1OqTMK01VaLlgSJfXDAGEfzt6CwMhokSq1ieuFSyElMFUwC8t2dEgB4f6pGLLOWFz6NtTisRqYTeu7mGoV6czzOw)

![](https://lh5.googleusercontent.com/gJNkSNLgTl7aPAGwlSoBctzBeRleg03Sm7T4Ae5B3A979FQg2jVbyXMedodhFsRrjQ6HSA1GhswfFStttGP9uvv4Bo5f8\_XmTH8iLMOXJGBVAFcKHiIk2Z7zs5Zs6l858wXcvZySWlI)

**Caution!!!** Using reshape() method on a Python list will throw an ‘AttributeError’
