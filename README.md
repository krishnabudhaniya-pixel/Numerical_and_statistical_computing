# Numerical and Statistical Computing

This repository contains beginner-friendly Python programs for common Numerical Methods used in B.Tech lab practicals.

All programs are:
- Written in simple and basic Python.
- Ready to run directly (no user input required).
- Built with predefined sample values for quick analysis.
- Designed to show iteration-wise steps where applicable.
- Suitable for practical exam preparation and record writing.

## Methods Included

1. Bisection Method
2. Regula Falsi Method
3. Newton-Raphson Method
4. Gauss Elimination Method
5. Jacobi Iteration Method
6. Gauss-Seidel Method
7. Newton Forward Interpolation Method
8. Newton Backward Interpolation Method

## File List

- [bisection_method.py](bisection_method.py)
- [regula_falsi_method.py](regula_falsi_method.py)
- [newton_raphson_method.py](newton_raphson_method.py)
- [gauss_elimination_method.py](gauss_elimination_method.py)
- [jacobi_iteration_method.py](jacobi_iteration_method.py)
- [gauss_seidel_method.py](gauss_seidel_method.py)
- [newton_forward_interpolation.py](newton_forward_interpolation.py)
- [newton_backward_interpolation.py](newton_backward_interpolation.py)

## Requirements

- Python 3.x installed

Check Python version:

```bash
python3 --version
```

## How to Run

Run any file using:

```bash
python3 file_name.py
```

Examples:

```bash
python3 bisection_method.py
python3 gauss_elimination_method.py
python3 newton_forward_interpolation.py
```

## Method-Wise Notes

### 1) Bisection Method
- Uses sample equation: $f(x) = x^3 - x - 2$
- Uses fixed interval and tolerance.
- Prints iteration table with midpoint and error.
- Prints final approximate root.

### 2) Regula Falsi Method
- Uses sample equation: $f(x) = x^3 - x - 2$
- Uses fixed interval and tolerance.
- Prints iteration table with false-position value and error.
- Prints final approximate root.

### 3) Newton-Raphson Method
- Uses sample equation: $f(x) = x^3 - x - 2$
- Uses derivative: $f'(x) = 3x^2 - 1$
- Uses fixed initial guess and tolerance.
- Prints iteration-wise values and final root.

### 4) Gauss Elimination Method
- Uses predefined augmented matrix for a 3-variable system.
- Shows elimination steps.
- Uses back substitution to print final values of $x_1, x_2, x_3$.

### 5) Jacobi Iteration Method
- Uses predefined linear system.
- Starts with initial approximation $(0, 0, 0)$.
- Shows iteration table and max error.
- Stops on convergence and prints final solution.

### 6) Gauss-Seidel Method
- Uses predefined linear system.
- Starts with initial approximation $(0, 0, 0)$.
- Uses latest values within each iteration.
- Prints iteration table and final converged solution.

### 7) Newton Forward Interpolation
- Uses predefined equally spaced $x$ and tabulated $y$ values.
- Builds forward difference table.
- Computes interpolated value at predefined $x_p$.

### 8) Newton Backward Interpolation
- Uses predefined equally spaced $x$ and tabulated $y$ values.
- Builds difference table.
- Computes interpolated value at predefined $x_p$ near the end of the table.

## Practical Exam Use

This repository is useful for:
- Last-minute practical revision.
- Understanding step-by-step numerical procedures.
- Running methods quickly without taking manual input.
- Writing clean and simple exam code.

## Customization

To test different problems, edit sample values directly in each file:
- Equation and interval/initial guess for root-finding files.
- Matrix coefficients/constants for linear system files.
- Table values and interpolation point for interpolation files.

## License

This project is for educational and academic practice use.
