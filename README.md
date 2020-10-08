# Haynes-Shockley experiment
> The Charge mobility in semiconductor materials
## goals
- Minority charge carriers amount.
- The effect of the distance between electrodes on the specimen in the production of electrons and holes.
- Measuring of carrier’s lifetime.

![config](./image.jpg)

***Photo electric effect (laser beam) causes the drift mobility of minority charge carriers sweeps length of the semiconductor.***

Important fields: ***lifetime, drift velocity, electric field***
<hr>
<h2>Measurement of drift velocity</h2>
<p>
E<sub>s</sub> is an internal electric pulse field that produced by a pulsed generator. Distance between optical fiber and needle (<ins>point contact</ins>) is d. V<sub>s</sub> is the electrical pulls and V<sub>l</sub> is the laser pulls. The laser pulls causes 2 small peak between up and down main semiconductor peak. The
second peak is the wider and relevant to minority carriers. 
<mark/>V<sub>d</sub> = <pre xml:lang="latex">x/y</pre> </mark>(<span>&#247;</span>) 

is the drift velocity.
</p>

```javascript
function test() {
 console.log("look ma’, no spaces");
}
```

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
