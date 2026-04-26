# Basic Rate Limiting

Rate limiting helps reduce brute force login attempts.

---

## Common Targets

```txt
/wp-login.php
/admin/
login pages
account pages
API endpoints
```

---

## Example Rule Idea

```txt
If requests exceed threshold:
Temporarily block or challenge visitor
```

---

## Good Uses

- Login protection
- API abuse prevention
- Bot reduction
- Form spam reduction
