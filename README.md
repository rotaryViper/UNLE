# Trigonometry Collisions

Test: Wriggling 1 node around with 400 nodes\
Enable advanced paint instrumentation (slow): True

From 6-18 seconds

6580 ms  Scripting\
101 ms  Rendering\
131 ms  Painting\
297 ms  System\
4923 ms  Idle\
12032 ms  Total

In a single timer fire:\
applyCollisions: 3.69ms\
applyCollisions: 6.77ms

1-2 call of apply collisions

Use strict mode\
Removed division from collision code and replaced var with const or let\
Removed collision detection during dragging
