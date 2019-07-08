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
<h4 id="example-">[ Example ]</h4>
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
<h3 id="types-of-operators-">[ Types of Operators ]</h3>
<ul>
<li>Addition	: 	<strong>+</strong></li>
<li>Subtraction	:	<strong>-</strong></li>
<li>Multiplication	:	<strong>*</strong></li>
<li>Division	:	<strong>/</strong></li>
<li>Remainder	:	<strong>%</strong></li>
</ul>
<h3 id="practice-problem-">[ Practice Problem ]</h3>
<p><strong>Money Sorting Problem :</strong></p>
<p>You are withdrawing $156.35 of cash from a bank.<br>
If the bank gives out to you the least number of bills/coins, how many of each bill/coin do you get?</p>
<pre><code>#include &lt;Windows.h&gt;
#include &lt;stdio.h&gt;

void main() {
	int cash;
	printf("금액을 입력하세요 : "); // 38000
	scanf("%d", &amp;cash);
	int fifty_thousand = cash / 50000;
	int ten_thousand = cash / 10000;
	int five_thousand = (cash % 10000) / 5000;
	int one_thousand = (cash % 5000) / 1000;
	int five_hundred = (cash % 1000) / 500;
	int one_hundred = (cash % 500) / 100;
	
	printf("오만원짜리 %d장\n", fifty_thousand);
	printf("만원짜리 %d장\n", ten_thousand);
	printf("오천원짜리 %d장\n", five_thousand);
	printf("천원짜리 %d장\n", one_thousand);
	printf("오백원짜리 %d장\n", five_hundred);
	printf("백원짜리 %d장\n", one_hundred);	
}
</code></pre>

