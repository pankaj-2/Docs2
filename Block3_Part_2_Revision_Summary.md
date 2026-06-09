# MBA Exam Revision — Unit 9: Long Run Cost Analysis

> **Overview:** In the long run, ALL inputs are variable (no fixed costs). This unit covers how costs behave as firms change plant size, the sources of cost savings (economies), and how to estimate and use cost functions for decisions.

---

## Chapter: Long Run Cost Analysis

---

### 9.1 Introduction

- Long-run cost analysis helps managers decide on expanding/contracting plant size.
- Short-run cost functions → judge current output; Long-run cost functions → plan future plant size.

---

### 9.2 Long-Run Cost Functions

- In the long run, all inputs are variable → no fixed costs exist.
- The **Long Run Average Cost (LRAC)** curve is derived by picking the *lowest* point from all Short Run Average Cost (SRAC) curves.
- LRAC is also called the **"planning curve"** or **"envelope curve"** (it wraps around all SRAC curves).
- Long Run Total Cost: **LRTC = LRAC × Q**
- At the single optimum point **a**: SRAC = SRMC = LRAC = LRMC

**ASCII: How LRAC is Built**

```
Cost
 |   SRAC1   SRAC2   SRAC3   SRAC4
 |  \      \/      \/      /
 |   \    /  \    /  \   /
 |    \__/    \__/    \_/
 |   [LRAC = bold envelope curve below all SRACs]
 |___________________________________ Output (Q)
      Q1  Q2      Q3      Q4
```

---

### 9.3 Economies and Diseconomies of Scale

- **Economies of scale** → LRAC *falls* as output increases (increasing returns to scale).
- **Diseconomies of scale** → LRAC *rises* as output increases (decreasing returns to scale).
- **Constant returns to scale** → LRAC stays flat.
- The U-shape of LRAC is explained by economies then diseconomies of scale (NOT diminishing returns — that's short run only).

**Cost-Output Elasticity (Ec):**

```
Ec = MC / AC

Ec < 1  → Economies of scale (MC < AC)
Ec = 1  → Constant returns (MC = AC)
Ec > 1  → Diseconomies of scale (MC > AC)
```

#### Internal Economies of Scale

**A) Real Economies**

- **Labour:** Division of labour + specialisation → lower cost per unit.
- **Technical:** Indivisible machines spread cost over more units; large machines automate multiple steps.
- **Inventory:** Larger firms absorb supply/demand fluctuations with less proportional stock.
- **Marketing:** Advertising & R&D costs spread over more units → lower cost per unit.
- **Managerial:** Specialisation + decentralisation + team experience → faster, cheaper decisions.
- **Transport & Storage:** Storage costs fall with size; transport costs fall then flatten (L-shaped).

**B) Pecuniary Economies**

- Bulk buying → lower raw material prices.
- Large firms get lower interest rates from banks.
- Bulk advertising → better ad rates.
- Bulk transport → lower per-unit shipping cost.
- Monopsony power → lower wage costs.

#### External Economies of Scale

- Shared by ALL firms in an industry when the whole industry expands.
- Examples: shared research, specialised suppliers, by-product processors.

#### Diseconomies of Scale

- Arise mainly from **human/behavioural problems**, not technical ones.
- **Morale & motivation:** More employees → less personal connection → lower productivity.
- **Communication:** More management layers → messages distorted or lost → lower efficiency.

**ASCII: Shape of LRAC**

```
Cost
 |\ 
 | \   Economies    Constant    Diseconomies
 |  \   of scale    returns      of scale
 |   \_____________
 |                 \_________
 |                            \___/
 |__________________________________ Output (Q)
                   Q* (optimum)
```

---

### 9.4 Learning Curve

- As workers practice more, they get better → cost per unit *falls* over time.
- **Learning curve effect** = reduction in labour cost due to accumulated experience.

---

### 9.5 Economies of Scope

- Cost advantage from producing **two or more products *jointly*** rather than separately.
- Different from economies of scale (which is about *volume*); scope is about *variety*.

**Formula:**

```
SC = [C(Q1) + C(Q2) − C(Q1,Q2)] / C(Q1,Q2)

SC > 0 → Economies of scope (joint production is cheaper)
SC < 0 → Diseconomies of scope
```

**Mini Worked Example:**

| Scenario | Cost |
|---|---|
| 10,000 TVs + 5,000 Radios jointly | Rs. 8.40 cr |
| 10,000 TVs alone | Rs. 10.00 cr |
| 5,000 Radios alone | Rs. 0.50 cr |

```
SC = (10.00 + 0.50 − 8.40) / 8.40 = 0.25
→ 25% cost saving from joint production
```

---

### 9.6 Cost Function and Its Determinants

**General form:** `C = f(S, O, P, T, E)`

