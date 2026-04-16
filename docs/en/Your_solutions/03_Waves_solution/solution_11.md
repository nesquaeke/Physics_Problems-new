✅ 11. Two-Slit Interference (Mathematical Solution)
📌 Physical Idea

Two slits act as two wave sources.
Each slit produces a wave that spreads in space.

The final wave is the sum of both waves.

📌 1. Wave from each slit

Each slit produces a spherical wave:

𝑢
1
(
𝑟
,
𝑡
)
=
𝐴
𝑟
1
sin
⁡
(
𝑘
𝑟
1
−
𝜔
𝑡
)
u
1
	​

(r,t)=
r
1
	​

A
	​

sin(kr
1
	​

−ωt)
𝑢
2
(
𝑟
,
𝑡
)
=
𝐴
𝑟
2
sin
⁡
(
𝑘
𝑟
2
−
𝜔
𝑡
)
u
2
	​

(r,t)=
r
2
	​

A
	​

sin(kr
2
	​

−ωt)

Where:

𝑟
1
r
1
	​

 = distance from slit 1
𝑟
2
r
2
	​

 = distance from slit 2
𝑘
=
2
𝜋
𝜆
k=
λ
2π
	​

📌 2. Total wave (Superposition)

The total wave is:

𝑢
(
𝑟
,
𝑡
)
=
𝑢
1
+
𝑢
2
u(r,t)=u
1
	​

+u
2
	​


So:

𝑢
(
𝑟
,
𝑡
)
=
𝐴
𝑟
1
sin
⁡
(
𝑘
𝑟
1
−
𝜔
𝑡
)
+
𝐴
𝑟
2
sin
⁡
(
𝑘
𝑟
2
−
𝜔
𝑡
)
u(r,t)=
r
1
	​

A
	​

sin(kr
1
	​

−ωt)+
r
2
	​

A
	​

sin(kr
2
	​

−ωt)
📌 3. Interference idea

The pattern comes from phase difference:

Δ
𝑟
=
𝑟
2
−
𝑟
1
Δr=r
2
	​

−r
1
	​

🟢 Constructive Interference (Bright area)

When waves are in phase:

Δ
𝑟
=
𝑛
𝜆
Δr=nλ

👉 Waves add together → bright line appears

🔴 Destructive Interference (Dark area)

When waves are out of phase:

Δ
𝑟
=
(
𝑛
+
1
2
)
𝜆
Δr=(n+
2
1
	​

)λ

👉 Waves cancel → dark line appears

📌 4. What the simulation does (numerical idea)

For each pixel on the screen:

Compute distance 
𝑟
1
r
1
	​

 and 
𝑟
2
r
2
	​

Compute wave1 and wave2
Add them:
𝑢
=
𝑢
1
+
𝑢
2
u=u
1
	​

+u
2
	​

Convert result into brightness (color)
📌 5. Effect of parameters
If d increases → more interference stripes
If λ increases → wider spacing between stripes
If λ decreases → tighter pattern
📌 6. Summary
Two slits → two waves
Waves combine using superposition
Phase difference creates interference
Bright and dark patterns appear on screen
🎯 Final one-line idea

The interference pattern is created by adding two wave functions and observing how their phase difference changes the intensity.



Concept: Thomas Young's famous double-slit experiment. Two points create waves simultaneously. When the peaks of the waves meet, they create bright bands (constructive interference). When a peak meets a valley, they cancel out, creating dark bands (destructive interference).
