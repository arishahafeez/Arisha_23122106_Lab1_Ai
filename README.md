# Arisha_23122106_Lab1_AI_6A

## Intelligent Agents Assignment

### AI Real Estate Recommendation Agent

**Student Name:** Arisha Hafeez
**Roll Number:** 23122106 **Section:** A **Semester:**  6

---

## Project Overview

This repository contains my submission for the Intelligent Agents assignment, focused on
the design and evaluation of an **AI Real Estate Recommendation Agent**.

The agent is built around a common real-world problem: property buyers are often
overwhelmed by the number of listings spread across different platforms, making it hard to
find a home that fits their budget and requirements. This project models an agent that
collects a buyer's preferences — budget, location, and property type — and recommends the
most suitable listings automatically.

The assignment report covers four parts — problem identification, problem formulation
(with a graphical environment diagram), evaluation using the PEAS framework, and
classification of the agent's environmental properties.

As a small practical example, I also implemented a rule-based Travel Agent in Python to
demonstrate conditional decision-making using if / elif / else logic.

---

## Repository Contents

| File | Description |
|---|---|
| `AI_Real_Estate_Agent_Assignment.pdf` | Complete Intelligent Agents assignment report |
| `[HerName]_Lab1_TravelAgent.ipynb` | Google Colab notebook containing the rule-based Travel Agent example |
| `README.md` | Project documentation and overview |

---

## Basic Travel Agent Example

As a small practical example, I created a simple rule-based Travel Agent.

The agent checks the number of passengers booking together and applies a group discount
accordingly.

- If there are **5 or more passengers**, a 20% group discount is applied.
- If there are **3 or 4 passengers**, a 10% discount is applied.
- Otherwise, the full price applies with no discount.

### Python Code

```python
num_passengers = 4
base_price = 15000
destination = "Murree"

if num_passengers >= 5:
    discount = 0.20
elif num_passengers >= 3:
    discount = 0.10
else:
    discount = 0

total_price = base_price * num_passengers * (1 - discount)
print(f"Total price for {num_passengers} passengers to {destination}: PKR {total_price}")


---

## Key Concepts Applied

- **PEAS Framework** — Performance measure, Environment, Actuators, Sensors
- **Environment Properties** — Partially Observable, Stochastic, Sequential, Dynamic,
  Continuous, Multi-Agent
- **Conditional Decision Making** — if / elif / else logic, as shown in the Travel Agent
  example above
