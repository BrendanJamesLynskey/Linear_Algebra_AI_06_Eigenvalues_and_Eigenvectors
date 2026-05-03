# Eigenvalues &amp; Eigenvectors

Deck 06 of the [Linear Algebra for AI / ML](https://github.com/BrendanJamesLynskey/LLM_Hub_Linear_Algebra) series.

**Live presentation:** https://brendanjameslynskey.github.io/Linear_Algebra_AI_06_Eigenvalues_and_Eigenvectors/

A matrix's eigenvectors are the directions it doesn't rotate. Find them and the matrix becomes a diagonal &mdash; and a thousand questions about gradients, stability, PCA and Hessians become trivial. Includes an interactive 2D eigenvector animation.

## What's inside

- Definition of eigenvector / eigenvalue and the geometric picture
- Characteristic polynomial; trace and determinant identities
- Diagonalisation $A = V\Lambda V^{-1}$, powers, matrix exponentials, linear ODEs
- The spectral theorem for symmetric matrices: $A = Q\Lambda Q^\top$ with $Q^\top Q = I$
- Positive semi-definite / positive definite matrices and what they mean for ML
- Power iteration, inverse iteration, Lanczos, randomised SVD &mdash; how libraries actually compute spectra
- PCA as the most-used eigenproblem in ML
- Hessian eigenvalues, gradient flow, condition number, learning-rate stability
- Interactive 2D eigenvector animation (drag a 2&times;2 matrix, watch a unit circle deform into an ellipse along the eigendirections)

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
