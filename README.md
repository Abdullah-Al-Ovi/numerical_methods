# Numerical Methods Assignment

This repository contains a Python program that demonstrates essential numerical methods, including Forward Difference, Backward Difference, Centered Difference, and Missing Value Interpolation. The program computes results based on user inputs and displays them both in the terminal and graphically as tables using Matplotlib.

## Features

1. **Forward Difference**:

   - Computes the forward differences for a given dataset.
   - Results are displayed in a tabular format.

2. **Backward Difference**:

   - Computes the backward differences for the dataset.
   - Results are displayed in a tabular format.

3. **Centered Difference**:

   - Computes central differences for the dataset.
   - Displays results in a tabular format.

4. **Missing Value Interpolation**:

   - Estimates missing `y` values in the dataset using linear interpolation.
   - Highlights the interpolated value in the graphical output.

## Prerequisites

Make sure you have the following installed on your system:

- Python 3.8 or higher
- pip (Python package manager)

Required Python libraries:

- `pandas`
- `matplotlib`

## Installation

Follow these steps to clone and run the project:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Abdullah-Al-Ovi/numerical_methods.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd numerical_methods
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

   > If a `requirements.txt` file is not included, you can manually install the required libraries:

   ```bash
   pip install pandas matplotlib
   ```

4. **Run the Program**:

   ```bash
   python numerical_assignment.py
   ```

## Usage

1. Launch the program by running `python numerical_methods.py`.
2. Follow the prompts to:
   - Enter the number of data points.
   - Provide `x` and `y` values for the dataset (use `None` or leave blank for missing values).
   - Choose a numerical method to compute.
3. View the results in the terminal or as a graphical table.

## Examples

### Example 1: Forward Difference

#### Input:

```
Choose an option (1-4): 1
Enter the number of data points: 4
Enter the x-values:
1
2
3
4
Enter the y-values:
2
4
7
11
```

#### Output:

A graphical table pops up displaying the forward differences:

```
+-----+-----+-------------------+
|  x  |  y  | Forward Difference |
+-----+-----+-------------------+
| 1.0 | 2.0 | 2.0               |
| 2.0 | 4.0 | 3.0               |
| 3.0 | 7.0 | 4.0               |
| 4.0 | 11.0| Not available               |
+-----+-----+-------------------+
```

### Example 2: Missing Value Interpolation

#### Input:

```
Choose an option (1-4): 4
Enter the number of data points: 4
Enter the x-values:
1
2
3
4
Enter the y-values (use 'None' for missing values):
2
4
None
11
```

#### Output:

A graphical table pops up with the interpolated value highlighted:

```
+-----+-----+
|  x  |  y  |
+-----+-----+
| 1.0 | 2.0 |
| 2.0 | 4.0 |
| 3.0 | 7.5 |  <- Highlighted (gold background)
| 4.0 | 11.0|
+-----+-----+
```

## Contributing

Contributions are welcome! Feel free to fork the repository, make improvements and make a pull request.


