# Test-Driven Development Demo

This is a **minimal example** of Test-Driven Development (TDD) using Node.js and Jest.

We'll build a single function, `add(a, b)`, step-by-step **the TDD way**:
1. Write a **failing test**.
2. Write just enough code to **make it pass**.
3. **Refactor** the code while keeping tests green.

---

## Setup

You only need Node.js installed.

```bash
git clone https://github.com/YOUR_USERNAME/tdd-demo.git
cd tdd-demo
npm init -y
npm install --save-dev jest