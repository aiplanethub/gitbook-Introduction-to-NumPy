# Compare Python List and NumPy Array

|                                Python List VS                                 |                                   NumPy Array                                   |
| :---------------------------------------------------------------------------: | :-----------------------------------------------------------------------------: |
|                    Can contain data of different data types                   |                        Can contain data of same data type                       |
| Takes huge amount of time and memory for numerical computations of large data | Very cheap in terms of time and memory for numerical computations of large data |

### Compare Python List & Numpy Array

* Create two lists:

![](https://lh5.googleusercontent.com/3X4w8p9-TfwsLgETsvMZ4AqASsguVslLa19qoBhNc9KHyf689r9wVbhDspoSZU\_X\_WawbbFIZUZPKPSC23plV1NcC6OY\_PDI81aC0E10A-VFZKmitbVNrPZXFXdXNDVN1MmeMw9V7Kw)

* Import NumPy and Create two numpy array using two Python lists:

![](https://lh3.googleusercontent.com/eATf4uQhlASiP1D-sWkPtqirUCEzvO\_ze4szNncJC64ISUrCRAlRyMbLFozfhbTOI1maEvwUG0bF2asVG6Zby6ORvOICqvd7Evvv5ITulh7kreF84yyzGQZNjs33PoeaQxKTlmrk7oY)

* Define a function that will perform element wise addition of two Python lists.

![](https://lh3.googleusercontent.com/BA4KBWhub7myd4-IXyVifyKhkWrWJ3dTyPBkU6uQNNRw4lBL6VA-FgnnsDEDD4y4HMheGNmBpwN8qFUxMvDM2Gv7i2KURrVZiUAbBIKrb\_kId5rZ39QTeUGCZxLei4xY5qJQ-26WOXM)

* Define a function that will perform element wise addition of two NumPy arrays.

![](https://lh3.googleusercontent.com/QG3zCB3x4YHU97XH1pF03DQoTJu6k4Zt0CFLWCf-yz\_q7caXdLUA8P7cNFSaEUgHfiS2p3bony4euNUWafVOcpxea3fSzpqvE31w7YOUyuPgjm1DqXaEu8-g7B0hJBp1Xfb2OvEoX\_Q)

* Notice the time taken by both the functions (i.e. list\_sum() and numpy\_arr\_sum()) to perform same task.

![](https://lh3.googleusercontent.com/D47Rq719KGhn-pdgBM3jT55W6mT-TWJcZBh\_LSSyYyITFYnQBdCVlC8-kZXg9kcSgPi-MXfM0tj-B4y8kyUKOzHr3sahJyScSSdU8fdfCgDjpwdVYZyR8-kIi8tqKcDn5ILVqGwvlnM)

* You can observe here, the time taken by python list to do the element wise sum is much much more than the NumPy arrays.
