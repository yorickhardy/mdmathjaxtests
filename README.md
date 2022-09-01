# mdmathjaxtests

Purpose
-------

* To experiment with MathJax and Markdown on GitHub 
* $x^2+y^2=1$
* [Linked content](linked.md)

$$\begin{CD} A @>>> & B \end{CD}$$

$\require{xypic}$

<script type="text/javascript">
  MathJax = {
    loader: {
      load: ['[custom]/xypic.js'],
      paths: {custom: 'https://cdn.jsdelivr.net/gh/sonoisa/XyJax-v3@3.0.1/build/'}
    },
    tex: {
      packages: {'[+]': ['xypic']}
    }
  };
</script>

\begin{xy}
 \xymatrix{ A \ar[r] & B }
\end{xy}