| Variable | Meaning | Direction of effect on cost |
|---|---|---|
| S (Plant size) | Scale of operations | ↑S → ↓unit cost |
| O (Output level) | Quantity produced | ↑O → ↑total cost |
| P (Input prices) | Labour, materials, etc. | ↑P → ↑cost |
| T (Technology) | Production method | Better T → ↓cost |
| E (Managerial efficiency) | Management quality | ↑E → ↓cost |

---

### 9.7 Estimation of Cost Function

**Three Methods:**

| Method | How it works | Best for |
|---|---|---|
| **Accounting** | Classify costs into fixed/variable/semi-variable; estimate each separately | Firm level |
| **Engineering** | Use physical input-output relationships + input prices to build cost curve | Short run; when historical data is scarce |
| **Econometric** | Use regression on historical cost & output data | Industry/national level |

- The three methods are **complementary**, not competing.

#### Functional Forms of Total Cost (TC)

**A) Linear:**
```
TC = a + bQ
AC = (a/Q) + b    [falls then flattens]
MC = b             [constant]
```

**B) Quadratic:**
```
TC = a + bQ + cQ²
AC = (a/Q) + b + cQ   [U-shaped]
MC = b + 2cQ           [linearly rising]
```

**C) Cubic:**
```
TC = a + bQ + cQ² + dQ³
AC = (a/Q) + b + cQ + dQ²   [U-shaped]
MC = b + 2cQ + 3dQ²          [U-shaped]
```

> **Rule:** To test full theoretical cost-output shape (U-shaped AC *and* MC), use **cubic** function.

**Mini Worked Example (Quadratic):**

Given: `TC = 1016 − 3.36Q + 0.021Q²`

*Step 1 — AC and MC:*
```
AC = (1016/Q) − 3.36 + 0.021Q
MC = −3.36 + 0.042Q
```

*Step 2 — Minimise AC (set dAC/dQ = 0):*
```
−1016/Q² + 0.021 = 0
Q² = 1016/0.021 = 48,381
Q = 220 units
```

*Step 3 — AC at Q = 220:*
```
AC = (1016/220) − 3.36 + (0.021 × 220) = Rs. 5.88/unit
```

*Decision: Market price = Rs. 5.50. Since min cost (5.88) > price (5.50), do NOT build the plant.*

---

### 9.8 Empirical Estimates of Cost Function

**Short-run findings (Table 9.1 summary):**
- Most industries show **constant or declining MC** (not the U-shaped MC theory predicts).
- Linear total variable cost with constant MC best describes real short-run cost.

**Long-run findings (Table 9.2 summary):**
- Light manufacturing (e.g. baking) → diseconomies set in quickly → small plant is efficient.
- Meat packing, household appliances → LRAC is **flat** over a wide range → many plant sizes equally efficient.
- Electricity, metals → strong economies of scale → large plant is most efficient.
- Empirical LRAC is usually **L-shaped** (not U-shaped as theory suggests).

```
Theoretical LRAC     Empirical LRAC (common)
     /\                   |\ 
    /  \                  | \
   /    \                 |  \_______________
  /      \                |
 Q*                       Q
 U-shaped                 L-shaped
```

**Problems in Estimating Cost Functions:**
1. Cost and output data must be correctly matched by time period.
2. Output rate must be steady (fluctuating output distorts results).
3. Accounting data may miss implicit costs or misallocate costs by period.
4. Multi-product firms make it hard to separate costs per product.
5. Price changes over time must be removed by deflating data with price indices.
6. Choosing the right functional form (linear/quadratic/cubic) is not straightforward.

---

### 9.9 Managerial Uses of Cost Function

- **Optimum plant size:** Find plant size K where LRAC is minimum.
- **Optimum output for a given plant:** Find Q where short-run AC is minimum.
- **Firm's supply curve:** Price determines how much a firm supplies; needs cost function + firm's objective to derive supply schedule.

---

### 9.10 Summary (Key Takeaways)

- Long run → all costs are variable; LRTC = LRAC × Q.
- LRAC is the "envelope curve" of all SRACs.
- U-shape of LRAC explained by economies → diseconomies of scale.
- Economies of scope = cost advantage from producing multiple products jointly.
- Three estimation methods: accounting, engineering, econometric (all complementary).
- Cubic cost function best matches theory; empirical LRAC is usually L-shaped.

---

### Quick Formula Sheet

| Concept | Formula |
|---|---|
| LRTC | LRAC × Q |
| Cost-output elasticity | Ec = MC/AC |
| Economies of scope | SC = [C(Q1)+C(Q2)−C(Q1,Q2)] / C(Q1,Q2) |
| Linear TC → MC | MC = b (constant) |
| Quadratic TC → MC | MC = b + 2cQ |
| Cubic TC → MC | MC = b + 2cQ + 3dQ² |
| Min AC output | Set dAC/dQ = 0, solve for Q |
| Min MC output | Set dMC/dQ = 0, solve for Q |
