# Public Lottery Draw (Jan 2026)

This repository hosts a fully transparent and automated lottery draw.

### 📅 Schedule
- **Time**: January 1, 2026, 20:00 (UTC+8)
- **Pool**: Numbers 1 to 300
- **Winners**: 10 participants

### 🛡️ How it works (Fairness Guaranteed)
1. **Automation**: The draw is triggered automatically by GitHub Actions (see `.github/workflows/`).
2. **Transparency**: The randomness is generated using the standard Linux `shuf` utility.
3. **Immutability**: Once the draw is complete, a `done` file is created to lock the process, preventing any re-runs or tampering with the results.
4. **Public Record**: All results, including the execution timestamp and Run ID, will be permanently committed to the `results/` folder.

---

### 👤 Contact & Support
- **Created By**: ifeng
- **Web Site**: [https://www.hicairo.com](https://www.hicairo.com)
- **Telegram**: [https://t.me/HiaiFeng](https://t.me/HiaiFeng)

---
*Verified by GitHub Actions Automation*
