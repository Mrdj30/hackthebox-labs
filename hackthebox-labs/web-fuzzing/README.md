# 🔍 Web Fuzzing

> [← Back to modules](../README.md)

[![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)](.)
[![Topics](https://img.shields.io/badge/Topics-7%2F7-brightgreen?style=flat-square)](.)
[![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow?style=flat-square)](.)
[![Tools](https://img.shields.io/badge/Tools-ffuf%20%7C%20gobuster%20%7C%20feroxbuster-blue?style=flat-square)](.)

Web fuzzing is the process of sending automated, modified inputs to a web application to discover hidden content, parameters, endpoints, and vulnerabilities.

---

## 📋 Topics

| # | Topic | Flag / Answer | Status |
|---|-------|--------------|--------|
| 1 | [Recursive Fuzzing](./01-recursive-fuzzing/) | `HTB{d33p3r_d1rector1es_ar3_c00l}` | ✅ Solved |
| 2 | [Parameter and Value Fuzzing](./02-parameter-value-fuzzing/) | GET + POST flags found | ✅ Solved |
| 3 | [Virtual Host and Subdomain Fuzzing](./03-vhost-subdomain-fuzzing/) | vhost + subdomain found | ✅ Solved |
| 4 | [Filtering Fuzzing Output](./04-filtering-fuzzing-output/) | POST flag confirmed | ✅ Solved |
| 5 | [Validating Findings](./05-validating-findings/) | Content-Length confirmed | ✅ Solved |
| 6 | [API Fuzzing](./06-api-fuzzing/) | Endpoint + flag found | ✅ Solved |
| 7 | [Skill Assessment](./07-skill-assessment/) | Flag via chained fuzzing | ✅ Solved |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| `ffuf` | Fast URL/parameter fuzzing |
| `gobuster` | Directory, VHost, DNS fuzzing |
| `feroxbuster` | Recursive directory scanning |
| `curl` | Manual request/validation |
| `webfuzz_api` | API endpoint discovery |

---

## 💡 Key Takeaways

- Recursive fuzzing reveals directories hidden deep inside nested paths
- Parameter fuzzing exposes hidden GET/POST parameters attackers can manipulate
- VHost/subdomain fuzzing uncovers virtual hosts not visible in standard DNS
- Filtering output by status codes and content-length cuts noise dramatically
- Chaining techniques — recursion → parameter → subdomain → deep scan — mirrors real-world enumeration

---

## ⏱️ Estimated Time

**3–5 hours** to complete all 7 topics from scratch.
