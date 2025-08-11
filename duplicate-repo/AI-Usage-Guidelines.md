# Use of AI Tools – Reflection (Manual Q&A Intern)

## 🎯 Goal

Learn how to use AI tools effectively in a Manual Q&A role while protecting data privacy, maintaining accuracy, and applying critical thinking.

---

## ❓ Why is this important?

In a Manual Q&A role, accuracy and attention to detail are essential.  
AI tools can help by speeding up certain tasks—such as summarising test cases, drafting bug reports, or checking documentation—but if misused, they can:

- Leak confidential test data.
- Produce inaccurate or misleading information.
- Reduce the habit of independently verifying results.

---

## 🔍 Research & Learn

### 1. AI tools typically used in a Manual Q&A role

- **ChatGPT / Claude** → For drafting test scenarios, clarifying requirements, and generating example test data.
- **Grammarly** → For improving clarity in bug reports or test documentation.
- **Test Case Generators** → For creating initial outlines of test cases (then refining manually).

### 2. Benefits and risks of AI in Q&A work

**Benefits**

- Quickly generate test ideas and scenarios.
- Summarise complex requirement documents.
- Improve clarity and grammar in bug reports.

**Risks**

- AI might miss edge cases that a human tester would find.
- Risk of exposing sensitive customer data or proprietary systems info.
- Possible incorrect or incomplete test coverage if relying solely on AI.

### 3. Information that should never be entered into AI tools

- Login credentials or API keys.
- Internal system architecture details.
- Real customer data or screenshots containing sensitive information.
- Proprietary Focus Bear workflows or unreleased features.

### 4. How to fact-check and validate AI-generated content

- Compare AI-generated test steps with the actual system under test.
- Cross-reference against official requirement documents.
- Ask a senior tester or developer to review critical outputs.
- Manually run through any AI-suggested test to confirm accuracy.

---

## 📝 Reflection

### 1. When to use AI vs my own skills

- **Use AI**: For generating initial test case outlines, brainstorming edge cases, or improving bug report grammar.
- **Use my own skills**: For executing tests, identifying unexpected behaviours, verifying defect reproduction steps, and making go/no-go release decisions.

### 2. Avoiding over-reliance

- Treat AI as a helper, not a decision-maker.
- Always manually execute and verify any AI-suggested test.
- Continue improving domain knowledge so I can spot AI mistakes.

### 3. Ensuring data privacy

- Use anonymised or dummy data when working with AI.
- Avoid sharing any proprietary Focus Bear information in AI prompts.
- Follow Focus Bear’s internal data handling guidelines at all times.

---

## 🛠️ Task

**Task Identified:** Writing regression test scenarios for a new Focus Bear feature.  
**AI Tool Used:** ChatGPT.

**AI Output Review:**  
The AI provided a good starting point for regression tests, but some scenarios were irrelevant to the current release. I removed those and added more edge cases based on my testing experience.

**Best Practice Documented:**

> Always review AI-generated test cases against actual system requirements and update them to match the project’s current scope.

---

## 📌 Summary

As a Manual Q&A Intern, I will:

- Use AI for efficiency, not as a replacement for hands-on testing.
- Protect Focus Bear’s confidential and proprietary data.
- Validate all AI outputs through manual execution and requirement checks.
