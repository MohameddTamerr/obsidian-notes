

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

Optimization types:

- [[Linear Programming]]
- [[Nonlinear Programming]]
- [[Integer Programming]]

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