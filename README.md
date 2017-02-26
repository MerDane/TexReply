#Reply Latex
This reply template of PHD thesis is modified from:
https://www.latextemplates.com/template/frequently-asked-questions
## Usage:
```
\question{Question}{page number}{ans}
```
which only consists of direct answer for the question or suggestion.

```
\qwithr{Question}{page number}{ans}{Revised text}
```
which includes not only the answer but also the revised text from the thesis.
##Example:
```latex
\question{you can directly use the equation form in answer part}{the page}{\\ some equations as:%
\begin{equation}
	g(x)=\frac { 1 }{ 1+{ e }^{ -kx } } 
\end{equation}
and equation 2.5 as:
\begin{equation}
	{ g' }(x)\quad =\quad g(x)[1-g(x)]\cdot{k}
\end{equation}}%
```
##PDF compile
```shell
compile.bat #to compile the pdf
```
