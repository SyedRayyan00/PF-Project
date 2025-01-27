# NAME : Syed Rayyan
# Roll : 175

import pandas as pd
import numpy as np
import seaborn as sns

# Summary of pandas, numpy, seaborn, and matplotlib

# Pandas
# Pandas is a powerful data manipulation and analysis library for Python.
# It provides data structures like Series and DataFrame to handle and analyze data efficiently.

# Numpy
# Numpy is a fundamental package for scientific computing in Python.
# It provides support for arrays, matrices, and many mathematical functions to operate on these data structures.

# Matplotlib
# Matplotlib is a plotting library for creating static, animated, and interactive visualizations in Python.
# It provides an object-oriented API for embedding plots into applications.
import matplotlib.pyplot as plt

# Seaborn
# Seaborn is a statistical data visualization library based on Matplotlib.
# It provides a high-level interface for drawing attractive and informative statistical graphics.

# Example usage of each library:

# Pandas: Creating a DataFrame
data = {'Name': ['Alice', 'Bob', 'Charlie'], 'Age': [25, 30, 35], 'Gender': ['F', 'M', 'M']}
df = pd.DataFrame(data)
print("Pandas DataFrame:\n", df)

# Numpy: Creating an array and performing operations
arr = np.array([1, 2, 3, 4, 5])
print("Numpy Array:\n", arr)
print("Sum of Numpy Array:", np.sum(arr))

# Matplotlib: Creating a simple plot
plt.plot(arr)
plt.title('Simple Plot')
plt.xlabel('Index')
plt.ylabel('Value')
plt.show()

# Seaborn: Creating a count plot
sns.countplot(x='Gender', data=df)
plt.title('Count Plot of Gender')
plt.show()# PF-Project



# Github link(https://github.com/SyedRayyan00/PF-Project.git)