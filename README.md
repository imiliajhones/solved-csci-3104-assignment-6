Download Link: https://assignmentchef.com/product/solved-csci-3104-assignment-6
<br>
<ol>

 <li>Gru has decided to give you yet another task. He gives you a system of inequalities with variables <em>x</em><sub>1</sub><em>,x</em><sub>2</sub><em>,…,x<sub>n</sub></em>, where each inequality is of the form <em>x<sub>i</sub></em><sub>1 </sub><em>&lt; x<sub>i</sub></em><sub>2 </sub>for <em>i</em><sub>1</sub><em>,i</em><sub>2 </sub>∈ {1<em>,…,n</em>}. He proceeds to give you an example of such a system of inequalities: <em>n </em>= 5 and <em>x</em><sub>1 </sub><em>&lt; x</em><sub>3</sub>, <em>x</em><sub>1 </sub><em>&lt; x</em><sub>4</sub>, <em>x</em><sub>2 </sub><em>&lt; x</em><sub>5</sub>, <em>x</em><sub>5 </sub><em>&lt; x</em><sub>4</sub>.</li>

</ol>

Your task, he explains, is to write down an algorithm (high level description is sufficient) which does two things: (1) it should check whether a solution to a given system of inequalities exists, and (2) if a solution exists, it should find the solution. (<strong>Gru’s hint: </strong>Convert the system of inequalities into a graph).

<ol start="2">

 <li>Gru argues that he could simplify our algorithm for finding SCCs by using the original graph <em>G </em>(instead of <em>G<sup>T</sup></em>) in the second call to DFS, and considering the vertices in <em>increasing </em>order of finish times. Will Gru’s idea produce the correct result? If yes, provide justification of why it works; if not, provide a counterexample.</li>

 <li>Gru gives you a graph <em>G</em>, a set of edge weights <em>w</em>, and an MST <em>T </em>of <em>G</em>. He would like to know if <em>T </em>is also an MST of <em>G</em><sup>0</sup>, where <em>G</em><sup>0 </sup>is formed by decreasing the weight of exactly one of the edges in <em>T</em>. In other words, denote the edge chosen to be (<em>x,y</em>) ∈ <em>T</em>, <em>k </em>be a positive number representing the decreased edge weight, and a weight function defined as</li>

</ol>

(

<sub>0                                  </sub><em>w</em>(<em>u,v</em>)                if (<em>u,v</em>) 6= (<em>x,y</em>)

<em>w </em>(<em>u,v</em>) = <em>w</em>(<em>x,y</em>) − <em>k </em>if (<em>u,v</em>) = (<em>x,y</em>)

Prove that <em>T </em>is an MST for <em>G</em><sup>0</sup>, whose edge weights are given by <em>w</em><sup>0</sup>.

<ol start="4">

 <li>Your final task this week (assigned, of course, by Gru himself) is to show that a graph <em>G </em>has a unique MST if, for every cut of <em>G</em>, there exists a unique light edge crossing the cut. In addition, Gru asks you to disprove the converse via a counterexample.</li>

</ol>