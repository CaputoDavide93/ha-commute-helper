# Contributing to HA Commute Helper

Thank you for your interest in contributing! 🎉

## 🚀 Quick Start

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/YOUR_USERNAME/HA_Commute_Helper.git`
3. **Create** a branch: `git checkout -b feature/your-feature`
4. **Make** your changes
5. **Test** in Home Assistant
6. **Commit**: `git commit -m 'Add feature'`
7. **Push**: `git push origin feature/your-feature`
8. **Open** a Pull Request

## 📋 Guidelines

### Code Style

- Follow [Home Assistant development guidelines](https://developers.home-assistant.io/)
- Use type hints for all functions
- Follow PEP 8 style guide
- Use meaningful variable names

### Testing

Before submitting:

```bash
# Install dev dependencies
pip install -r requirements_dev.txt

# Run linting
pylint custom_components/commute_helper

# Run type checking
mypy custom_components/commute_helper

# Test in HA development container
hass -c config/
```

### Commit Messages

```
type(scope): description

[optional body]
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

## 🐛 Bug Reports

Please include:
- Home Assistant version
- Integration version
- Configuration excerpt
- Error logs from `home-assistant.log`
- Steps to reproduce

## 💡 Feature Requests

Open an issue with:
- Clear description
- Use case
- Expected behavior
- Mockups (if applicable)

## 📝 Pull Request Process

1. Update documentation if needed
2. Update manifest.json version
3. Ensure all checks pass
4. Request review from maintainers

---

Thank you for contributing! 🙏
