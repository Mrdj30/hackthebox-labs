# 🔍 Web Fuzzing

> [← Back to main](../README.md)

Web fuzzing is the process of sending automated, modified inputs to a web application to discover hidden content, parameters, endpoints, and vulnerabilities.

---

## 📋 Topics

| # | Topic | Flag / Answer | Status |
|---|-------|--------------|--------|
| 1 | [Recursive Fuzzing](./01-recursive-fuzzing/) | `HTB{d33p3r_d1rector1es_ar3_c00l}` | ✅ Solved |
| 2 | [Parameter and Value Fuzzing](./02-parameter-value-fuzzing/) | GET + POST flags found | ✅ Solved |
| 3 | [Virtual Host and Subdomain Fuzzing](./03-vhost-subdomain-fuzzing/) | vhost + subdomain found | ✅ Solved |
| 4 | [Filtering Fuzzing Output](./04-filtering-fuzzing-output/) | POST flag confirmed | ✅ Solved |
| 5 | [Validating Findings](./05-validating-findings/) | `Content-Length` confirmed | ✅ Solved |
| 6 | [API Fuzzing](./06-api-fuzzing/) | Endpoint + flag found | ✅ Solved |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| `ffuf` | Fast URL/parameter fuzzing |
| `gobuster` | Directory, VHost, DNS fuzzing |
| `curl` | Manual request/validation |
| `webfuzz_api` | API endpoint discovery |
