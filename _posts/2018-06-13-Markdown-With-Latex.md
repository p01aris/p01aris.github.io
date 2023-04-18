---
layout: post
title: Linux zfs configuarion
usemathjax: true
---
# Markdown Note

*Italic* and **Bold**

~~Scratched Text~~

superscript^2^

# #Show Pic

```
![Hello World](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEYAAAAUCAAAAAAVAxSkAAABrUlEQVQ4y+3TPUvDQBgH8OdDOGa+oUMgk2MpdHIIgpSUiqC0OKirgxYX8QVFRQRpBRF8KShqLbgIYkUEteCgFVuqUEVxEIkvJFhae3m8S2KbSkcFBw9yHP88+eXucgH8kQZ/jSm4VDaIy9RKCpKac9NKgU4uEJNwhHhK3qvPBVO8rxRWmFXPF+NSM1KVMbwriAMwhDgVcrxeMZm85GR0PhvGJAAmyozJsbsxgNEir4iEjIK0SYqGd8sOR3rJAGN2BCEkOxhxMhpd8Mk0CXtZacxi1hr20mI/rzgnxayoidevcGuHXTC/q6QuYSMt1jC+gBIiMg12v2vb5NlklChiWnhmFZpwvxDGzuUzV8kOg+N8UUvNBp64vy9q3UN7gDXhwWLY2nMC3zRDibfsY7wjEkY79CdMZhrxSqqzxf4ZRPXwzWJirMicDa5KwiPeARygHXKNMQHEy3rMopDR20XNZGbJzUtrwDC/KshlLDWyqdmhxZzCsdYmf2fWZPoxCEDyfIvdtNQH0PRkH6Q51g8rFO3Qzxh2LbItcDCOpmuOsV7ntNaERe3v/lP/zO8yn4N+yNPrekmPAAAAAElFTkSuQmCC)
```

## LaTeX

Upmath converts LaTeX equations in double-dollars `$$`: $$ax^2+bx+c=0$$. All equations are rendered as block equations. If you need inline ones, you can add the prefix `\inline`: \inline $$  \inline p={1\over q}$$. Place big equations on separate lines:

$$x_{1,2} = {-b\pm\sqrt{b^{2*3} - 4ac} \over 2a}.$$

In this case the LaTeX syntax will be highlighted in the source code. You can even add equation numbers (unfortunately there is no automatic numbering and refs support):

$$\|\vec{A}\|=\sqrt{A_x^2 + A_y^2 + A_z^2}.$$ (1)

It is possible to write Cyrillic symbols in `\text` command: $$Q_\text{плавления}>0$$.

One can use matrices:

$$T^{\mu\nu}=\begin{pmatrix}
\varepsilon&0&0&0\\
0&\varepsilon/3&0&0\\
0&0&\varepsilon/3&0\\
0&0&0&\varepsilon/3
\end{pmatrix},$$

integrals:

$$P_\omega={n_\omega\over 2}\hbar\omega\,{1+R\over 1-v^2}\int\limits_{-1}^{1}dx\,(x-v)|x-v|,$$


- $$\pi \approx 3.14159$$
- $$\pm \, 0.2$$
- $$\dfrac{0}{1} \neq \infty$$
- $$0 < x < 1$$
- $$0 \leq x \leq 1$$
- $$x \geq 10$$
- $$\forall \, x \in (1,2)$$
- $$\exists \, x \notin [0,1]$$
- $$A \subset B$$
- $$A \subseteq B$$
- $$A \cup B$$
- $$A \cap B$$
- $$X \implies Y$$
- $$X \impliedby Y$$
- $$a \to b$$
- $$a \longrightarrow b$$
- $$a \Rightarrow b$$
- $$a \Longrightarrow b$$
- $$a \propto b$$
- 

```
- $$\pi \approx 3.14159$$
- $$\pm \, 0.2$$
- $$\dfrac{0}{1} \neq \infty$$
- $$0 < x < 1$$
- $$0 \leq x \leq 1$$
- $$x \geq 10$$
- $$\forall \, x \in (1,2)$$
- $$\exists \, x \notin [0,1]$$
- $$A \subset B$$
- $$A \subseteq B$$
- $$A \cup B$$
- $$A \cap B$$
- $$X \implies Y$$
- $$X \impliedby Y$$
- $$a \to b$$
- $$a \longrightarrow b$$
- $$a \Rightarrow b$$
- $$a \Longrightarrow b$$
- $$a \propto b$$
```

```
- $$\bar a$$
- $$\bar a$$
- $$\tilde a$$
- $$\breve a$$
- $$\hat a$$
- $$a^ \prime$$
- $$a^ \dagger$$
- $$a^ \ast$$
- $$a^ \star$$
- $$\mathcal A$$
- $$\mathrm a$$
- $$\cdots$$
- $$\vdots$$
- $$\#$$
- $$\$$$
- $$\%$$
- $$\&$$
- $$\{ \}$$
- $$\_$$
```

- $$\bar a$$
- $$\tilde a$$
- $$\breve a$$
- $$\hat a$$
- $$a^ \prime$$
- $$a^ \dagger$$
- $$a^ \ast$$
- $$a^ \star$$
- $$\mathcal A$$
- $$\mathrm a$$
- $$\cdots$$
- $$\vdots$$
- $$\#$$
- $$\$$$
- $$\%$$
- $$\&$$
- $$\{ \}$$
- $$\_$$

