Download Link: https://assignmentchef.com/product/solved-ee444-544-homework-3
<br>
Consider the unstable plant

<ul>

 <li>Find a characterization of the set of all controllers stabilizing the feedback system (<em>C,P</em>):</li>

</ul>

where <em>N,D,X,Y,</em>∈ <em>H</em>∞ are such that <em>N</em>(<em>s</em>)<em>X</em>(<em>s</em>) + <em>D</em>(<em>s</em>)<em>Y </em>(<em>s</em>) = 1 and <em>P</em>(<em>s</em>) = <em>N</em>(<em>s</em>)<em>/D</em>(<em>s</em>).

<ul>

 <li>Find a controller <em>C</em>(<em>s</em>) stabilizing (<em>C,P</em>), and satisfying the following steady state performance conditions:

  <ul>

   <li>steady state error for a unit step reference input is zero</li>

   <li>steady state error for a sinusoidal input of the form <em>r</em>(<em>t</em>) = sin(3<em>t</em>), <em>t </em>≥ 0, is zero.</li>

  </ul></li>

</ul>

Implement this feedback system in Simulink and illustrate that performance conditions are satisfied.

<strong>Problem 2</strong>. For the nominal plant given in Problem 1 consider the following set of uncertain plants:

P = {<em>P</em><sub>∆ </sub>= <em>P</em>(1 + ∆<em>m</em>) : <em>P</em><sub>∆ </sub><em>has </em>2 <em>poles in </em>C<sub>+ </sub><em>, </em>|∆<em>m</em>(<em>jω</em>)| <em>&lt; </em>|<em>W</em><em>m</em>(<em>jω</em>)| <em>, </em>∀ <em>ω </em>}

where

<em>W</em><em>m</em>(<em>s</em>) = <em>δ </em>(<em>s </em>+ 1)<em>.</em>

<ul>

 <li>Find the largest <em>δ &gt; </em>0 for which there exists a controller <em>C </em>stabilizing (<em>C,P</em><sub>∆</sub>) for all <em>P</em><sub>∆ </sub>∈ P; and determine the corresponding optimal controller, <em>C</em><sub>opt</sub>.</li>

 <li>With the largest <em>δ </em>computed above, pick an arbitrary element <em>P</em><sub>∆ </sub>6= <em>P </em>in the set P, and prove that (<em>C</em><sub>opt</sub><em>,P</em><sub>∆</sub>) is indeed stable (find the location of the closed loop system poles and determine the stability margins of this system i.e. gain, phase, delay and vector margins).</li>

</ul>