## semver

```latex
\providecommand{\version}{1.0.1}

\begin{document}
  hello, current version is \version

  \semverEq{\version}{1.0.1}{
    Version is exactly 1.0.1
  }{}

  \semverGe{\version}{1.0.0}{
    Version is >= 1.0.0
  }{}

  \semverLe{\version}{2.0.0}{
    Version is <= 2.0.0
  }{}

  \semverBetween{\version}{1.0.0}{2.0.0}{
    Version is between 1.0.0 and 2.0.0
  }{}
\end{document}
```
