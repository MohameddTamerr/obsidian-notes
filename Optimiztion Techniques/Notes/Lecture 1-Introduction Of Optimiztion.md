

## What is Optimization

> Optimization = finding the **best solution among all possible solutions**

### Simple daily examples
- fastest route to university
- cheapest ride
- best study schedule

---

## Key Components of Optimization

### 1️⃣ Decision Variables
Things we can **control or decide**.

Example

`x = number of lemonade cups`

---

### 2️⃣ Objective Function

What we want to **maximize or minimize**

Examples
- maximize profit
- minimize cost
- minimize time

General form

```
max / min   f(x1 , x2 , ... , xn)
```

---

### 3️⃣ Constraints

Limitations or restrictions.

Examples
- limited resources
- time limits
- production capacity

General form

```
g1(x1,...xn) ≤ b1
g2(x1,...xn) ≤ b2
```

---

# Example — Lemonade Problem

### Decision Variable

```
x = number of lemonade cups
```

Selling price = 5  
Cost per cup = 2

### Profit

```
Profit = 5x − 2x
Profit = 3x
```

### Objective Function

```
max Z = 3x
```

### Constraints

```
0.1x ≤ 10     (sugar)
0.5x ≤ 50     (lemons)
0.02x ≤ 2     (time)
x ≥ 0
```

---

# Types of Optimization Problems

Optimization problems are commonly classified into three main types.

---

## Linear Programming (LP)

> [[Linear Programming]]

A **Linear Programming problem** is an optimization problem where:

- the **objective function is linear**
- the **constraints are linear**
- the **decision variables are continuous**

Example

```
max 3x₁ + 5x₂
```

subject to

```
x₁ + 2x₂ ≤ 10
2x₁ + x₂ ≤ 12
x₁ , x₂ ≥ 0
```

LP problems are usually **easier to solve** and always have a **global optimal solution**.

Applications

- production planning
- resource allocation
- portfolio optimization
- diet problems

➡️ For a detailed explanation see: [[Linear Programming]]

---

## Nonlinear Programming (NLP)

> [[Nonlinear Programming]]

A **Nonlinear Programming problem** occurs when the **objective function or constraints are nonlinear**.

Example

```
min x₁² + x₂²
```

subject to

```
x₁ + x₂ = 1
x₁ , x₂ ≥ 0
```

NLP problems are **more complex** because they may contain **multiple local optimum solutions**.

Applications

- machine learning
- robotics
- chemical process optimization

➡️ For a deeper explanation see: [[Nonlinear Programming]]

---

## Integer Programming (IP)

> [[Integer Programming]]

In **Integer Programming**, the decision variables must take **integer values**.

Example

```
xᵢ = 1   project selected
xᵢ = 0   project not selected
```

These are called **binary decision variables**.

Applications

- job scheduling
- facility location
- network design
- project selection

Integer programming problems are **harder to solve** because solutions must be integers.

➡️ For full details see: [[Integer Programming]]

---

## Comparison

| Type | Function | Variables | Difficulty |
|-----|-----|-----|-----|
| LP | Linear | Continuous | Easy |
| NLP | Nonlinear | Continuous | Medium |
| IP | Linear / Nonlinear | Integer | Hard |

---

## Relationship Between Them

```
Optimization
│
├── Linear Programming
├── Nonlinear Programming
└── Integer Programming
```

All three are **different ways of modeling optimization problems** depending on the structure of the system.

---

# Comparison of LP, NLP, and IP

| Aspect | LP | NLP | IP |
|------|------|------|------|
| Linearity | Linear | Nonlinear | Linear / Nonlinear |
| Variables | Continuous | Continuous | Integer |
| Difficulty | Easy | Medium | Hard |
| Solve Time | Fast | Medium | Can be slow |
| Global Optimum | Guaranteed | Maybe not | Guaranteed* |

---

# Continuous vs Discrete Variables

| Type | Meaning | Example |
|-----|-----|-----|
| Continuous | any real value | 2.5 liters |
| Discrete | integers only | 3 workers |

### Continuous examples
- production volume
- temperature
- investment

### Discrete examples
- number of workers
- number of flights
- yes/no decisions

---

# Steps to Formulate an Optimization Problem

1. Identify **decision variables**
2. Define **objective function**
3. Write **constraints**
4. Check **mathematical correctness**

> [!important]
> Hardest part = **formulating the problem correctly**

---

# Common Modeling Mistakes

| Mistake | Example |
|------|------|
| Forgetting non-negativity | x ≥ 0 |
| Inconsistent units | kg vs pounds |
| Missing constraints | unrealistic solution |
| Overcomplicated model | hard to solve |

> [!tip]
> A good model should be **simple but realistic**

---

# Real Applications

## Google Search

Goal

```
maximize user satisfaction
```

Constraint

```
response time < 0.5 seconds
```

---

## Amazon Delivery

Objective

```
minimize travel distance
```

Constraints
- truck capacity
- delivery time
- traffic

Problem name

```
Vehicle Routing Problem (VRP)
```

---

## Netflix Recommendations

Goal

```
maximize viewing time
```

Constraints
- user preferences
- available content

---

# Optimization in AI

Training a neural network is an **optimization problem**.

Example

```
min L(θ)
```

Where

```
θ = model parameters
L = loss function
```

Common algorithm

```
Gradient Descent
```

---

# Key Ideas

Optimization problems always include:

- Decision Variables
- Objective Function
- Constraints

Main types:

- Linear Programming (LP)
- Nonlinear Programming (NLP)
- Integer Programming (IP)

---

# Concept Map

```
Optimization
│
├── Decision Variables
├── Objective Function
└── Constraints
```

---

# Optimization Types Map

```
Optimization
│
├── Linear Programming
├── Nonlinear Programming
└── Integer Programming
```