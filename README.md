# BIG COUNTRIES

## 📌 Problem Description

We have a table called **World** that looks like this:

| name        | continent | area    | population | gdp          |
|-------------|-----------|---------|------------|--------------|
| Afghanistan | Asia      | 652230  | 25500100   | 20343000000  |
| Albania     | Europe    | 28748   | 2831741    | 12960000000  |
| Algeria     | Africa    | 2381741 | 37100000   | 188681000000 |
| Andorra     | Europe    | 468     | 78115      | 3712000000   |
| Angola      | Africa    | 1246700 | 20609294   | 100990000000 |

Each row tells us about a country — its name, what continent it belongs to, its area (size), population (how many people live there), and GDP (how much money the country makes).

## 🌍 What is a "Big Country"?
A country is called **BIG** if:

1. It has an area of at least **3,000,000 km²** — that's really huge!
2. OR it has a population of **25,000,000 people** or more — that’s a lot of people!

Our task is to **find the big countries** and show only their **name**, **population**, and **area**.

## 🧠 Example

If we start with this table:

| name        | continent | area    | population | gdp          |
|-------------|-----------|---------|------------|--------------|
| Afghanistan | Asia      | 652230  | 25500100   | 20343000000  |
| Albania     | Europe    | 28748   | 2831741    | 12960000000  |
| Algeria     | Africa    | 2381741 | 37100000   | 188681000000 |
| Andorra     | Europe    | 468     | 78115      | 3712000000   |
| Angola      | Africa    | 1246700 | 20609294   | 100990000000 |

👉 The output should look like this:

| name        | population | area    |
|-------------|------------|---------|
| Afghanistan | 25500100   | 652230  |
| Algeria     | 37100000   | 2381741 |

**Why?**
- Afghanistan has a population over **25 million** ✅
- Algeria has both a population over **25 million** ✅ and a **huge** area ✅
- Albania, Andorra, and Angola are **too small** for both rules ❌

## 🛠️ How to Solve It
You can write an SQL query that checks two things:
- **Is the area ≥ 3,000,000?**
- **OR is the population ≥ 25,000,000?**

If **either one** is true, the country is **BIG**!

### 🏁 Output
Your solution should show:
- **Country name**
- **Population**
- **Area**

✨ And you can return the results in any order!

---

Happy coding! 🚀 Let’s find those big countries! 🌎✨

