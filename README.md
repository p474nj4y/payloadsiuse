# 🛡️ XSS WAF Bypass Payload Collection

A curated collection of **URL-encoded Cross-Site Scripting (XSS) payloads** intended for **authorized security testing**, WAF evaluation, and web application security research.

> ⚠️ **Disclaimer:** This repository is intended **only for legal penetration testing, security research, and educational purposes** on systems you own or are explicitly authorized to test

---

## 📖 Overview

Modern Web Application Firewalls (WAFs) often rely on pattern matching and signature-based detection. This repository provides a collection of encoded payloads that can be useful for evaluating how applications and defensive controls handle different forms of user input.

The payloads include variations using:

- URL encoding
- Mixed-case keywords
- HTML tag variations
- Event handler injection
- SVG-based payloads
- Image-based payloads
- iframe/object/embed contexts
- Data URI techniques
- Unicode and escape sequence encoding
- Attribute injection
- JavaScript URI variations
- CSS-based payloads 
- Legacy browser payloads
- Browser parsing edge cases

---

## 📂 Repository Structure

```text
.
├── xssWAFbypass.txt
└── README.md
```

---

## 🚀 Usage

Use the payload list during **authorized web application security assessments**.

Example workflow:

1. Identify reflected input.
2. Determine the injection context (HTML, attribute, JavaScript, URL, etc.).
3. Test appropriate payloads from the collection.
4. Observe how the application and any WAF respond.
5. Document successful and blocked cases.

---

## 🎯 Intended Use Cases

- Penetration Testing
- Bug Bounty Research
- Security Training Labs
- WAF Validation
- Secure Development Testing
- Capture The Flag (CTF) Practice

---

## 📊 Payload Categories

The collection contains payloads covering numerous contexts, including:

| Category | Description |
|----------|-------------|
| URL Encoded | Percent-encoded payloads |
| HTML Injection | HTML tag-based testing |
| Attribute Injection | Attribute escape testing |
| Event Handlers | Event-driven payload variants |
| SVG | SVG element testing |
| Image Tags | Image-based contexts |
| iframe | Embedded document contexts |
| JavaScript URIs | `javascript:` scheme variants |
| Data URIs | Data URI testing |
| CSS | Style and CSS-related vectors |
| Unicode | Unicode and encoded character variants |
| Browser Edge Cases | Browser parsing behaviors |

---

## 💡 Best Practices

- Test in a controlled environment.
- Confirm the injection context before selecting payloads.
- Record blocked vs. successful payloads.
- Verify findings manually.
- Follow responsible disclosure practices when reporting vulnerabilities.

---

## ⚠️ Legal Notice

This repository **must not** be used against systems without prior authorization.

The author assumes **no responsibility** for misuse or illegal activities involving these payloads.

---

## 🤝 Contributing

Contributions are welcome.

If you have additional payloads, improvements, or categorization suggestions, feel free to open an issue or submit a pull request.

---

## ⭐ Support

If this repository is useful for your security research or learning, consider giving it a ⭐.

---

## 📜 License

This project is licensed under the MIT License.
