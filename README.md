# 🧮 Parametric Curve Fitting — Assignment Submission

## 📘 Problem Statement
Find the values of the unknown parameters \( \theta, M, X \) in the given parametric equation of a curve:
x(t) &= t\cos(\theta) - e^{M|t|}\sin(0.3t)\sin(\theta) + X
y(t) &= 42 + t\sin(\theta) + e^{M|t|}\sin(0.3t)\cos(\theta)




## ⚙️ Method Summary
- Generated \( t \) uniformly in [6, 60].
- Used Differential Evolution (global) + Nelder–Mead (local) optimization.
- Objective: minimize L1 distance between observed and predicted points.
- Alignment: points sorted by angular position around centroid.

## 🧠 Final Results
theta=30.051099 degrees
M=0.02895995
X=55.085117

**Fit metrics:**
- Total L1 Distance ≈ 5517.08  
- Mean L1 per point ≈ 3.68  
- RMSE ≈ 5.17

---

## 🧾 Final Equations (LaTeX Submission)
```tex
\begin{aligned}
x(t)&=t\cos(30.051099^\circ) - e^{0.02895995|t|}\sin(0.3t)\sin(30.051099^\circ) + 55.085117\\[4pt]
y(t)&=42 + t\sin(30.051099^\circ) + e^{0.02895995|t|}\sin(0.3t)\cos(30.051099^\circ)
\end{aligned}
## Desmos Visualization
( t*cos(0.5249) - e^(0.02895995*abs(t))*sin(0.3*t)*sin(0.5249) + 55.085117,
  42 + t*sin(0.5249) + e^(0.02895995*abs(t))*sin(0.3*t)*cos(0.5249) )

​

