# mdmathjaxtests
<-- the scripts do not load when editing on GitHub, but they do load when viewing the site page -->
<script>
 MathJax = {
  loader: {
   load: ['[custom]/xypic.js'],
   paths: {custom: 'https://cdn.jsdelivr.net/gh/sonoisa/XyJax-v3@3.0.1/build/'}
  },
  tex: {
   inlineMath: [['$', '$'], ['\\(', '\\)']],
   packages: {'[+]': ['xypic']}
  }
 };
</script>
<script type="text/javascript" id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml-full.js"></script>

Linked content
--------------

$$ \int_a^b e^{-st}f(t) dt $$

Purpose
-------

* To experiment with MathJax and Markdown on GitHub 
* $x^2+y^2=1$
* [Linked content](linked.md)
* [GitHub MarkDown specification](https://github.github.com/gfm/)
* [GitHub Pages site for this project](https://yorickhardy.github.io/mdmathjaxtests/)
* [GitHub HTML page for this project](https://yorickhardy.github.io/mdmathjaxtests/xypic.html)

AMSCD diagram
-------------

$$\begin{CD} A @>>> & B \end{CD}$$

XY-Pic diagram (only works when viewing the pages directly)
--------------

\begin{xy}
 \xymatrix{ A \ar[r] & B }
\end{xy}
