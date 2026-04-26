# Basic Security Headers

These headers help reduce common browser-based security risks.

```apache
Header set X-Content-Type-Options "nosniff"
Header set X-Frame-Options "SAMEORIGIN"
Header set Referrer-Policy "strict-origin-when-cross-origin"
Header set Permissions-Policy "geolocation=(), microphone=(), camera=()"
```

---

## Purpose

These headers help:

- Reduce clickjacking risks
- Reduce browser MIME sniffing issues
- Limit unnecessary browser permissions
- Improve privacy
