# Basic Cloudflare Firewall Rules

Common defensive firewall ideas for websites.

---

## Protect Admin Pages

```txt
/admin/*
/wp-admin/*
```

Add challenge or restrict access.

---

## Protect Login Pages

```txt
/wp-login.php
/login
```

Use rate limiting or bot protection.

---

## Protect API Endpoints

```txt
/api/*
```

Rate limit where appropriate.

---

## Block Bad Traffic Patterns

- Excessive requests
- Known bad bots
- Suspicious traffic spikes