| $\alpha$   | `A`        |               |
| ---------- | ---------- | ------------- |
| `\beta`    | `B`        |               |
| `\gamma`   | `\Gamma`   |               |
| `\delta`   | `\Delta`   |               |
| `\epsilon` | `E`        | `\varepsilon` |
| `\zeta`    | `Z`        |               |
| `\eta`     | `H`        |               |
| `\theta`   | `\Theta`   | `\vartheta`   |
| `\zeta`    | `I`        |               |
| `\kappa`   | `K`        | `\varkappa`   |
| `\lambda`  | `\Lambda`  |               |
| `\mu`      | `M`        |               |
| `\nu`      | `N`        |               |
| `\xi`      | `\Xi`      |               |
| `\omicron` | `O`        |               |
| `\pi`      | `\Pi`      | `\varpi`      |
| `\rho`     | `P`        | `\varrho`     |
| `\sigma`   | `\Sigma`   | `\varsigma`   |
| `\tau`     | `T`        |               |
| `\upsilon` | `\Upsilon` |               |
| `\phi`     | `\Phi`     | `\varphi`     |
| `\chi`     | `X`        |               |
| `\psi`     | `\Psi`     |               |
| `\omega`   | `\Omega`   |               |

| $$\alpha$$   | $$A$$        |                 |
| $$\beta$$    | $$B$$        |                 |
| $$\gamma$$   | $$\Gamma$$   |                 |
| $$\delta$$   | $$\Delta$$   |                 |
| $$\epsilon$$ | $$E$$        | $$\varepsilon$$ |
| $$\zeta$$    | $$Z$$        |                 |
| $$\eta$$     | $$H$$        |                 |
| $$\theta$$   | $$\Theta$$   | $$\vartheta$$   |
| $$\zeta$$    | $$I$$        |                 |
| $$\kappa$$   | $$K$$        | $$\varkappa$$   |
| $$\lambda$$  | $$\Lambda$$  |                 |
| $$\mu$$      | $$M$$        |                 |
| $$\nu$$      | $$N$$        |                 |
| $$\xi$$      | $$\Xi$$      |                 |
| $$\omicron$$ | $$O$$        |                 |
| $$\pi$$      | $$\Pi$$      | $$\varpi$$      |
| $$\rho$$     | $$P$$        | $$\varrho$$     |
| $$\sigma$$   | $$\Sigma$$   | $$\varsigma$$   |
| $$\tau$$     | $$T$$        |                 |
| $$\upsilon$$ | $$\Upsilon$$ |                 |
| $$\phi$$     | $$\Phi$$     | $$\varphi$$     |
| $$\chi$$     | $$X$$        |                 |
| $$\psi$$     | $$\Psi$$     |                 |
| $$\omega$$   | $$\Omega$$   |                 |

cool tikz-pictures:

$$\usetikzlibrary{decorations.pathmorphing}
\begin{tikzpicture}[line width=0.2mm,scale=1.0545]\small
\tikzset{>=stealth}
\tikzset{snake it/.style={->,semithick,
decoration={snake,amplitude=.3mm,segment length=2.5mm,post length=0.9mm},decorate}}
\def\h{3}
\def\d{0.2}
\def\ww{1.4}
\def\w{1+\ww}
\def\p{1.5}
\def\r{0.7}
\coordinate[label=below:$A_1$] (A1) at (\ww,\p);
\coordinate[label=above:$B_1$] (B1) at (\ww,\p+\h);
\coordinate[label=below:$A_2$] (A2) at (\w,\p);
\coordinate[label=above:$B_2$] (B2) at (\w,\p+\h);
\coordinate[label=left:$C$] (C1) at (0,0);
\coordinate[label=left:$D$] (D) at (0,\h);
\draw[fill=blue!14](A2)--(B2)-- ++(\d,0)-- ++(0,-\h)--cycle;
\draw[gray,thin](C1)-- +(\w+\d,0);
\draw[dashed,gray,fill=blue!5](A1)-- (B1)-- ++(\d,0)-- ++(0,-\h)-- cycle;
\draw[dashed,line width=0.14mm](A1)--(C1)--(D)--(B1);
\draw[snake it](C1)--(A2) node[pos=0.6,below] {$c\Delta t$};
\draw[->,semithick](\ww,\p+0.44*\h)-- +(\w-\ww,0) node[pos=0.6,above] {$v\Delta t$};
\draw[snake it](D)--(B2);
\draw[thin](\r,0) arc (0:atan2(\p,\w):\r) node[midway,right,yshift=0.06cm] {$\theta$};
\draw[opacity=0](-0.40,-0.14)-- ++(0,5.06);
\end{tikzpicture}$$

plots:

$$\begin{tikzpicture}[scale=1.0544]\small
\begin{axis}[axis line style=gray,
    samples=120,
    width=9.0cm,height=6.4cm,
    xmin=-1.5, xmax=1.5,
    ymin=0, ymax=1.8,
    restrict y to domain=-0.2:2,
    ytick={1},
    xtick={-1,1},
    axis equal,
    axis x line=center,
    axis y line=center,
    xlabel=$x$,ylabel=$y$]
\addplot[red,domain=-2:1,semithick]{exp(x)};
\addplot[black]{x+1};
\addplot[] coordinates {(1,1.5)} node{$y=x+1$};
\addplot[red] coordinates {(-1,0.6)} node{$y=e^x$};
\path (axis cs:0,0) node [anchor=north west,yshift=-0.07cm] {0};
\end{axis}
\end{tikzpicture}$$
