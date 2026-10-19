# Exercise 11 — The Debugging Gauntlet

Five programs, escalating difficulty. Fix each one, then document it.

For each: what type of error, what the message said (or didn't), and what was actually wrong.

---

## DebugMe1

| | |
|---|---|
| **Error type** (syntax / runtime / logic) | Syntax |
| **Message Java gave** | src/DebugMe1.java:5: error: ';' expected |
| **What was actually wrong** | missing an expected semicolon |
| **The fix** | add a seminicolon at the end of line 5 |

---

## DebugMe2

| | |
|---|---|
| **Error type** |  Syntax |
| **Message** | src/DebugMe2.java:6: error: ';' expected, and src/DebugMe2.java:5: error: incompatible types: String cannot be converted to int
        int age = "17"; |
| **What was wrong** |  |
| **The fix** | |

---

## DebugMe3

| | |
|---|---|
| **Error type** | Syntax |
| **Message** | error: incompatible types |
| **What was wrong** |  |
| **The fix** | |

---

## DebugMe4

| | |
|---|---|
| **Error type** |  error: cannot find symbol
        double average = totalscore / numTests;
                         ^
  symbol:   variable totalscore
  location: class DebugMe4
src/DebugMe4.java:9: error: cannot find symbol
        System.out.println("Average: " + Average);
                                         ^
  symbol:   variable Average
  location: class DebugMe4
2 errors |
| **Message** | |
| **What was wrong** | |
| **The fix** | |

---

## DebugMe5

> ⚠️ This one **compiles and runs**. It just gives the wrong answer.

| | |
|---|---|
| **Error type** | Logic |
| **What output did you expect?** | |
| **What output did you get?** | |
| **What was actually wrong** | |
| **The fix** | |
| **How did you find it?** | |

---

## Reflection

**1. Which was hardest? Why?**

[your answer]

**2. DebugMe5 had no error message at all. What strategy did you use to find the problem?**

[your answer]

**3. Why is a logic error more dangerous in real software than a syntax error?**

[your answer]
