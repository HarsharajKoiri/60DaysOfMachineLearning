# 1. What is Machine Learning?
  - Machine Learning (ML) = A method where computers learn from data instead of being explicitly programmed.

## Goal: 
  - Predict outcomes or find patterns.

- ML is a subset of Artificial Intelligence (AI).
  
---
## Example: 
  - Recommending videos on YouTube, spam detection in Gmail.

---
# 2. Types of Machine Learning			

  - ### Supervised Learning
      - Train with input and output (labeled data)
      - *Eg:* Email spam detection (spam/ham)
      
  - ### Unsupervised Learning
      - Train with only input, no output labels
      - *Eg:* Customer segmentation, Grouping similar news

  - ### Reinforcement Learning
      - Learn by reward and punishment
      - *Eg:* Teaching a robot to walk


---
# 3. Key Terminologies

<pre>
  Term                         Meaning<br>
  Model                      The algorithm that learns from data<br>
  Training                   Teaching the model with available data<br>
  Testing                    Checking model performance on new data<br>
  Features                   Input variables (example: size of house)<br>
  Labels                     Output variable (example: price of house)<br>
  Dataset                    Collection of data points (rows + columns)<br>
  Algorithm                  The logic that finds patterns (example: Decision Tree, Linear Regression)
</pre>
---
# 4. Very Important ML Cycle
   
    Collect Data   ➔
    Prepare Data   ➔
    Choose Model   ➔
    Train Model    ➔
    Evaluate Model ➔
    Predict New Data

---
# 5. Real-Life Examples of ML

  - YouTube recommends videos (based on your history).<br>
  - Netflix suggests shows.<br>
  - Credit card fraud detection.<br>
  - Self-driving cars.<br>
  - Medical diagnosis from X-rays.<br>


---
# code:

```simple python code:
# Simple Python program
x = 5
y = 10
print("Sum:", x + y)

# Loop through range
for i in range(5):
    print("Loop index:", i)
```
```Output:
Sum: 15
Loop index: 0
Loop index: 1
Loop index: 2
Loop index: 3
Loop index: 4
```

```Numpy Basics:
# Numpy array creation and basic operations
arr = np.array([1, 2, 3, 4, 5])
print("Numpy Array:", arr)

# Multiply array by 2
print("Array multiplied by 2:", arr * 2)
```
```Output:
Numpy Array: [1 2 3 4 5]
Array multiplied by 2: [ 2  4  6  8 10]
```
```Pandas Basics
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

# Pandas - Load Data and basic exploration
url = "https://raw.githubusercontent.com/jbrownlee/Datasets/master/iris.csv"
df = pd.read_csv(url)
print("First 5 rows of data:\n", df.head())

# Basic data description
print("Data Description:\n", df.describe())
```
```Output
First 5 rows of data:
    5.1  3.5  1.4  0.2  Iris-setosa
0  4.9  3.0  1.4  0.2  Iris-setosa
1  4.7  3.2  1.3  0.2  Iris-setosa
2  4.6  3.1  1.5  0.2  Iris-setosa
3  5.0  3.6  1.4  0.2  Iris-setosa
4  5.4  3.9  1.7  0.4  Iris-setosa
Data Description:
               5.1         3.5         1.4         0.2
count  149.000000  149.000000  149.000000  149.000000
mean     5.848322    3.051007    3.774497    1.205369
std      0.828594    0.433499    1.759651    0.761292
min      4.300000    2.000000    1.000000    0.100000
25%      5.100000    2.800000    1.600000    0.300000
50%      5.800000    3.000000    4.400000    1.300000
75%      6.400000    3.300000    5.100000    1.800000
max      7.900000    4.400000    6.900000    2.500000
```
```Simple Plot with Matplotlib
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

# Matplotlib - Plot a simple line graph
x = [1, 2, 3, 4, 5]
y = [2, 4, 6, 8, 10]

plt.plot(x, y)
plt.title("Simple Line Plot")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.show()
```
```Output
![download](https://github.com/user-attachments/assets/e1c8cae4-f2e3-408a-813b-fbe620704eca)
```
