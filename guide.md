## Structure
To create a LaTeX document, you need to define its structure using the following commands:
| Command | Purpose |
| ------- | ------- |
|\documentclass{article}| % Define the document class|
|\usepackage{amsmath} | % Load the amsmath package for math environments |
| \begin{document} ... \end{document}| % The contents of the document |

## Basic Math Mode
To include mathematical equations in your LaTeX document, you need to use math mode, which is indicated by dollar signs or double dollar signs:
| Command | Purpose |
| ------- | ------- |
| $a+b=c$  |                 % Single-line math mode|
|$$a+b=c$$   |              % Multi-line math mode|

## Basic Math Environments
LaTeX provides several math environments that can be used for displaying mathematical equations:
| Command | Purpose |
| ------- | ------- |
|\begin{equation} ... \end{equation} |  % Displayed equation|
|\begin{align} ... \end{align}   |      % Aligned equations|
|\begin{gather} ... \end{gather}   |    % Grouped equations|
|\begin{cases} ... \end{cases}      |   % Cases |

## Basic Symbols
LaTeX provides a wide range of symbols that can be used in mathematical equations. Some commonly used symbols include:
+   -   \cdot   \times   \div   =   \neq
<   >   \leq    \geq     \pm    \mp   \sqrt{}
\in \subset \supset \cup     \cap   \not
\alpha   \beta  \gamma   \theta   \pi    \phi  \varphi
\sin     \cos   \tan     \log     \lim   \int

## Fractions and Exponents
To write fractions and exponents in LaTeX, you can use the following commands:
| Command | Purpose |
| ------- | ------- |
|\frac{numerator}{denominator}   |   % Fraction|
|a^b                                % Exponent|
|\sqrt[n]{expression}      |        % n-th root|

## Matrices
To write matrices in LaTeX, you can use the matrix environment:

\begin{equation}

\begin{matrix}

a_{11} & a_{12} & \cdots & a_{1n} \\

a_{21} & a_{22} & \cdots & a_{2n} \\

\vdots & \vdots & \ddots & \vdots \\

a_{m1} & a_{m2} & \cdots & a_{mn}

\end{matrix}

\end{equation}


## Brackets and Parentheses
To write brackets and parentheses in LaTeX, you can use the following commands:
| Command | Purpose |
| ------- | ------- |
|( expression ) |    % Parentheses|
[ expression ]  |   % Square brackets|
\{ expression \}|   % Curly brackets|
| l expression l  |   % Absolute value|
\langle expression \rangle  | % Angle brackets|


