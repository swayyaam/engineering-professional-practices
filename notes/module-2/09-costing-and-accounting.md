# Costing and Accounting

> **Source:** `Module 2/Lecture 09 Costing Accounting.pdf` (Lecture 09), pages 1–19 · **Syllabus:** Selected Functions of Engineering

## Lecture outcomes

After attending the lectures, a student will be able to:

| | |
|---|---|
| **LO 1** | Explain the concepts of **cost** and **cost driver**. |
| **LO 2** | Differentiate between **fixed cost** and **variable cost**. |
| **LO 3** | Make **cost-volume-profit analyses** to find out the break-even points under a variety of decision-making situations. |

## Key points

- **Cost** = the price one must pay — a sacrifice or resource given up for an item or service. A **cost driver** is any output measure that **causes** cost.
- **Fixed cost** does not change with the cost-driver activity level; **variable cost** changes **in direct proportion** to it.
- Net income **I = pQ − (F + vQ)**.
- **Break-even quantity Q\* = F / (p − v)** — fixed cost ÷ contribution margin per unit.
- **Margin of safety = planned sales − break-even sales**; it shows how far sales can fall before losses occur.
- Automation raises **F** and lowers **v** — which moves the break-even point.

---

## 1. Cost and cost driver

- **Cost** is the price that one must pay — **a sacrifice or resource given up** for an item or service.
- When an item or service is **procured and used up immediately**, the cost is **easy to measure**. But when it is used for a **long period**, the cost is **difficult to measure**.
- A **cost driver** is **any output measure that causes cost** — i.e. causes the use of costly resources.

### Cost drivers along the value chain

| Value chain function | Example of cost | Example of cost driver |
|---|---|---|
| **R&D** | Cost of feasibility study | Number of new project proposals |
| **Design** of products, services and processes | Cost to develop and test prototype | Number of parts per product |
| **Production** | Labour wages | Number of labour-hours |
| | Material cost | Quantity of material used |
| | Cost of energy expended in machining | Machine hours |
| **Marketing** | Cost of advertisement | Number of advertisements |
| **Distribution** | Transportation cost | Weights of items |
| **Customer service** | Cost of supplies, travel | Number of service calls |

## 2. Fixed and variable costs

| | **Fixed cost** | **Variable cost** |
|---|---|---|
| **Definition** | One that **does not change** when the level of its cost driver activity changes | One that **changes in direct proportion** to the change in its cost driver activity level |

**Example.** As the production volume changes, the **material cost changes**, but the **machine cost per hour does not change**.
→ Material cost: **variable cost**. Machine cost: **fixed cost**.

## 3. Cost-volume-profit (CVP) analysis

The analysis that helps in assessing the effect of **output volume** on **revenue (sales), expenses (cost), and net income (net profit)**.

### Major assumptions

1. Costs can be classified as **fixed or variable** with respect to a single measure of volume of output activity.
2. **Sales and variable costs vary proportionately** with the output level.
3. **All items produced are sold**, with no inventory built up.
4. **Productivity is unchanged.**
5. **Sales mix is constant.**

### Notation and equations

| Symbol | Meaning |
|---|---|
| **p** | Unit sales price (Rs/unit) |
| **v** | Unit variable cost of manufacturing (Rs/unit) |
| **F** | Fixed cost (Rs/week) |
| **Q** | Quantity produced and sold (unit/week) |

| Quantity | Expression |
|---|---|
| Total variable cost (Rs/week) | **vQ** |
| Total fixed cost (Rs/week) | **F** |
| Total cost of production (Rs/week) | **F + vQ** |
| Total sales revenue (Rs/week) | **pQ** |
| **Net income** | **I = pQ − (F + vQ)** |

## 4. Break-even point

The **break-even point** is the level of sales **Q\*** at which **revenue equals expenses** and **net income equals zero**:

$$F + vQ^* = pQ^* \quad\Longrightarrow\quad pQ^* - F - vQ^* = 0 \quad\Longrightarrow\quad \boxed{Q^* = \frac{F}{p-v}}$$

### Contribution margin (marginal income)

$$\text{Contribution margin} = \text{Unit sales price} - \text{Unit variable cost} = p - v$$

The break-even point is thus:

$$Q^* = \frac{F}{p-v} = \frac{\text{Fixed cost}}{\text{Contribution margin per unit}}$$

**Q\* is the amount of sales at which the total contribution margin equals the fixed cost** — i.e. the total amount at which the fixed cost is **fully recovered**.

### Graphical solution

```
 (Rs/week)                             Total Revenue = pQ
     ^                            ／
     |                        ／  ／  Total Cost = F + vQ
     |                    ／  ／
     |     PROFIT     ／ ／
     |            ／ ／ ← Break-even Point
     |        ／ ／
     |    ／ ／        LOSS                 ↑ slope v
     | ／／ ────────────────────── Fixed Cost = F
     |／
     +-------------|--------------------> Q (unit/week)
                   Q*
```

- Below **Q\***: total cost exceeds total revenue → **loss**.
- Above **Q\***: total revenue exceeds total cost → **profit**.
- The **variable cost** line rises from the origin with slope **v**; the **total cost** line is the same slope offset upward by **F**.

