# 📊 Understanding Release Cycles & Version Control

## Role Context

Manual Q&A Intern at Focus Bear.  
My work requires understanding when to test, what environment to test in, and how version control impacts the testing process. This ensures that I’m validating the correct version of the product and catching issues early.

---

## 🔍 Research & Learn

### Typical Stages in a Software Release Cycle

1. **Development** – Developers work on new features or bug fixes in dedicated branches.
2. **Testing (QA)** – QA tests changes in a controlled environment to find bugs before deployment.
3. **Staging** – A pre-production environment that closely mirrors production for final checks.
4. **Production** – The live environment where the app is available to end users.

### QA Work in Feature Releases vs. Hotfixes

- **Feature Release**: QA conducts thorough regression testing, exploratory testing, and usability checks.
- **Hotfix**: QA focuses on verifying the specific fix quickly while ensuring no critical new bugs are introduced.

### What is Version Control (Git) and Its Impact on Testing

- Git tracks changes in source code over time and allows multiple developers to work in parallel.
- For QA, Git provides visibility into what changes are included in a build and which branch they came from.
- Helps link bugs to specific commits or pull requests.

### Git Branches and Why Testers Should Care

- **Main/Production branch** – Stable code currently in production.
- **Feature branches** – Contain new features being developed and tested.
- **Hotfix branches** – For urgent fixes to production issues.
- Testers need to know which branch they are testing to ensure they validate the correct code changes.

### QA and Rollbacks

- If a release causes critical issues, QA confirms the rollback resolves the problem and doesn’t introduce new ones.
- Regression checks are done on the rolled-back version to ensure stability.

---

## 📝 Reflection

### Adjusting Testing for Feature Release vs. Small Bug Fix

- **Feature Release**: Full regression testing, exploratory testing, performance checks, and UI/UX validation.
- **Small Bug Fix**: Focus on verifying the fix and running targeted regression around the affected area.

### Handling “Bug Only Happens on an Older Branch”

- Check out the older branch (if possible) or request a test build from it.
- Attempt to reproduce the issue in that branch.
- Compare behavior with the latest branch to confirm if the bug still exists.

### Why It’s Important to Know the Version Being Tested

- Prevents false bug reports caused by testing outdated or incorrect builds.
- Ensures QA feedback is relevant to the current release.
- Helps track when and where bugs were introduced.

---
