# Hi, I'm Ibrar 👋

Senior embedded software engineer working on MISRA and AUTOSAR code review for safety-critical C/C++ teams. Currently building **[Firmlint](https://firmlint.com)**.

🌐 [firmlint.com](https://firmlint.com) · 📧 hello@firmlint.com

---

## 🔍 Firmlint (MISRA Assistant)

A static-analysis tool for **MISRA C:2012**, **MISRA C++:2023** and **AUTOSAR C++14** code, with AI explanations that are verified rather than trusted.

- **Analysis:** cppcheck and clang-tidy run locally and report findings in SARIF, HTML and JSON.
- **Explanations:** a local LLM (Ollama by default) explains each finding and proposes a fix.
- **Verification:** each proposed fix is applied to a copy of the file, re-analysed and compile-checked. Only fixes that pass are marked **verified**. The rest are marked **not verified** for human review.
- **Distribution:** Docker image, no cloud account required. Integrates with GitLab CI, GitHub Actions and Jenkins.

```bash
docker pull ghcr.io/ibrarmohammed1137/misra-assistant:latest
```

📦 [Container package](https://github.com/users/ibrarmohammed1137/packages/container/package/misra-assistant) (GitHub login required)

## Tech stack

Python · C · C++ · FastAPI · Docker · GitHub Actions · GitLab CI · Ollama · cppcheck · clang-tidy · SARIF

**Standards:** MISRA C:2012 · MISRA C++:2023 · AUTOSAR C++14 · CERT C · CWE Top 25

## Other projects

- [firmlint-site](https://github.com/ibrarmohammed1137/firmlint-site): Firmlint landing page
- [ai-can-analyzer](https://github.com/ibrarmohammed1137/ai-can-analyzer): CAN message analyzer for detecting defects (C++)

## Contact

- Email: hello@firmlint.com
- LinkedIn: [add your profile URL]

I'm interested in conversations with engineering managers and functional safety leads about MISRA review, static analysis and AI in safety-critical workflows.
