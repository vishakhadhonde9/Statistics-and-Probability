# Matplotlib -
- Matplotlib is the most popular Python library used for data visualization. It helps us create graphs, charts, and plots from data.
- It was developed by John D. Hunter in 2003 and is widely used in:

      Data Science
      Machine Learning
      Artificial Intelligence
      Statistics
      Scientific Computing
      Business Analytics

- Using Matplotlib, we can convert numerical data into visual representations that are easier to understand.
- It is used to create: Line charts, Bar charts, Histograms, Scatter plots, Pie charts, Subplots and Statistical visualizations.

## Syntax:

          import matplotlib.pyplot as plt

- matplotlib is a Python library used for data visualization.
- pyplot is a module inside Matplotlib that contains plotting functions.
- plt is just a short alias (nickname) for matplotlib.pyplot.

## Modules -

| Module | Purpose |
|---------|---------|
| `matplotlib.pyplot` | Create plots and charts easily |
| `matplotlib.figure` | Create and manage figures |
| `matplotlib.axes` | Handle axes, labels, ticks, and plotting area |
| `matplotlib.colors` | Work with colors and colormaps |
| `matplotlib.animation` | Create animations |
| `matplotlib.image` | Read and display images |
| `matplotlib.patches` | Draw shapes like circles, rectangles, and polygons |
| `matplotlib.lines` | Create and customize line objects |
| `matplotlib.style` | Apply predefined plot styles |

## Common Matplotlib Functions -

| Function | Purpose |
|----------|---------|
| `plot()` | Line Chart |
| `scatter()` | Scatter Plot |
| `bar()` | Bar Chart |
| `hist()` | Histogram |
| `pie()` | Pie Chart |
| `boxplot()` | Box Plot |
| `figure()` | Create Figure |
| `subplots()` | Multiple Plots |
| `title()` | Add Title |
| `xlabel()` | X-Axis Label |
| `ylabel()` | Y-Axis Label |
| `legend()` | Show Legend |
| `grid()` | Show Grid |
| `savefig()` | Save Chart |
| `show()` | Display Chart |


      import matplotlib.pyplot as plt
      
      x = [1,2,3,4]
      y = [10,20,30,40]
      
      plt.plot(x,y)
      
      plt.title("Sample Plot")
      
      plt.xlabel("X")
      
      plt.ylabel("Y")
      
      plt.grid(True)
      
      plt.show()


### Customizing Line Plot -

# Matplotlib Colors, Line Styles, and Markers

| Colors | Line Styles | Markers |
|---------|------------|----------|
| `red` | `'-'` (Solid) | `'o'` (Circle) |
| `blue` | `'--'` (Dashed) | `'s'` (Square) |
| `green` | `':'` (Dotted) | `'^'` (Triangle) |
| `black` | `'-.'` (Dash Dot) | `'*'` (Star) |
| `yellow` |  | `'+'` (Plus) |
| `cyan` |  | `'x'` (Cross) |
| `magenta` |  |  |

### numpy (Core) -

| Function | Simple Explanation | Example | Output |
|----------|-------------------|---------|--------|
| `np.array()` | Converts a Python list or tuple into a NumPy array. | `np.array([1, 2, 3])` | `[1 2 3]` |
| `np.arange()` | Creates numbers within a range with a fixed step size. | `np.arange(1, 10, 2)` | `[1 3 5 7 9]` |
| `np.linspace()` | Creates a fixed number of evenly spaced values between two numbers. | `np.linspace(0, 10, 5)` | `[0. 2.5 5. 7.5 10.]` |
| `np.zeros()` | Creates an array where all values are `0`. | `np.zeros((2,3))` | `[[0. 0. 0.] [0. 0. 0.]]` |
| `np.ones()` | Creates an array where all values are `1`. | `np.ones((2,3))` | `[[1. 1. 1.] [1. 1. 1.]]` |
| `np.eye()` | Creates an identity matrix (diagonal values are `1`, others are `0`). | `np.eye(3)` | `[[1. 0. 0.] [0. 1. 0.] [0. 0. 1.]]` |

### NumPy Linear Algebra Functions (`numpy.linalg`)

| Function | Simple Explanation |
|----------|-------------------|
| `la.det()` | Calculates the determinant of a square matrix. |
| `la.inv()` | Calculates the inverse of a square matrix. |
| `la.eig()` | Finds eigenvalues and eigenvectors of a matrix. |
| `la.solve()` | Solves a system of linear equations. |
| `la.norm()` | Calculates the length (magnitude) of a vector or matrix. |

# NumPy Random Functions (`numpy.random`)

| Function | Simple Explanation |
|----------|-------------------|
| `random.rand()` | Generates random floating-point numbers between 0 and 1. |
| `random.randn()` | Generates random numbers from a normal (Gaussian) distribution. |
| `random.randint()` | Generates random integers within a specified range. |
| `random.choice()` | Randomly selects one or more elements from a given array or list. |
| `random.shuffle()` | Randomly rearranges (shuffles) the elements of an array. |











