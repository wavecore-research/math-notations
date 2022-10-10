# math-notations
Mathematical notations used in our work.


Vectors are denoted by boldface lower case $\boldsymbol{\mathrm{x}}$ and matrices by boldface capital letters $\boldsymbol{\mathrm{X}}$.
The superscript ${(\cdot)}^T$ is used to denote the transpose operation. The absolute value is denoted by $\left\lvert \cdot \right\rvert$ for vectors and scalars, while the same notation is used to denote the determinant of a matrix.
The notation $\mathbb{E} \left\lbrace \cdot \right\rbrace$ denotes the expectation of a random variable. The set of complex numbers is denoted by the symbol $\mathbb{C}$ and the set of strictly positive numbers by $\mathbb{R}^+$. The uniform distribution bounded by the closed interval between $a$ and $b$ is denoted by $\mathcal{U}_{[a, b]}$. The angle of a complex scalar or vector is denoted by $\angle$. The operator $\diag \left( \cdot \right)$ is applied in two ways, when operating on a vector it yields a matrix with the input vector on the main diagonal and zeros elsewhere. When operating on a matrix $\diag \left(\cdot\right)$ returns the main diagonal entries as a vector. The standard complex normal (Gaussian) distribution with mean $\mu$, standard deviation $\sigma$ is denoted by $\mathcal{C}\mathcal{N}\left(\mu,\sigma^2\right)$.


Used LaTex commands:
```latex
\newcommand{\vect}[1]{\boldsymbol{\mathrm{#1}}}
\newcommand{\mat}[1]{\boldsymbol{\mathrm{#1}}}
\newcommand{\MSE}{\mathrm{MSE}}
\newcommand{\tr}{\mathrm{tr}}
\newcommand{\moddef}{\mathrm{mod}}
\newcommand{\diag}{\mathrm{diag}}
\newcommand{\vecop}{\text{vec}}
\newcommand{\hddots}{\hdots}
\newcommand*{\inC}[1]{\in\mathbb{C}^{#1}}
\newcommand{\abs}[1]{\left\lvert#1\right\rvert}
\newcommand{\expt}[1]{\mathbb{E} \left\{#1\right\}}
\newcommand{\cn}[2]{\ensuremath{\sim\mathcal{C}\mathcal{N}\left(#1,#2\right)}}
\newcommand{\norm}[1]{\left\lVert#1\right\rVert}
```
