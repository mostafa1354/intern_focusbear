# 🧠 Core Manual QA Skills – Using Heuristics to Guide Testing

## Role Context

Manual Q&A Intern at Focus Bear.  
My role requires testing features even when documentation is incomplete, which means applying heuristics can help identify high-risk areas and edge cases quickly.

---

## 🔍 Research & Learn

### What Are Heuristics in Software Testing?

Heuristics are **rules of thumb, mental shortcuts, or patterns** used to guide decision-making in testing, especially when requirements are incomplete or unclear.  
They help testers decide:

- **What to test first**
- **How deeply to explore**
- **Where potential risks may lie**

They are **not guarantees**, but they can lead to faster discovery of important issues.

---

### Why Heuristics Are Useful

- Allow quick prioritization under time pressure.
- Help find bugs that might be missed by rigid, scripted testing.
- Encourage creative and exploratory thinking.
- Provide a framework for approaching ambiguous situations.

---

### Common Testing Heuristics

- **The Rule of Three**: If you find one bug, look for at least two more in the same area.
- **Consistency Heuristic**: Compare against internal consistency (within the app), external consistency (industry norms), and historical consistency (past versions).
- **CRUD**: Check Create, Read, Update, Delete operations for relevant data entities.
- **Zero, One, Many**: Test with none, one, and multiple items to see how the system handles different counts.
- **Boundaries**: Test at and just beyond input limits.

---

### How Experienced Testers Use Heuristics to Prioritize

- Focus on **high-risk areas** first (features most critical to the user or most likely to fail).
- Use historical bug patterns to guide initial exploration.
- Start with areas of **new or changed code** where regressions are more likely.

---

### When to Be Cautious About Over-Relying on Heuristics

- Heuristics can lead to bias—testers may overfocus on familiar areas.
- May miss requirements if relying solely on gut instinct instead of checking documentation.
- Should complement, not replace, structured test cases.

---

## 📝 Reflection

### If I Had Only 15 Minutes to Test a New Focus Bear Feature

I would:

1. Identify the **core user flow** and test it end-to-end (Critical Path Heuristic).
2. Apply **Consistency Heuristic** to ensure it aligns with other parts of the app.
3. Check **Boundaries** for key inputs or configurations.
4. Use the **Rule of Three** if I find an issue to explore similar problem areas.

---

### How Heuristics Help Find Edge Cases & Unexpected Bugs

- **Zero, One, Many** exposes logic gaps when dealing with unusual data counts.
- **Boundaries** reveal off-by-one errors, validation issues, or performance problems.
- **Consistency** catches UI/UX mismatches that scripted tests might ignore.

---

### Risks of Using Gut Instinct vs. Structured Test Cases

- Gut instinct can **miss coverage** in less obvious areas.
- Structured cases ensure **systematic coverage** but may miss unexpected bugs.
- Best approach: **Blend both** — start with exploratory heuristics to find high-impact issues, then follow with structured cases for completeness.

---
