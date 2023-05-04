Download Link: https://assignmentchef.com/product/solved-cs70-homework1
<br>
Before you start your homework, state briefly how you worked on it. Who else did you work with? List names and email addresses. (In case of homework party, you can just describe the group.)

Classify the following statements as being one of the following, where <em>x </em>and <em>y </em>are arbitrary propositions, and justify your answers (e.g., using a truth table)

<ul>

 <li>True for all combinations of <em>x </em>and <em>y </em>(Tautology)</li>

 <li>False for all combinations of <em>x </em>and <em>y </em>(Contradiction)</li>

 <li>Neither</li>

 <li><em>x</em>∧(<em>x </em>=⇒ <em>y</em>)∧(¬<em>y</em>)</li>

 <li><em>x </em>=⇒ (<em>x</em>∨<em>y</em>)</li>

 <li>(<em>x</em>∨<em>y</em>)∨(<em>x</em>∨¬<em>y</em>)</li>

 <li>(<em>x </em>=⇒ <em>y</em>)∨(<em>x </em>=⇒ ¬<em>y</em>)</li>

 <li>(<em>x</em>∨<em>y</em>)∧(¬(<em>x</em>∧<em>y</em>))</li>

 <li>(<em>x </em>=⇒ <em>y</em>)∧(¬<em>x </em>=⇒ <em>y</em>)∧(¬<em>y</em>)</li>

</ul>

<h1>2      Miscellaneous Logic</h1>

<ul>

 <li>Let the statement, (∀<em>x </em>∈ R)(∃<em>y </em>∈ R) <em>G</em>(<em>x</em><em>,y</em>), be true for predicate <em>G</em>(<em>x</em><em>,y</em>).</li>

</ul>

For each of the following statements, decide if the statement is certainly true, certainly false, or possibly true, and justify your solution. (If possibly true, provide a specific example where the statement is false and a specific example where the statement is true.)

<ul>

 <li><em>G</em>(3<em>,</em>4)</li>

 <li>(∀<em>x </em>∈ R) <em>G</em>(<em>x</em><em>,</em>3)</li>

 <li>∃<em>y G</em>(3<em>,y</em>)</li>

 <li>∀<em>y </em>¬<em>G</em>(3<em>,y</em>)</li>

 <li>∃<em>x G</em>(<em>x</em><em>,</em>4)</li>

</ul>

<ul>

 <li>Give an expression using terms involving ∨<em>,</em>∧ and ¬ which is true if and only if exactly one of <em>X</em><em>,Y</em>, and <em>Z </em>is true.</li>

</ul>

<h1>3       Propositional Practice</h1>

Convert the following English sentences into propositional logic and the following propositions into English. State whether or not each statement is true with brief justification.

<ul>

 <li>There is a real number which is not rational.</li>

 <li>All integers are natural numbers or are negative, but not both.</li>

 <li>If a natural number is divisible by 6, it is divisible by 2 or it is divisible by 3.</li>

 <li>(∀<em>x </em>∈ R)(<em>x </em>∈ C)</li>

 <li>(∀<em>x </em>∈ Z)(((2 | <em>x</em>)∨(3 | <em>x</em>)) =⇒ (6 | <em>x</em>)) (f) (∀<em>x </em>∈ N)((<em>x </em><em>&gt; </em>7) =⇒ ((∃<em>a</em><em>,b </em>∈ N)(<em>a</em>+<em>b </em>= <em>x</em>)))</li>

</ul>

4      Proof by?

<ul>

 <li>Prove that if for any two integers <em>x </em>and <em>y</em>, if 10 does not divide <em>xy</em>, then 10 does not divide <em>x </em>and 10 does not divide <em>y</em>. In notation: (∀<em>x</em><em>,y </em>∈ Z) (10 – <em>xy</em>) =⇒ ((10 – <em>x</em>) ∧ (10 – <em>y</em>)). What proof technique did you use?</li>

 <li>Prove or disprove the contrapositive.</li>

 <li>Prove or disprove the converse.</li>

</ul>

<h1>5       Prove or Disprove</h1>

<ul>

 <li>(∀<em>n </em>∈ N) if <em>n </em>is odd then <em>n</em><sup>2 </sup>+2<em>n </em>is odd.</li>

 <li>(∀<em>x</em><em>,y </em>∈ R) min(<em>x</em><em>,y</em>)=(<em>x</em>+<em>y</em>−|<em>x</em>−<em>y</em>|)<em>/</em></li>

 <li>(∀<em>a</em><em>,b </em>∈ R) if <em>a</em>+<em>b </em>≤ 10 then <em>a </em>≤ 7 or <em>b </em>≤</li>

 <li>(∀<em>r </em>∈ R) if <em>r </em>is irrational then <em>r</em>+1 is irrational.</li>

 <li>(∀<em>n </em>∈ Z<sup>+</sup>) 10<em>n</em><sup>2 </sup><em>&gt; n</em>!.</li>

</ul>

<h1>6       Preserving Set Operations</h1>

For a function <em>f</em>, define the image of a set <em>X </em>to be the set <em>f</em>(<em>X</em>)= {<em>y </em>| <em>y </em>= <em>f</em>(<em>x</em>) for some <em>x </em>∈ <em>X</em>}. Define the inverse image or preimage of a set <em>Y </em>to be the set <em>f</em><sup>−1</sup>(<em>Y</em>)= {<em>x </em>| <em>f</em>(<em>x</em>) ∈ <em>Y</em>}. Prove the following statements, in which <em>A </em>and <em>B </em>are sets. By doing so, you will show that inverse images preserve set operations, but images typically do not.

<em>Hint: For sets X and Y, X </em>=<em>Y if and only if X </em>⊆<em>Y and Y </em>⊆ <em>X. To prove that X </em>⊆<em>Y, it is sufficient to show that </em>(∀<em>x</em>)((<em>x </em>∈ <em>X</em>) =⇒ (<em>x </em>∈<em>Y</em>))<em>.</em>

(a) <em>f</em><sup>−1</sup>(<em>A</em>∪<em>B</em>)= <em>f</em><sup>−1</sup>(<em>A</em>)∪ <em>f</em><sup>−1</sup>(<em>B</em>). (b) <em>f</em><sup>−1</sup>(<em>A</em>∩<em>B</em>)= <em>f</em><sup>−1</sup>(<em>A</em>)∩ <em>f</em><sup>−1</sup>(<em>B</em>).

<ul>

 <li><em>f</em><sup>−1</sup>(<em>A</em><em>B</em>)= <em>f</em><sup>−1</sup>(<em>A</em>) <em>f</em><sup>−1</sup>(<em>B</em>).</li>

 <li><em>f</em>(<em>A</em>∪<em>B</em>)= <em>f</em>(<em>A</em>)∪ <em>f</em>(<em>B</em>).</li>

 <li><em>f</em>(<em>A</em>∩<em>B</em>) ⊆ <em>f</em>(<em>A</em>)∩ <em>f</em>(<em>B</em>), and give an example where equality does not hold.</li>

 <li><em>f</em>(<em>A</em><em>B</em>) ⊇ <em>f</em>(<em>A</em>) <em>f</em>(<em>B</em>), and give an example where equality does not hold.</li>

</ul>