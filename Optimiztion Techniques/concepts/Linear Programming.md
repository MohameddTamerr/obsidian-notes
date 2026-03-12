## Linear Programming (LP)

> A type of optimization where the **objective function and constraints are linear**.

---

### Conditions

An optimization problem is **Linear Programming** when:

- objective function **linear**
- constraints **linear**
- decision variables **continuous**

---

### Mathematical Example

Maximize

```
Z = 3x₁ + 5x₂
```

Subject to

```
x₁ + 2x₂ ≤ 10
2x₁ + x₂ ≤ 12
x₁ ≥ 0
x₂ ≥ 0
```

---

### Interpretation

- `x₁` and `x₂` are **decision variables**
- the function `Z` represents the **objective (profit, cost, etc.)**
- the inequalities represent **resource limitations**

The solution will always occur at a **corner point of the feasible region**.

---

### Applications

Linear Programming is widely used in real-world decision making:

- **Production planning** → maximize factory profit
- **Resource allocation** → distribute limited resources
- **Portfolio management** → optimize investments
- **Diet problems** → minimize food cost while meeting nutrition needs
- **Transportation planning** → minimize shipping cost

---

### Key Property

> [!tip]
> Linear Programming problems have **one global optimal solution**.

This makes LP **much easier to solve than nonlinear optimization problems**.