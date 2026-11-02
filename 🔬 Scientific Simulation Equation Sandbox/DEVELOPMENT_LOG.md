This a journal book for the project from explaining things to myself clearly providing understanding

GITHUB COMMANDS


The Anti-Copy-Paste Strategy: How We Use AI Productively

When you want to know how a system works deeply enough to explain it to both a 5-year-old and a Senior Dev, you shouldn't ask an AI to write it. Instead, you change your prompts. Use these types of requests whenever you feel stuck:
• "Explain this concept to a 5-year-old / Senior Dev": Asking for twin explanations forces you to learn both the conceptual analogy (the 5-year-old view) and the underlying systems design (the Senior Dev view).
• "Give me a pseudo-code logic breakdown": Ask for human-language logic patterns or step-by-step blueprints rather than functional code.
• "What are the trade-offs of using X over Y?": This trains your architectural brain—perfect for a future backend master.
• "Review my architectural structure": You paste a package outline or workflow


LEARING NEW THINGS:
In Java desktop development, we use the Model-View-Controller (MVC) architectural pattern to handle this:
• The Model (Your Backend Engine): This handles the pure math, simulation math loops, data arrays, and files. It has absolutely no idea that a GUI or buttons exist. It could run perfectly as a silent text terminal program.
• The View (Your Swing GUI Layout): This builds the JFrame, JTabbedPane, and buttons. It only cares about visual spacing, colors, and layout management. It doesn't perform calculations.
• The Controller (The Bridge): This connects the two. When someone moves a speed slider in your View, the Controller intercepts that interaction and updates the variable inside the Model.

--------------------------------------------------------------------------------------------------------------------------------
# 📓 Engineering & Problem-Solving Log

## [Date: 2026-11-02] - Architectural Foundations

### 🎯 Today's Goal
Establish the project mindset, file boundaries, and directory layout for the Scientific Simulation Sandbox.

### 🧠 System Concepts Explored
- **Model-View-Controller (MVC):** Isolating calculations from visual windows.
- **Separation of Concerns:** Ensuring the layout files don't handle logic.

### 🚧 Struggles & Questions
- *How will I pass equation inputs from the UI panel to the parser without tangling the code?*
- *Should the simulation loop run on a separate background thread to keep the window responsive?*

### 💡 Core Discovery / Technical Insight
AI is a design partner, not a typewriter. To truly own this code, I am focusing on logic design over code generation.
