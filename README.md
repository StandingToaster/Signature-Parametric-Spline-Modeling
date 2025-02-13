# Parametric Spline Representation of Signature

This project models handwritten signatures using parametric cubic splines, allowing for smooth interpolation of user-drawn points. It enables users to input signature segments, processes the points using cubic splines, and renders a smooth approximation.

## Features
- Interactive input where users manually select points from a signature image.
- Cubic spline interpolation using SciPy for smooth curve generation.
- Visualization of the reconstructed signature with segmented colors.
- Mathematical modeling with parametric splines for accurate representation.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/signature-spline.git
   cd signature-spline
Install dependencies:
bash
Copy
Edit
pip install numpy scipy matplotlib
Run the script:
bash
Copy
Edit
python signature_spline.py
Usage
The script loads an image of a handwritten signature.
Users select multiple segments using plt.ginput().
The program applies cubic spline interpolation to smooth the selected points.
The final reconstructed signature is displayed.
Technologies Used
NumPy for numerical computations.
SciPy for spline interpolation.
Matplotlib for visualization.
