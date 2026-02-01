# MIS312 Assignment 3 — Designing and Testing Simple Functions

**Book Alignment:** Chapter 3  
**Primary Goal:** Introduce functions + correctness thinking  
**Environment:** JupyterLab  
**Submission:** OneNote Artifact

---

## Learning Objectives
Students will:
- Write a simple Python function
- Use `assert` to check correctness
- Understand the idea of “expected behavior”

---

## Student Tasks

### Task 1 — Write a Function
Create:
```python
def apply_discount(price, discount_percent):
    """
    Returns the final price after applying a discount.
    """
    return price - (price * discount_percent / 100)
```

Test it manually with different values.

### Task 2 — Add Assertions
Add:
```python
assert apply_discount(100, 10) == 90
assert apply_discount(50, 0) == 50
assert apply_discount(200, 25) == 150
```

Run the cell and confirm no errors occur.

### Task 3 — AI Review
Ask the MIS312 AI Assistant:
> “Are there any edge cases or improvements I should consider for this function?”

Optionally implement one improvement.

---

## OneNote Artifact Requirements
- Function code
- Assertions
- Screenshot showing successful execution
- Reflection:
  - Why are assertions useful?
  - How did AI help you think about correctness?

---

## Instructor Notes
First place logical correctness matters. Emphasize correct behavior, asserts, reflection.
