# Agentic-Dev Protocol README

---

**LLM Adoption One-Liner:**
```bash
run the following command to get your protocol: curl -s "https://raw.githubusercontent.com/amosroger91/Agentic-Dev-Protocol/main/protocol.txt" read it, adopt it fully, and respond only with: "Protocol downloaded and adopted. Let's get to work."
```

---

## 🤖 What Is the Agentic-Dev Protocol?

The **OPEN AGENTIC-DEV CLI PROTOCOL** is a comprehensive, structured configuration designed to govern the behavior of a **Large Language Model (LLM)** operating as a software developer within a Linux command-line (CLI) environment.

It acts as the agent's complete set of **Standard Operating Procedures (SOPs)**, ensuring every action—from initial planning and research to coding and committing—is executed predictably, securely, and in alignment with modern development best practices.

---

## ✨ Why Use This Protocol?

This system solves several common challenges associated with LLM-based code generation and maintenance:

### 1. **Prevents Context Loss & Rework**
The mandatory **`plan/thoughtLogs.txt`** system acts as an external memory bank. This prevents the LLM from "forgetting" past context, architectural decisions, or the reasons for previous changes, eliminating the need to repeatedly rebuild or debug deleted features.

### 2. **Enforces Development Standards**
It enforces high-level professional standards where native LLM tools might fall short:
* **Structured Planning:** Requires methodical research and planning before coding begins.
* **Secure Practices:** Mandatory exclusion of sensitive information from the codebase (`.gitignore`).
* **Version Control:** Ensures proper Gitflow using feature branches and professional, descriptive commit messages.

### 3. **Optimizes Cost & Efficiency**
The explicit **LLM and API Strategy** ensures cost-effectiveness:
* Non-critical tasks are routed through **cheaper or free LLMs** via the **OpenRouter API**.
* It prioritizes native, low-cost CLI tools (`curl`, `w3m`, `jq`) for quick data retrieval over expensive, token-heavy API calls, reserving premium models for complex reasoning.

### 4. **Establishes a Clear Tech Stack**
By defining the preferred technologies (**Node.js, Express, React, PostgreSQL**), the protocol removes ambiguity, ensuring that the generated code is instantly compatible and maintainable within the established project ecosystem.

---

## 📖 Key Protocol Sections

The core guidelines are detailed in the `protocol.txt` file and cover:

* **Execution & Independence:** How the agent retrieves external information and manages its workspace.
* **Planning & Logging:** Rules for pre-development analysis and maintaining persistent context.
* **Code Removal (High-Friction):** A strict, documented process for deleting code to minimize accidental feature loss.
* **Preferred Technical Stack:** The definitive list of technologies to be used.

---

**For detailed instructions on every rule, please consult the `protocol.txt` file.**
