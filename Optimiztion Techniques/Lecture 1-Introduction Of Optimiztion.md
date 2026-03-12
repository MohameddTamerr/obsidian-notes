## What is Optimization

Optimization = finding the **best solution** among all possible solutions.

Example daily decisions:

- fastest route to university
    
- cheapest ride
    
- best schedule for study
    

---

## Key Components of Optimization

### 1️⃣ Decision Variables

Things we can control.

Example

x = number of lemonade cups

---

### 2️⃣ Objective Function

What we want to **maximize or minimize**

Examples

- maximize profit
    
- minimize cost
    
- minimize time
    

General form

max / min  f(x1, x2, ... , xn)

---

### 3️⃣ Constraints

Limitations of the problem.

Examples

- limited resources
    
- time limits
    
- capacity
    

General form

g1(x1,...xn) ≤ b1  
g2(x1,...xn) ≤ b2

---

# Example – Lemonade Problem

Decision variable

x = number of lemonade cups

Selling price = 5  
Cost = 2

Profit per cup

5x − 2x = 3x

Objective

max Z = 3x

Constraints

0.1x ≤ 10     (sugar)  
0.5x ≤ 50     (lemons)  
0.02x ≤ 2     (time)  
x ≥ 0

---

# Types of Optimization Problems

Optimization  
│  
├── Linear  
├── Nonlinear  
└── Integer

---

# Linear Programming (LP)

Conditions

- objective function **linear**
    
- constraints **linear**
    
- variables **continuous**
    

Example

max 3x1 + 5x2  
  
s.t  
x1 + 2x2 ≤ 10  
2x1 + x2 ≤ 12  
x1 , x2 ≥ 0

Applications

- production planning
    
- resource allocation
    
- portfolio management
    
- diet problems
    

---

# Nonlinear Programming (NLP)

Used when

objective OR constraints are nonlinear

Example

min x1² + x2²  
  
s.t  
x1 + x2 = 1  
x1 , x2 ≥ 0

Applications

- machine learning
    
- robotics
    
- chemical processes
    

Problem

finding global optimum is difficult

---

# Integer Programming (IP)

Decision variables must be **integers**

Example

xi = 1   project selected  
xi = 0   project not selected

Applications

- job scheduling
    
- facility location
    
- network design
    

---

# Continuous vs Discrete Variables

### Continuous

Any real value

Examples

- production volume
    
- temperature
    
- investment
    

Example

2.5 liters

---

### Discrete

Integer values only

Examples

- number of workers
    
- number of flights
    
- yes / no decisions
    

Example

3 workers

(not 2.5 workers)

---

# Steps to Formulate an Optimization Problem

1️⃣ Identify decision variables

2️⃣ Define objective function

3️⃣ Write constraints

4️⃣ Check mathematical correctness

Important idea

Hardest part = formulating the problem

---

# Common Modeling Mistakes

- forgetting **x ≥ 0**
    
- inconsistent units (kg vs pounds)
    
- missing constraints
    
- making the model too complex
    

Rule

Model should be simple but realistic

---

# Real Applications

### Google Search

Goal

maximize user satisfaction

Constraint

response time < 0.5 sec

---

### Amazon Delivery

Objective

minimize distance

Constraints

- truck capacity
    
- delivery time
    
- traffic
    

Problem name

Vehicle Routing Problem (VRP)

---

### Netflix Recommendations

Goal

maximize viewing time

Constraints

- user preferences
    
- available content
    

---

# Optimization in AI

Training a neural network = optimization problem

Example

min L(θ)

Where

θ = parameters  
L = loss function

Common method

Gradient Descent

---

# Key Ideas

Optimization problems always include

Decision variables  
Objective function  
Constraints

# Optimization

Types:
- [[Linear Programming]]
- [[Nonlinear Programming]]
- [[Integer Programming]]
	