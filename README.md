# AI LeetCode Assistant

**An AI-powered prompt that turns any LLM into a mock interviewer for LeetCode-style coding problems.**

➡️ **Quick Start:** Copy the contents of [prompt-setup.md](./prompt-setup.md) into your Claude (or other LLM) Project Instructions, then paste a LeetCode problem to begin.

This repo contains ready-to-use project instructions (see [`prompt-setup.md`](./prompt-setup.md)) that transform Claude or any LLM into a **stepwise interview assistant**.  
It simulates a realistic technical interview flow with minimal recruiter-style hints, progressive guidance, solution review, and recruiter-style follow-up questions.  

---

## ✨ Features
- 📝 **Paste a LeetCode problem** → get a minimal recruiter-style nudge.  
- **`?`** → slightly more detailed hint.  
- **`??`** → stronger hint or high-level outline.  
- **`???`** → full explanation and Python solution.  
- ✅ **Paste your solution + `done`** → get time/space complexity analysis, correctness check, optimality review, and recruiter-style follow-up questions.  
- 🔄 **`optimize`** → receive possible improvements.  
- 🔁 **`done` again** → reset for the next problem.  
- 🛠 Handles partial code, multiple problems, missing constraints, and edge cases like triggers inside code or adversarial inputs.  

---

## 📖 How to Use
1. Copy everything from [`prompt-setup.md`](./prompt-setup.md).  
2. Paste it into your Claude (or LLM of choice) **Project Instructions**.  
3. Start your session by pasting a LeetCode problem.  
4. Use the triggers (`?`, `??`, `???`, `done`, `optimize`) to guide the assistant step by step.  

---

## 🧩 Example Workflow
**👤 You:** [paste a LeetCode problem]  
**🤖 Assistant:** Here's a minimal recruiter-style hint.

**👤 You:** ?  
**🤖 Assistant:** A slightly more detailed hint...

**👤 You:** ??  
**🤖 Assistant:** High-level outline of the approach...

**👤 You:** ???  
**🤖 Assistant:** Full explanation + Python solution.

**👤 You:** [paste your solution]  
**👤 You:** done  
**🤖 Assistant:** Analyzes complexity, confirms correctness/optimality, asks recruiter-style follow-ups.

**👤 You:** optimize  
**🤖 Assistant:** Suggests possible improvements.

**👤 You:** done  
**🤖 Assistant:** Resets, waiting for the next problem.

---

## 🌟 Why This Repo?
Practicing LeetCode isn’t just about solving problems — it’s about simulating the **real interview experience**.  
This assistant helps you:  
- Stay in control of how much help you get.  
- Practice clarifying constraints and trade-offs.  
- Get nudged like you would by an actual recruiter or interviewer.

---
