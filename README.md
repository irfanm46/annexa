# annexa ⬡
> ISO 27001:2022 toolkit for engineers. Free. Offline. No signup. No API keys. No billing.

**[🚀 Launch App](https://irfanm46.github.io/annexa)** · [Report Bug](https://github.com/irfanm46/annexa/issues) · [Request Feature](https://github.com/irfanm46/annexa/issues)

---

![ISO 27001:2022](https://img.shields.io/badge/ISO%2027001-2022%20Edition-00e5ff?style=flat-square)
![Controls](https://img.shields.io/badge/Controls-93%20Annex%20A-7c3aed?style=flat-square)
![Offline](https://img.shields.io/badge/Works-Offline-10b981?style=flat-square)
![No Signup](https://img.shields.io/badge/No-Signup%20Required-f59e0b?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-white?style=flat-square)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-00e5ff?style=flat-square)

---
 
## What is this?

Every MNC wants ISO 27001. Nobody explains it in plain English for engineers.

**annexa** is the toolkit that should have existed — built *by engineers, for engineers*. No consultant jargon. No £500/month SaaS. No Docker setup. Just open the link and go.

---

## ✨ Features:

### ▦ Compliance Heatmap
Visual grid of all 93 Annex A controls. Click to mark each as **Implemented**, **Partial**, **Gap**, or **N/A**. Your progress saves automatically in the browser. Screenshot it, share it, use it in audits.

### ◈ Controls Guide — Plain English
Every control explained in language engineers actually understand. Filter by your role:
- ⚙ DevOps Engineer
- ◈ Backend Developer  
- ◎ Security Analyst
- ▦ System Admin
- ◉ GRC / Compliance

### ◎ Risk Register
Add assets, score risks with Likelihood × Impact sliders. Auto-calculated severity (Low / Medium / High). Sorted automatically. Saved locally.

### ⇄ 2013 → 2022 Migration Diff
Side-by-side view of what changed between ISO 27001:2013 and 2022. Filter by **New** (11 controls), **Merged**, **Renamed**, **Unchanged**. Critical for teams still transitioning.

### ◉ SoA Generator *(coming v0.2)*
Auto-generate your Statement of Applicability — the mandatory certification document consultants charge thousands for.

### ⚠ Threat Mapper *(coming v0.2)*
Pick a real attack scenario → see which controls prevent it and which gaps you need to close.

### ◈ Posture Score *(coming v0.2)*
Answer 15 questions → get a radar chart of your security posture across all 4 Annex A domains.

### </> Compliance-as-Code Snippets *(coming v0.2)*
Ready-to-use Terraform, GitHub Actions, bash scripts — one per technical control.

---

## 🚀 Quick Start

**Option 1 — Just use it (recommended)**
```
https://irfanm46.github.io/annexa
```
Works in any browser. No install. No account.

**Option 2 — Run locally**
```bash
git clone https://github.com/irfanm46/annexa.git
cd annexa
# open index.html in your browser — that's it
```

**Option 3 — Self host**
Drop `index.html` anywhere. It has zero dependencies.

---

## 🔒 Privacy

```
✓ Zero data sent to any server
✓ No analytics, no tracking, no telemetry  
✓ All your data stays in your browser (localStorage)
✓ Works fully offline after first load
✓ Open source — audit it yourself
```

---

## 📋 ISO 27001:2022 — Quick Reference

| Domain | Controls | Range |
|---|---|---|
| Organizational | 37 | A.5.1 – A.5.37 |
| People | 8 | A.6.1 – A.6.8 |
| Physical | 14 | A.7.1 – A.7.14 |
| Technological | 34 | A.8.1 – A.8.34 |
| **Total** | **93** | |

**New in 2022 (11 controls):**
`A.5.7` Threat Intelligence · `A.5.23` Cloud Services · `A.5.30` ICT Continuity · `A.7.4` Physical Monitoring · `A.8.10` Data Deletion · `A.8.11` Data Masking · `A.8.12` DLP · `A.8.16` Network Monitoring · `A.8.21` Web Filtering · `A.8.28` Secure Coding · `A.8.29` Security Testing

---

## ⌨️ Keyboard Shortcuts

| Keys | Action |
|---|---|
| `g d` | Dashboard |
| `g h` | Heatmap |
| `g c` | Controls Guide |
| `g r` | Risk Register |
| `g x` | 2013→2022 Diff |
| `?` | Show all shortcuts |

---

## 🗺️ Roadmap

- [x] Compliance Heatmap (v0.1)
- [x] Controls Guide with role filter (v0.1)
- [x] Risk Register (v0.1)
- [x] 2013 → 2022 Diff Viewer (v0.1)
- [ ] Statement of Applicability (SoA) Generator (v0.2)
- [ ] Security Posture Score — radar chart (v0.2)
- [ ] Threat → Control Mapper (v0.2)
- [ ] Audit Evidence Wizard (v0.2)
- [ ] Compliance-as-Code snippets (v0.2)
- [ ] Cross-framework mapper: ISO 27001 ↔ SOC 2 ↔ NIST ↔ GDPR (v0.3)
- [ ] PWA — installable as desktop/mobile app (v0.3)
- [ ] Export everything to PDF (v0.3)

---

## 🤝 Contributing

Contributions are what make open source great. Any contributions are **hugely welcome**.

1. Fork the repo
2. Create your branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

**Ideas for contributions:**
- Add missing controls to the guide
- Add stack-specific implementation notes (AWS, GCP, Azure, K8s)
- Translate to other languages
- Add compliance-as-code snippets
- Improve the UI

---

## 📄 License

MIT — free forever. Do whatever you want with it.

---

## ⭐ Star History

If this helped you, a star means the world and helps other engineers find it. 

---

<div align="center">
  <b>Built for engineers who got handed an ISO 27001 requirement with zero guidance.</b><br>
  <sub>Free · Offline · Open Source · No Signup · No BS</sub>
</div>