## 5. Worked example

> A factory has the following fixed and variable costs. Note that **repair and maintenance cost is a semi-variable cost**. The unit price of the item is **Rs 30**.

| | Fixed cost (Rs/year) | Variable cost (Rs/unit) |
|---|---|---|
| Depreciation | 20,000 | |
| Insurance | 5,000 | |
| Repair & Maintenance | 5,000 | 0.50 |
| Material | | 9.50 |
| Labour and Power | | 10.00 |
| **Total** | **30,000** | **20.00** |

**(a) Find the break-even quantity to be produced.**

Given **F = 30,000** Rs/year, **v = 20** Rs/unit, **p = 30** Rs/unit:

$$Q^* = \frac{F}{p-v} = \frac{30{,}000}{30-20} = 3{,}000 \text{ units/year}$$

**(b) If the production plan is 2,000 units annually, what is the profit/loss?**

The production plan is **Qp = 2,000 units/year**.

| | Calculation | Result |
|---|---|---|
| Total revenue | (2,000)(30) | 60,000 Rs/year |
| Total cost | 30,000 + (2,000)(20) | 70,000 Rs/year |
| **Loss** | 70,000 − 60,000 | **10,000 Rs/year** |

## 6. Margin of safety

$$\text{Margin of safety} = \text{Planned sales} - \text{Break-even sales}$$

- It helps to **assess the possible risk**.
- It shows **how far sales can fall below the planned level before losses occur**.

```
 (Rs/week)                    Total Revenue = pQ
     ^                    ／
     |                ／  ／ Total Cost = F + vQ
     |    PROFIT  ／  ／
     |        ／ ／
     |    ／／ ← break-even
     | ／／     LOSS
   F |──────────────────────
     |          |<-- Margin of Safety -->|
     +----------|------------------------|---> Q (unit/week)
                Q*                       Qp
                              (Planned Production)
```

## 7. Effect of changes in cost structure

### Change in fixed cost

If fixed cost rises from **F₁** to **F₂** (with **v** unchanged), the total cost line shifts **upward in parallel**, and the break-even quantity rises: **Q₁\* → Q₂\***, with **Q₂\* > Q₁\***.

### Change in variable cost

If variable cost rises from **v₁** to **v₂** (with **F** unchanged), the total cost line becomes **steeper** from the same intercept **F**, and the break-even quantity rises: **Q₁\* → Q₂\***, with **Q₂\* > Q₁\***.

### Example — automation

**Automation usually involves substantial fixed cost and reduced variable cost.** Normally, high volume of production breaks even the cost — **but it may not always be the case.**

| | Without automation | With automation |
|---|---|---|
| **Fixed cost** | F₁ | F₂ |
| **Variable cost** | v₁ | v₂ |
| **Break-even quantity** | Q₁\* | Q₂\* |

$$F_1 < F_2, \qquad v_1 > v_2, \qquad Q_1^* > Q_2^*$$

**Reading:** automation raises the fixed cost and cuts the variable cost. In the case drawn, the steeper contribution per unit more than compensates, so the break-even quantity **falls**.

## 8. Sales-mix analysis

Two products:

- **Product 1:** p₁, v₁, and F₁
- **Product 2:** p₂, v₂, and F₂

Assume a **constant mix of c units of product 2 for every one unit of product 1**. Thus if the break-even point for product 1 is **Q₁\***, then the break-even point for product 2 is **Q₂\* = cQ₁\***.

Hence:

$$[(p_1)(Q_1^*) + (p_2)(cQ_1^*)] - [(v_1)(Q_1^*) + (v_2)(cQ_1^*)] - [F_1 + F_2] = 0$$

**Q₁\***, and hence **Q₂\* = cQ₁\***, can be determined. These values are **conditional on the constant sales mix of 1:c**.

## 9. Various cost-behaviour patterns

> The deck presents these as five sketched graphs. Their shapes are **transcribed from that slide image**.

Not every cost is a straight line. The deck sketches five real-world shapes:

| Pattern | Shape | Why |
|---|---|---|
| **Labour cost** (workers learning with experience) | Concave — rises steeply, then flattens | The learning curve: each additional unit costs less labour than the last. |
| **Material cost** (price rising with usage) | Convex — rises slowly, then steeply | Larger quantities push the buyer into scarcer, dearer supply. |
| **Wage cost** (guaranteed wage) | Flat, then rising linearly | A guaranteed minimum is paid regardless of output; beyond a threshold, wage rises with output. |
| **Material cost** (unit price discounting) | Piecewise linear, flattening in steps | Volume discounts reduce the marginal price at each break point. |
| **Machine cost** (machines are added) | A step function | Capacity is bought in whole machines; cost jumps each time one is added. |

> These shapes matter because CVP analysis (§3) assumes costs are **either fixed or strictly proportional**. Where the real pattern is a curve or a step, the straight-line model holds only over a limited range of output.

> The qualitative side of accounting in engineering — budgeting, cost control, NPV/IRR, depreciation and activity-based costing — is covered in [Managerial Functions in Engineering](08-managerial-functions.md#5-accounting).
