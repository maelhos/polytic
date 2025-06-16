
# Polytic

Polytic is a fast library that extends on the **NTL** and **PML** to provide a fast Python binding for polynomial arithmetic
We aim at binding the following NTL elements :

- **ZZ**    : Big integers
- **ZZ_p**  : Big integers mod $p$
- **zz_p**  : ~$64$ bit integers mod $p$
- **zz_pX** : Univariate polynomials mod small $p$
- **zz_pX** : Univariate polynomials mod big $p$

As well as binding **PML* by Vincent Neiger:

- **zz_pXY** : Bivariate polynomials mod small $p$

And extending to multivariate as a standalone lib with:

- **ZZ_pXY** : Bivariate polynomials mod big $p$
- **zz_pXn** : Multivariate polynomials mod small $p$
- **ZZ_pXn** : Multivariate polynomials mod big $p$

And also, general finite fields and/ore binary fields in the future maybe... 