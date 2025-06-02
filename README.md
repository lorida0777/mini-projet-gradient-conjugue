# mini-projet-gradient-conjugue
Implémentation manuelle du gradient conjugué pour résoudre des systèmes linéaires à matrices creuses SDP issus du problème de Poisson 2D, avec comparaison de l’effet des préconditionneurs Jacobi et SSOR sur la convergence.


# Méthode du Gradient Conjugué

Ce projet compare l'implémentation du Gradient Conjugué :

- `numpy_version/` : version manuelle sans bibliothèques externes, matrice dense.
- `scipy_version/` : version avec matrice creuse (scipy.sparse) et préconditionneurs Jacobi et SSOR.

## Lancer les notebooks

```bash
cd numpy_version
jupyter notebook gradient_conjugue_numpy.ipynb

