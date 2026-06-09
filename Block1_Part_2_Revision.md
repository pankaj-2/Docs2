# MBA Revision Notes — Managerial Economics

---

## Chapter: Unit 3 — Basic Concepts & Techniques

> Covers the key quantitative tools used by managers for decision-making: sets, functions, derivatives, optimization, regression, and risk analysis.

---

### 3.2 Opportunity Set

- A **set** = a well-defined collection of objects (e.g., all positive numbers between 1 and 10).
- An **opportunity set** = all feasible actions available to a decision-maker.
- For a consumer with income ₹100, prices ₹5 (X) and ₹4 (Y) → can buy any combo on/inside line AB.

```
Y
25(A)|\.
     |  \.
     |    \.
   0 |______\____> X
            20(B)
Area OAB = Consumer's Opportunity Set
```

---

### 3.3 Variables and Constants

- **Variable** = quantity that changes within a problem (e.g., X, Y).
- **Constant/Parameter** = quantity that stays fixed (e.g., a, b in Y = a + bX).
- **Independent variable (X)** = cause; value comes from outside the system.
- **Dependent variable (Y)** = effect; value determined by the equation.
- A **function** links two variables: Q = Q(P) means one Q for every P → demand curve.

**Function Types:**

```
LINEAR      → straight line         Q = a – bP
QUADRATIC   → U-shape or hill       Q = a – bP + CP²  (C>0 = U; C<0 = hill)
CUBIC       → S-curve / wave        Q = a – bP + CP² + dP³
```

**5 Key Economic Functions:**

| Function       | Type      | Formula                        |
|----------------|-----------|--------------------------------|
| Demand         | Linear    | Q = a – bP                     |
| Total Revenue  | Quadratic | TR = bQ – CQ²  (a=0)          |
| Production (SR)| Cubic     | TP = bL + CL² – dL³  (a=0)    |
| Cost (SR)      | Cubic     | TC = bQ + CQ² – dQ³  (a=0)    |
| Profit (SR)    | Cubic     | π = bQ + CQ² + dQ³  (a<0)     |

---

### 3.4 Derivatives

- **Slope (dy/dx)** in maths = **Marginal concept** in economics.
- dy/dx = change in Y for every 1-unit change in X.

**Key Marginal Functions:**

| Derivative | Economic Meaning               |
|------------|-------------------------------|
| dQ/dP      | Marginal demand of price       |
| dS/dA      | Marginal sales of advertising  |
| dR/dQ      | Marginal revenue               |
| dC/dQ      | Marginal cost                  |

**Elasticity = Marginal ÷ Average:**

```
Price elasticity of demand = (dQ/dP) × (P/Q)
  > 1 → Elastic demand
  < 1 → Inelastic demand
  = 1 → Unitary elastic
```

**Differentiation Rules (Appendix):**

| Rule        | Formula                                  |
|-------------|------------------------------------------|
| Basic       | Y = axⁿ  →  dy/dx = naXⁿ⁻¹             |
| Addition    | Y = u(x)+v(x)  →  du/dx + dv/dx        |
| Product     | Y = u·v  →  u(dv/dx) + v(du/dx)        |
| Quotient    | Y = u/v  →  [v(du/dx) – u(dv/dx)] / v² |
| Chain       | Y = y[u(x)]  →  (dy/du)·(du/dx)        |
| Log         | Y = log X  →  1/x                       |
| Exponential | Y = eˣ  →  eˣ                           |

---

### 3.5 Partial Derivatives

- Used when a function has **more than one independent variable**.
- Hold all other variables constant and differentiate with respect to one variable.
- Symbol: **δ** (delta).

**Mini Example:**

```
If Z = 4x² + 3xy + 5y²

δZ/δx = 8x + 3y   (treat y as constant)
δZ/δy = 3x + 10y  (treat x as constant)
```

- **First-order partial derivatives:** δf/δx, δf/δy
- **Second-order partial derivatives:** differentiate again → δ²f/δx², δ²f/δy²

---

### 3.6 Optimisation Concept

- **Optimisation** = choosing the best alternative from available options.

**3 Elements of Every Optimisation Problem:**

```
1. Decision Variables  → WHAT to choose (e.g., output level Q)
2. Objective Function  → WHAT to maximise/minimise (e.g., profit, cost)
3. Feasible Set        → ALL available alternatives
```

#### Unconstrained Optimisation

| Order        | Condition  | Maximise         | Minimise         |
|--------------|------------|------------------|------------------|
| 1st (Necess.)| Set dy/dx=0| δy/δx = 0        | δY/δX = 0        |
| 2nd (Suffic.)| Check sign | δ²y/δx² < 0     | δ²y/δx² > 0     |

**Mini Example — Maximise Total Revenue:**

```
Demand: P = 45 – 0.5Q
TR = 45Q – 0.5Q²

Step 1: dTR/dQ = 45 – Q = 0  →  Q = 45
Step 2: d²TR/dQ² = –1 < 0  ✓ (maximum confirmed)

∴ TR is maximised at Q = 45 units
```

#### Constrained Optimisation (Lagrange Multiplier)

- Used when optimisation must satisfy a **constraint**.
- Combine objective function + λ × constraint into one **Lagrange expression (L)**.
- Set δL/δx = 0 and δL/δλ = 0, then solve.

**Mini Example:**

