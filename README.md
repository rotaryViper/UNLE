# 2D distance collisions

Test: Wriggling 1 node around with 400 nodes\
Enable advanced paint instrumentation (slow): True\

From 2-14 seconds\
\
11692 ms  Scripting\
54 ms  Rendering\
69 ms  Painting\
153 ms  System\
12 ms  Idle\
11982 ms  Total\
\
In a single timer fire:\
applyCollisions: 5.66ms\
applyCollisions: 2.66ms\
applyCollisions: 6.25ms\
\
3 calls of apply collisions\
