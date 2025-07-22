# github-final-project
Final Project: Part 1

Read me file Updated by Vijay Shrestha

A calculator that calculates simple interest given principal, annual rate of interest and time period in years.
Input:
   p, principal amount
   t, time period in years
   r, annual rate of interest
Output
   simple interest = p*t*r



   Here’s a clear explanation of how a **Simple Interest Calculator** works:

---

 **What is Simple Interest?**

**Simple Interest (SI)** is a straightforward method for calculating interest on borrowed or invested money **without compounding**. It is calculated only on the **original principal** for the entire time period.

---

**Formula:**

$$
\text{Simple Interest (SI)} = \frac{P \times R \times T}{100}
$$

Where:

* **`P`** = Principal amount (initial money)
* **`R`** = Annual Rate of Interest (in %)
* **`T`** = Time period (in years)

---

 **Inputs:**

* `p`: Principal amount (e.g., \$1000)
* `r`: Annual rate of interest (e.g., 5%)
* `t`: Time period in years (e.g., 2 years)

---

###  **Output:**

* The **simple interest** earned or paid over the time period.

---

### **Example:**

Let’s say:

* Principal `P = 1000`
* Rate `R = 5%`
* Time `T = 2` years

Then:

$$
SI = \frac{1000 \times 5 \times 2}{100} = \frac{10000}{100} = 100
$$

**Output:** Simple Interest = **100**

---

**Sample Code in Python:**

```python
p = float(input("Enter the principal amount: "))
r = float(input("Enter the annual interest rate (%): "))
t = float(input("Enter the time period in years: "))

si = (p * r * t) / 100

print(f"Simple Interest = {si}")
```

By Vijay Shrestha