```
Maximise Y = –x² + 8x + 20,  subject to x ≤ 2

Lagrange: L = [–(x–4)² + 36] + λ(x–2)

δL/δx = –2(x–4) + λ = 0
δL/δλ = (x–2) = 0  →  x = 2

Constrained max occurs at x = 2 (not x = 4)
λ = –4 → economic meaning: marginal utility of income (in consumer problems)
```

---

### 3.7 Regression Analysis

- **Regression** finds the mathematical relationship between a dependent variable and one or more explanatory variables.
- **Dependent variable (Y):** what you're trying to explain.
- **Explanatory variable (X):** what causes Y to change.

**Simple Regression Model:**

```
Y = a + bX

a = intercept parameter (value of Y when X = 0)
b = slope parameter (change in Y per 1-unit change in X)
```

---

### 3.8 Specifying the Regression Equation

**Steps to build a regression equation:**

```
Step 1 → Identify variables that affect demand (price, advertising, income…)
Step 2 → Collect data on each variable
Step 3 → Choose equation form:
          LINEAR:      Q = a + bP + cA
          POWER/EXP:   Q = a·Pᵇ·Aᶜ
```

- **Log-linear form** of power equation gives **direct elasticity estimates**:
  `log Q = log a + b·log P + c·log A`
  → b = price elasticity, c = advertising elasticity

---

### 3.9 Estimating the Regression Equation (OLS)

- **OLS (Ordinary Least Squares):** finds the line that **minimises the sum of squared errors**.
- Residual = actual Y – predicted Ŷ (vertical distance from point to line).

**Formulas:**

```
b̂ = Σ(Xᵢ – X̄)(Yᵢ – Ȳ) / Σ(Xᵢ – X̄)²
â = Ȳ – b̂·X̄
```

**Mini Example (from text data):**

```
7 production periods: costs range ₹100–₹410, output 0–25 units
Result: Ŷ = 87.08 + 12.21X

â = 87.08 → estimated fixed cost
b̂ = 12.21 → marginal cost (each extra unit costs ₹12.21 more)

Check: Output = 5 → Ŷ = 87.08 + 12.21(5) = 148.13
       Actual Y = 150 → Residual = 150 – 148.13 = 1.87
```

---

### 3.10 Decision Under Risk

**3 Types of Risk Attitudes:**

```
Risk Seeker  → Prefers riskier option (same expected return)
Risk Averter → Prefers safer option
Risk Neutral → Indifferent between options
```

**Key Terms:**
- **Strategy** = a plan of action (e.g., build new plant, launch marketing campaign).
- **State of Nature** = future condition beyond manager's control (recession, boom, normal).
- **Outcome** = gain or loss from a strategy + state of nature combination.

**3 Risk-Return Statistics:**

| Statistic               | Formula                          | Measures             |
|-------------------------|----------------------------------|----------------------|
| Expected Value (μ)      | μ = Σ Pᵢ·Xᵢ                    | Expected return      |
| Standard Deviation (σ)  | σ = √[Σ Pᵢ·(Xᵢ – μ)²]          | Risk (variability)   |
| Coefficient of Variation| ϑ = σ/μ                          | Risk per ₹ of return |

**Mini Example (Investment I):**

```
Outcomes: ₹100 (P=0.2), ₹200 (P=0.5), ₹400 (P=0.3)

μ = 0.2(100) + 0.5(200) + 0.3(400) = 240
σ = √[0.2(100–240)² + 0.5(200–240)² + 0.3(400–240)²] = 111.36
ϑ = 111.36 / 240 = 0.46
```

**Decision Tree:**

```
Decision Tree traces: Decision → State of Nature → Outcome

        [Manager]
        /        \
  Small Plant   Large Plant
   /    \          /     \
Boom  Recession  Boom  Recession

Probability of outcome = multiply probabilities along each branch
```

---

### 3.11 Uncertainty Analysis and Decision Making

**Key Distinctions:**

```
CERTAINTY    → Investor knows exact return (e.g., fixed deposit)
RISK         → Multiple outcomes; probabilities ARE known (e.g., coin toss)
UNCERTAINTY  → Multiple outcomes; probabilities are NOT known
```

- Decision making under uncertainty is **subjective**.
- Real-world example: A fast-food chain launched a healthier burger (40% less fat) — failed within 1 year because **what customers say ≠ what they do**.
- Lesson: Even well-researched strategies can fail. US new product failure rate = **80%**.

---

### 3.12 Role of Managerial Economist

- **Use 1:** Evaluate if resources inside the firm are being used efficiently.
- **Use 2:** Respond to external economic signals (e.g., if input price rises → substitute inputs).
- Working knowledge of managerial economics **increases value of both firm and manager**.

---

### 3.13 Summary Snapshot

| Concept              | One-line Definition                                              |
|----------------------|------------------------------------------------------------------|
| Opportunity Set      | All feasible alternatives available to a decision-maker         |
| Variables/Constants  | Variables change; constants stay fixed in a problem             |
| Derivatives          | Slope of a function = marginal concept in economics             |
| Partial Derivatives  | Derivative with respect to one variable, holding others fixed   |
| Optimisation         | Choosing the best alternative (max/min objective function)      |
| Regression Analysis  | Statistical method to estimate parameters of a function         |
| Risk                 | Multiple outcomes with known probabilities                      |
| Uncertainty          | Multiple outcomes with unknown probabilities                    |

---

*End of Unit 3 Revision Notes*
