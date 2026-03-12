## Integer Programming (IP)

> Optimization problems where **decision variables must take integer values**.

---

### Key Idea

In Integer Programming, variables **cannot take fractional values**.

Example:

```
x = 3   ✔ valid
x = 2.5 ✘ not allowed
```

This is useful when the decision represents **countable objects**.

---

### Binary Decision Example

```
xᵢ = 1   → project i is selected
xᵢ = 0   → project i is NOT selected
```

These are called **binary variables**.

---

### Mathematical Example

Maximize

```
Z = Σ (pᵢ xᵢ)
```

Subject to

```
Σ (cᵢ xᵢ) ≤ B
xᵢ ∈ {0,1}
```

Where:

- `pᵢ` = profit of project *i*
- `cᵢ` = cost of project *i*
- `B` = budget limit

---

### Applications

Integer Programming is used when decisions involve **discrete choices**.

Examples:

- **Job scheduling** → assign tasks to workers
- **Facility location** → decide where to build warehouses
- **Network design** → determine which links to include
- **Airline scheduling** → assign planes to routes
- **Project selection** → choose projects within a budget

---

### Why It Is Harder

> [!warning]
> Integer Programming is usually **much harder to solve than Linear Programming**.

Because the solver must **search through combinations of integer values** instead of continuous values.

---

### Quick Comparison

| Type | Variable Type | Difficulty |
|-----|-----|-----|
| LP | Continuous | Easy |
| NLP | Continuous (nonlinear) | Medium |
| IP | Integer / Binary | Hard |