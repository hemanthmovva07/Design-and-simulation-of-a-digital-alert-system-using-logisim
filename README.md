# Design-and-simulation-of-a-digital-alert-system-using-logisim
A Digital Alert System detects an unsafe condition and turns ON an alert when the required conditions are satisfied.

Inputs
D = Door status
M = Motion detected
F = Fire detected
S = Security system ON
Output
A = Alert
Logic

The alert should turn ON when:

Fire is detected OR (Security is ON AND Door is open) OR (Security is ON AND Motion is detected).

Boolean expression:

$$ A = F + SD + SM $$
Components in Logisim
4 Input pins: D, M, F, S
2 AND gates
1 OR gate
1 Output LED
Wires
Simple block diagram
Door (D) ─────┐
              AND ─────┐
Security (S) ─┘        │
                       │
Motion (M) ─────┐      │
                AND ───┤
Security (S) ───┘      │
                       OR ───► ALERT
Fire (F) ──────────────┘
Example
Fire	Security	Door	Motion	Alert
0	0	0	0	0
0	1	1	0	1
0	1	0	1	1
1	0	0	0	1
1	1	1	1	1

I can also give you the 
complete 9-slide PPT content, 
Logisim circuit steps, 
truth table, 
Boolean expression, 
objectives, 
methodology, 
results, and 
conclusion for this project.
