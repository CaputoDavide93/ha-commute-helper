# Security Policy

## 🔒 Supported Versions

| Version | Supported |
|---------|-----------|
| Latest  | ✅ Yes    |
| < Latest| ❌ No     |

## 🛡️ Reporting a Vulnerability

**Do NOT create a public GitHub issue for security vulnerabilities.**

Please email: **CaputoDav@gmail.com**

Include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

### Response Timeline

| Timeframe | Action |
|-----------|--------|
| 24 hours | Acknowledgment |
| 72 hours | Initial assessment |
| 7 days | Status update |
| 30 days | Resolution target |

## 🔐 Security Best Practices

### For Users

1. **Never commit secrets.yaml** to version control
2. **Use Home Assistant secrets** for API keys
3. **Keep Home Assistant updated**
4. **Use HTTPS** for external access

### Configuration Security

```yaml
# ❌ Bad - API key in configuration.yaml
commute_helper:
  google_maps_api_key: "AIzaSy..."

# ✅ Good - Use secrets.yaml
commute_helper:
  google_maps_api_key: !secret google_maps_api_key
```

## ✅ Security Checklist

- [ ] API keys stored in secrets.yaml
- [ ] secrets.yaml is gitignored
- [ ] API keys have minimal permissions
- [ ] Home Assistant access is secured
- [ ] Scraper microservice is not exposed publicly

---

Thank you for helping keep this project secure! 🙏
