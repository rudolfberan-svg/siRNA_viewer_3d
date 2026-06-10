An interactive web application that bridges structural biology and computational therapeutics. The app visualizes RNA:RNA duplexes in WebGL 3D space and runs a real-time analytics engine to predict whether a given siRNA/mRNA pair will successfully adopt a functional, canonical A-form helix required for RISC-mediated cleavage. It evaluates structural parameters like Watson-Crick pairing, G·U wobble saturation, purine tract distortions, and helical rise.
Watson-Crick pair fraction, ≥ 75% of pairs must be Watson-Crick (A·U or G·C), Max points = 3.
Duplex length, ≥ 6 nt to pass; Ideal: 16–25 nt, Max points = 2.
All-RNA duplex (U not T), Always passes (U-only input validated on entry), Max points = 2.
No consecutive mismatches, < 2 mismatches in a row, Max points = 2.
GC content (antisense), 30–70% GC, Max points = 2.
G·U wobble content, ≤ 30% of pairs are G·U wobble pairs, Max points = 1.
No long purine runs, < 5 consecutive purines (A or G) on antisense strand, Max points = 1.
Total possible score = 13.
A-form helix is highly likely if score ≥ 82%  (≥ 10.7 / 13 pts).
A-form helix is likely if score 55–81%  (7.2–10.5 / 13 pts).
A-form helix is unlikely if score < 55%  (< 7.2 / 13 pts).
