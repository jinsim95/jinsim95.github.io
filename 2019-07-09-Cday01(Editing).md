---
title: '[C] Day 1'
author: Jin Sim

---

<h2 id="basic-outline-of-c-language">Basic Outline of C Language</h2>
<ol>
<li>Print Statement</li>
<li>Variable</li>
<li>Operator</li>
<li>Boolean</li>
<li>Loop</li>
<li>Array</li>
</ol>
<h2 id="assumptions">Assumptions</h2>
<ul>
<li>
<p>Use of Microsoft Visual C ++</p>
</li>
<li>
<p>format of each file:</p>
<pre><code>  #include &lt;Windows.h&gt;
  #include &lt;stdio.h&gt;

  void main() {
  
  	system("pause")	#in order to view the printed line
  }
</code></pre>
</li>
</ul>
<h2 id="print-statement">Print Statement</h2>
<h4 id="example-">Example )</h4>
<pre><code>	#include &lt;Windows.h&gt;
	#include &lt;stdio.h&gt;

    void main(){
        // 1. integer : decimal
        printf("%d", 10);    printf("\n");
        // 2. floating numbers : float
        printf("%f", 3.14);    printf("\n");
        // 3: single letter : character
        printf("%c", 'B');    printf("\n");
        // 4. multiple letters : String
        printf("hello, c\n");

        system("pause");
    }
</code></pre>
<h2 id="operators">Operators</h2>
<h4 id="types-">Types )</h4>
<ul>
<li>Addition	: 	<strong>+</strong></li>
<li>Subtraction	:	<strong>-</strong></li>
<li>Multiplication	:	<strong>*</strong></li>
<li>Division	:	<strong>/</strong></li>
<li>Remainder	:	<strong>%</strong></li>
</ul>
<h4 id="practice-problem-">Practice Problem )</h4>
<p>화폐매수출력</p>

