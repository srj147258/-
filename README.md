# -
1 template  2  constexpr size t  OnesCount = (Input % 2)OnesCount&lt;(Input | 2)>;了  4 template &lt;> constexprsize_ _t OnesCount&lt;0> = 0;5  6  constexpr size t res =OnesCount&lt;45>; 
