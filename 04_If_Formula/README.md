# 🔀 IF Formulas in Excel

## 📌 Overview

In this lesson, I learned how to use the **IF function in Microsoft Excel**.

The IF function is a logical function used to check whether a condition is TRUE or FALSE and return a corresponding result.

---

## 🔢 IF Function Syntax

```excel
=IF(logical_test, value_if_true, value_if_false)
```

### Parameters

* **logical_test** → The condition that needs to be checked.
* **value_if_true** → The result returned when the condition is TRUE.
* **value_if_false** → The result returned when the condition is FALSE.

---

## 📝 Example

To check whether a student has passed or failed:

```excel
=IF(J2>=35,"Pass","Fail")
```

If the value in `J2` is **35 or more**, Excel returns:

```text
Pass
```

Otherwise, it returns:

```text
Fail
```

---

## 📊 Practice

I practiced the IF function using the student marks dataset.

The IF formula was used to apply a condition and automatically return the required result for each student.

---

## 🎯 Key Learnings

* Understanding the IF function
* Understanding logical conditions
* Using comparison operators with IF
* Returning different results based on a condition
* Applying IF formulas to multiple rows

---

## 🧠 Important Concept

The basic logic of the IF function is:

```text
Condition
   ↓
TRUE  →  One Result
FALSE →  Another Result
```

---

## 📂 Files

```text
04_IF_Formulas_in_Excel/
│
├── README.md
└── IF_Formulas_Practice.xlsx
```

---

## 🚀 Progress

**Topic:** IF Formulas in Excel
**Status:** ✅ Completed
