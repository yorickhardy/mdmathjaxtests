# mdmathjaxtests

Purpose
-------

* To experiment with MathJax and Markdown on GitHub 
* $x^2+y^2=1$
* [Linked content](linked.md)
* [GitHub MarkDown specification](https://github.github.com/gfm/)

$$\begin{CD} A @>>> & B \end{CD}$$

*xypic* **does not work** because github disables _script_ tags:
<script type="text/javascript" src="xypic.js">
</script>

$\require{xypic}$


\begin{xy}
 \xymatrix{ A \ar[r] & B }
\end{xy}

<iframe src="https://github.com/yorickhardy/mdmathjaxtests/raw/main/xypic.html"></iframe>
