# LaTeX Notes Template Reference
This is a styleguide for the LaTeX notes in this repository. This repository is based off the notes created by [Dexter Chua](https://dec41.user.srcf.net/notes/).

## Basic Elements

### Centering
```latex
\begin{center}
    [Your content]
\end{center}
```

### Drawing
```latex
\begin{tikzpicture}
    [Your drawing commands]
\end{tikzpicture}
```

### Equations
```latex
\[
    [Your equation]
\]
```

### Lists
```latex
\begin{itemize}
    \item [Item 1]
    \item [Item 2]
\end{itemize}
```

## Mathematical Formatting

### Mathematical Font
```latex
\mathcal{[Your Text]}
```

### Multi-line Problems
```latex
\begin{align*}
    [do something] \\
    &= \\
    &=
\end{align*}
```

### Integrals and Parentheses
```latex
\int_{bottom} [Expression]
\left( [Expression] \right)
```

## Mathematical Environments

### Theorem
```latex
\begin{thm}[Theorem Statement]
    [Your theorem content]
\end{thm}
```

### Definition
```latex
\begin{defi}[Definition]
    [Your definition content]
\end{defi}
```

### Proposition
```latex
\begin{prop}
    [Your Proposition]
\end{prop}
```

### Proof
```latex
\begin{proof}
    [Your Proof]
    \qedhere
\end{proof}
```

### Lemma
```latex
\begin{lemma}
    [Your Lemma]
\end{lemma}
```

## Advanced Structures

### Matrix
```latex
\begin{pmatrix}
    a1 & a2 \\
    b1 & b2
\end{pmatrix}
```

### Notation
```latex
\begin{notation}[Cycle Notation]
    [Your notation content]
\end{notation}
```

### Table
```latex
\begin{tabular}{lcr}
    \toprule
    [Column 1] & [Column 2] & [Column 3] \\
    \midrule
    [Column 1 Entry 1] & [Column 2 Entry 1] & [Column 3 Entry 3] \\
    \bottomrule
\end{tabular}
```

### Quantum Notation
```latex
\bra [State] \ket
```

### Example
```latex
\begin{eg}
    [Your Example]
\end{eg}
```
