<p>Examples</p>
<ul>
<li><a href="https://smartdown.site/">Smartdown Gallery</a></li>
<li><a href="https://smartdown.site/">Smartdown README.md</a></li>
</ul>
<p>Select File</p>
<h2 id="math-notation">Math Notation</h2>
<p>By using MathJax, we can display all sorts of notation.</p>
<p>We can do inline math: <span class="katex--inline"><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>E</mi><mo>=</mo><mi>m</mi><msup><mi>c</mi><mn>2</mn></msup></mrow><annotation encoding="application/x-tex">E = mc^2</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height: 0.814108em;"></span><span class="strut bottom" style="height: 0.814108em; vertical-align: 0em;"></span><span class="base"><span class="mord mathit" style="margin-right: 0.05764em;">E</span><span class="mrel">=</span><span class="mord mathit">m</span><span class="mord"><span class="mord mathit">c</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height: 0.814108em;"><span class="" style="top: -3.063em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathrm mtight">2</span></span></span></span></span></span></span></span></span></span></span></span></p>
<p>Or we can do block math:</p>
<p><span class="katex--display"><span class="katex-display"><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>A</mi><mo>⟶</mo><mi>B</mi></mrow><annotation encoding="application/x-tex">
A \longrightarrow B
</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height: 0.68333em;"></span><span class="strut bottom" style="height: 0.69433em; vertical-align: -0.011em;"></span><span class="base"><span class="mord mathit">A</span><span class="mrel">⟶</span><span class="mord mathit" style="margin-right: 0.05017em;">B</span></span></span></span></span></span></p>
<p><span class="katex--display">KaTeX parse error: Expected &amp; or \\ or \end at position 73: …text{Right} \\
\̲h̲l̲i̲n̲e̲
1 &amp; 0.24 &amp; 1 &amp;…</span></p>
<p>And even diagrams via <em>xyjax</em>:</p>
<p><span class="katex--display">KaTeX parse error: No such environment: xy at position 8: 
\begin{̲x̲y̲}̲
0;&lt;1em,0em&gt;:
(…</span></p>
<p><span class="katex--display">KaTeX parse error: No such environment: xy at position 8: 
\begin{̲x̲y̲}̲
\xymatrix {
U …</span></p>
<h4 id="testing-out-html-entity-escaping">Testing out HTML entity escaping</h4>
<p>Often we’ll use</p>
<h4 id="mathjax-latex-vs-asciimath-syntax">MathJax <span class="katex--inline">KaTeX parse error: Expected 'EOF', got '\LaTeX' at position 1: \̲L̲a̲T̲e̲X̲</span> vs AsciiMath Syntax</h4>
<p>Recently, I learned that MathJax had an alternative syntax, <a href="http://asciimath.org">AsciiMath</a> that is simpler for many purposes. Smartdown has enabled this feature, although we are currently using <code>@</code> as the delimiter instead of ` or <code>$</code>.</p>
<h5 id="latex-syntax"><span class="katex--inline">KaTeX parse error: Expected 'EOF', got '\LaTeX' at position 1: \̲L̲a̲T̲e̲X̲</span> Syntax</h5>
<p>Currently, Smartdown uses LaTeX-style math syntax, so the following formula:</p>
<p><span class="katex--display"><span class="katex-display"><span class="katex"><span class="katex-mathml"><math><semantics><mrow><munderover><mo>∑</mo><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></munderover><msup><mi>i</mi><mn>3</mn></msup><mo>=</mo><msup><mrow><mo fence="true">(</mo><mfrac><mrow><mi>n</mi><mo>(</mo><mi>n</mi><mo>+</mo><mn>1</mn><mo>)</mo></mrow><mrow><mn>2</mn></mrow></mfrac><mo fence="true">)</mo></mrow><mn>2</mn></msup></mrow><annotation encoding="application/x-tex">
\sum_{i=1}^{n} i^3=\left(\frac{n(n+1)}{2}\right)^2
</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height: 1.65401em;"></span><span class="strut bottom" style="height: 2.93168em; vertical-align: -1.27767em;"></span><span class="base"><span class="mop op-limits"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 1.6514em;"><span class="" style="top: -1.87233em; margin-left: 0em;"><span class="pstrut" style="height: 3.05em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathit mtight">i</span><span class="mrel mtight">=</span><span class="mord mathrm mtight">1</span></span></span></span><span class="" style="top: -3.05001em;"><span class="pstrut" style="height: 3.05em;"></span><span class=""><span class="mop op-symbol large-op">∑</span></span></span><span class="" style="top: -4.30001em; margin-left: 0em;"><span class="pstrut" style="height: 3.05em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mathit mtight">n</span></span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 1.27767em;"></span></span></span></span><span class="mord"><span class="mord mathit">i</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height: 0.864108em;"><span class="" style="top: -3.113em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathrm mtight">3</span></span></span></span></span></span></span></span><span class="mrel">=</span><span class="minner"><span class="minner"><span class="mopen delimcenter" style="top: 0em;"><span class="delimsizing size3">(</span></span><span class="mord"><span class="mopen nulldelimiter"></span><span class="mfrac"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height: 1.427em;"><span class="" style="top: -2.314em;"><span class="pstrut" style="height: 3em;"></span><span class="mord"><span class="mord mathrm">2</span></span></span><span class="" style="top: -3.23em;"><span class="pstrut" style="height: 3em;"></span><span class="frac-line hide-tail" style="height: 0.04em;"><svg width="400em" height="400em" viewBox="0 0 400000 400000" preserveAspectRatio="xMinYMin slice"><path d="M0 0 h400000 v400000 h-400000z M0 0 h400000 v400000 h-400000z"></path></svg></span></span><span class="" style="top: -3.677em;"><span class="pstrut" style="height: 3em;"></span><span class="mord"><span class="mord mathit">n</span><span class="mopen">(</span><span class="mord mathit">n</span><span class="mbin">+</span><span class="mord mathrm">1</span><span class="mclose">)</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height: 0.686em;"></span></span></span></span><span class="mclose nulldelimiter"></span></span><span class="mclose delimcenter" style="top: 0em;"><span class="delimsizing size3">)</span></span></span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height: 1.65401em;"><span class="" style="top: -3.9029em; margin-right: 0.05em;"><span class="pstrut" style="height: 2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mathrm mtight">2</span></span></span></span></span></span></span></span></span></span></span></span></span></p>
<p>is expressed as:</p>
<pre><code>$$
\sum_{i=1}^{n} i^3=\left(\frac{n(n+1)}{2}\right)^2
$$
</code></pre>
<h5 id="asciimath-syntax">AsciiMath Syntax</h5>
<p>The above formula is expressed in AsciiMath (using <code>@</code> as delimiters) as:</p>
<pre><code>@sum_(i=1)^n i^3=((n(n+1))/2)^2@
</code></pre>
<p>which Smartdown now renders as:</p>
<p>@sum_(i=1)^n i<sup>3=((n(n+1))/2)</sup>2@</p>
<p>Note that AsciiMath via MathJax does not support <em>display-mode</em> equations, but centering can be achieved via Markdown table syntax:</p>

<table>
<thead>
<tr>
<th align="center"></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">@sum_(i=1)^n i<sup>3=((n(n+1))/2)</sup>2@</td>
</tr>
</tbody>
</table><h5 id="more-asciimath-examples">More AsciiMath Examples</h5>

<table>
<thead>
<tr>
<th align="center">AsciiMath</th>
<th align="center">Rendered</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><code>@[[a,b],[c,d]]@</code></td>
<td align="center">@[[a,b],[c,d]]@</td>
</tr>
<tr>
<td align="center"><code>@sqrt sqrt root3x@</code></td>
<td align="center">@sqrt sqrt root3x@</td>
</tr>
<tr>
<td align="center"><code>@int_0^1 f(x)dx@</code></td>
<td align="center">@int_0^1 f(x)dx@</td>
</tr>
<tr>
<td align="center"><code>@hat(ab) bar(xy) ulA vec v dotx ddot y@</code></td>
<td align="center">@hat(ab) bar(xy) ulA vec v dotx ddot y@</td>
</tr>
</tbody>
</table><hr>
<h4 id="chemistry-via-mhchem">Chemistry via <code>mhchem</code></h4>
<p><span class="katex--display">KaTeX parse error: Expected 'EOF', got '\ce' at position 2: 
\̲c̲e̲{Zn^2+
  &lt;=&gt;[+ …</span></p>
<hr>
<p><a href=":@Home">Back to Home</a></p>

