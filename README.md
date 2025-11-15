# Redefining-QA-Multi-Agent-AI-Automation-Using-MCP-Protocol
This project demonstrates how to build a multi-agent AI automation framework using the Model Context Protocol (MCP). The setup enables LLMs (Claude AI in this case) to autonomously execute UI flows, API validations, file operations, and cross-system authentication workflows through standardized tool interfaces

## **Key Features**

* **Multi-Agent System:**

  * **Web Automation Agent** – Automates browser workflows using Playwright via MCP servers.
  * **API & File System Agent** – Executes API tests and interacts with local data.
  * **Excel Agent** – Reads and writes Excel files for scenario-driven data management.

* **End-to-End Test Scenarios:**

  1. **Registration Validation Workflow** – Ensures proper validation for empty/invalid registration.
  2. **Full Registration + Authentication (UI & API)** – Validates dual authentication flows and persists credentials.
  3. **Password Recovery & Cross-Channel Authentication** – Automates password reset and re-authentication via UI and API.

* **Comprehensive Reporting:**

  * Test summary dashboards
  * Detailed execution reports
  * Test artifacts
  * Test coverage analysis and matrix
  * Key observations

* **Agentic AI Orchestration:**

  * Coordinated multi-agent workflow using Claude AI as the client
  * Intelligent prompt-driven execution
  * Seamless synchronization across UI, API, and file systems

---

## **Getting Started**

### **Prerequisites**

* Python 3.10+
* Node.js (for Playwright)
* Claude AI client access
* MCP servers configured

### **Installation**

1. Clone the repository:

```bash
git clone https://github.com/sarthak1095/Redefining-QA-Multi-Agent-AI-Automation-Using-MCP-Protocol.git
```

2. Navigate to the project directory:

```bash
cd Redefining-QA-Multi-Agent-AI-Automation-Using-MCP-Protocol
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Configure `config.json` with MCP server endpoints and credentials.

---

## **Usage**

1. Run the multi-agent test workflow:

```bash
python run_tests.py
```

2. View the **consolidated test execution report** in Markdown/HTML format.
3. Check **Excel outputs** under `newdata.xlsx` for test data results.

---

## **Test Scenarios & Outcomes**

1. **Empty Registration Validation:** All field-level validations triggered successfully.
2. **Full Registration + Authentication:** UI and API login flows validated, credentials persisted to Excel.
3. **Password Recovery & Reauthentication:** End-to-end password reset validated across UI and API, logout verified.

✅ **Overall Status:** All scenarios passed (100% success rate)

---

## **Contributing**

Contributions are welcome! Please create an issue or pull request for bug fixes, improvements, or new test scenarios.

---

## **References**

* Learn Agentic AI – Build Multi-Agent Automation Workflows by Rahul Shetty
* MCP Protocol Documentation – Anthropic
