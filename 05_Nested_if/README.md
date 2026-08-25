# 🔀 Nested IF and IFS Formula

## 📌 Overview

In this lesson, I learned how to use **Nested IF** and **IFS** formulas in Microsoft Excel.

These formulas are useful when we need to check multiple conditions and return different results based on those conditions.

---

## 1️⃣ Nested IF Formula

A Nested IF means using one or more IF functions inside another IF function.

### Syntax

```excel
=IF(condition1,result1,IF(condition2,result2,IF(condition3,result3,result4)))
```

### Example

To assign grades based on marks:

```excel
=IF(A2>=90,"A",IF(A2>=75,"B",IF(A2>=60,"C",IF(A2>=35,"D","Fail"))))
```

### Logic

```text
Marks >= 90  → A
Marks >= 75  → B
Marks >= 60  → C
Marks >= 35  → D
Below 35     → Fail
```

The conditions are checked one by one until a TRUE condition is found.

---

## 2️⃣ IFS Formula

The IFS function is used to check multiple conditions without writing multiple IF functions inside each other.

### Syntax

```excel
=IFS(condition1,result1,condition2,result2,condition3,result3)
```

### Example

```excel
=IFS(A2>=90,"A",A2>=75,"B",A2>=60,"C",A2>=35,"D",A2<35,"Fail")
```

This checks each condition in order and returns the result for the first TRUE condition.

---

## 🔍 Nested IF vs IFS

| Feature                    | Nested IF                   | IFS                             |
| -------------------------- | --------------------------- | ------------------------------- |
| Multiple conditions        | Yes                         | Yes                             |
| Uses multiple IF functions | Yes                         | No                              |
| Formula readability        | More complex                | Easier                          |
| Useful for                 | Multiple logical conditions | Multiple condition-result pairs |

---

## 📊 Practice

I practiced Nested IF and IFS formulas using student marks data.

The formulas were used to classify students into different categories based on their marks.

---

## 🎯 Key Learnings

* Understanding Nested IF
* Writing multiple conditions using IF
* Understanding the IFS function
* Comparing Nested IF and IFS
* Applying multiple conditions to data
* Returning different results based on conditions

---

## 📂 Files

```text
05_Nested_IF_and_IFS/
│
├── README.md
└── Nested_IF_IFS_Practice.xlsx
```

---

## 🚀 Progress

**Lesson:** 05 - Nested IF and IFS Formula
**Day:** 03
**Status:** ✅ Completed
