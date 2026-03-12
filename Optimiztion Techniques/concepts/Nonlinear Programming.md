## Nonlinear Programming (NLP)

> Used when the **objective function OR constraints are nonlinear**

---

### Definition

Nonlinear Programming occurs when the optimization problem contains **nonlinear equations**.

Examples of nonlinear expressions:

```
x₁²
sin(x)
log(x)
x₁ · x₂
```

These make the optimization problem **more complex than Linear Programming**.

---

### Example

Minimize

```
x₁² + x₂²
```

Subject to

```
x₁ + x₂ = 1
x₁ ≥ 0
x₂ ≥ 0
```

---

### Why This Problem is Nonlinear

The objective function contains:

```
x₁²
x₂²
```

Squared variables make the function **nonlinear**.

---

### Applications

Nonlinear Programming is used in many real systems:

- Machine Learning training
- Robotics motion planning
- Chemical process optimization
- Power system optimization
- Neural network training

---

### Main Difficulty

> [!warning]
> Nonlinear problems may have **many local optimums**

This means an algorithm may stop at a **local solution** instead of the **best global solution**.

---

### Visualization

<div style="background:#1e1e1e;padding:20px;border-radius:10px;text-align:center;">
<img src="nlp-local-global.png" width="450">
</div>

Interpretation:

- **Local minimum** → best solution in a small region
- **Global minimum** → best solution overall
- **Local maximum** → peak in a limited region
- Multiple local optimums can exist

---

### Comparison with Linear Programming

| Feature | Linear Programming | Nonlinear Programming |
|------|------|------|
| Function | Linear | Nonlinear |
| Difficulty | Easier | Harder |
| Solutions | One global optimum | Multiple local optimums |
| Algorithms | Simplex | Gradient-based methods |

---

### Important Idea

```
Linear Programming → always one global optimum
Nonlinear Programming → may have many local optimums
```

That is why NLP problems are **harder to solve**.

---

### Relation to Previous Topic

Optimization problems are classified into:

```
Optimization
│
├── Linear Programming
├── Nonlinear Programming
└── Integer Programming
```

Nonlinear Programming extends LP when **real-world systems are not linear**.

---