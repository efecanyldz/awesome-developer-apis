# Contributing to Awesome Developer APIs

First off, thank you for considering contributing to this project! 🎉

It's people like you that make this such a great resource for the developer community.

## 📋 Table of Contents

- [How Can I Contribute?](#how-can-i-contribute)
- [Submission Guidelines](#submission-guidelines)
- [Quality Standards](#quality-standards)
- [Style Guide](#style-guide)
- [Code of Conduct](#code-of-conduct)

---

## How Can I Contribute?

### 🆕 Adding New APIs

1. **Fork** the repository
2. **Create** a new branch: `git checkout -b add-api-name`
3. **Add** your API to the appropriate category in README.md
4. **Commit** your changes: `git commit -m "Add [API Name] to [Category]"`
5. **Push** to your fork: `git push origin add-api-name`
6. **Submit** a Pull Request with a clear description

### 📝 Improving Documentation

- Fix typos or broken links
- Improve descriptions
- Update outdated information
- Add missing details

### 🗂️ Suggesting Categories

If you think a new category is needed:
1. Open an issue with the category name
2. Provide at least 3-5 quality APIs that fit the category
3. Explain why this category adds value

### 🐛 Reporting Issues

- Broken links
- Outdated information
- Duplicate entries
- Incorrect categorization

---

## Submission Guidelines

### Required Format

```markdown
| [API Name](https://api-website.com) | Clear, concise description | `authType` | ✅ | Status |
```

### Field Requirements

| Field | Description | Examples |
|-------|-------------|----------|
| **Name** | Official API name (linked to homepage/docs) | `[Stripe API](https://stripe.com/docs/api)` |
| **Description** | One-line description (max 80 characters) | `Payment processing and financial operations` |
| **Auth** | Authentication type | `apiKey`, `OAuth`, `None` |
| **HTTPS** | Always ✅ (we only accept HTTPS APIs) | ✅ |
| **Free** | Pricing model | ✅ Free, 💰 Paid, 🆓 Freemium |

### Example Entry

```markdown
| [OpenWeatherMap](https://openweathermap.org/api) | Current weather, forecasts, and historical data | `apiKey` | ✅ | 🆓 Freemium |
```

---

## Quality Standards

### ✅ An API Should Be Included If:

- **Active**: Updated or maintained within the last 12 months
- **Documented**: Has clear, accessible documentation
- **Stable**: Production-ready and reliable
- **Accessible**: Available for developers to use
- **Secure**: Uses HTTPS (HTTP-only APIs will not be accepted)
- **Unique**: Not a duplicate of an existing entry

### ❌ An API Should NOT Be Included If:

- Requires company-specific approval or partnership
- Has broken or incomplete documentation
- Is deprecated or no longer maintained
- Uses HTTP instead of HTTPS
- Is a duplicate of an existing entry
- Promotes illegal activities or harmful content

---

## Style Guide

### Alphabetical Order

Within each category, APIs should be listed alphabetically by name.

### Description Style

- Use active voice: "Retrieve stock data" not "Stock data retrieval"
- Be concise: 80 characters or less
- Don't include "API" in the description (it's redundant)
- Start with a verb when possible

#### Good Examples ✅
- `Payment processing and financial operations`
- `Retrieve real-time weather forecasts`
- `Access NBA statistics and live scores`

#### Bad Examples ❌
- `This API allows you to get weather data` (too wordy)
- `Weather` (too vague)
- `The best weather API for developers` (promotional)

### Authentication Types

Use these standardized values:
- `apiKey` - Requires an API key
- `OAuth` - Uses OAuth authentication
- `None` - No authentication required

### Pricing Indicators

- ✅ **Free** - Completely free to use
- 💰 **Paid** - Requires payment
- 🆓 **Freemium** - Has both free and paid tiers

---

## Code of Conduct

### Our Standards

**Positive Behavior:**
- Being respectful and inclusive
- Welcoming newcomers
- Providing constructive feedback
- Focusing on what's best for the community
- Showing empathy towards others

**Unacceptable Behavior:**
- Harassment or discriminatory language
- Trolling or insulting comments
- Spam or promotional content
- Publishing others' private information
- Any conduct that would be inappropriate professionally

### Enforcement

Violations may result in:
1. Warning
2. Temporary ban from contributing
3. Permanent ban

Report issues to the maintainers via GitHub issues.

---

## Review Process

### Timeline

- Pull requests are reviewed within **5-7 business days**
- Simple additions are usually merged within 1-2 days
- Complex changes may require discussion

### What We Look For

1. **Format**: Does it follow the required format?
2. **Quality**: Does the API meet our quality standards?
3. **Category**: Is it in the right category?
4. **Uniqueness**: Is it already listed?
5. **Working**: Are all links functional?

### Approval Criteria

✅ **Approved** if:
- Meets all quality standards
- Follows the style guide
- Is properly formatted
- Adds value to the list

❌ **Changes Requested** if:
- Minor formatting issues
- Needs better description
- Link issues

❌ **Closed** if:
- Doesn't meet quality standards
- Duplicate entry
- Inappropriate content
- No response to requested changes after 14 days

---

## Recognition

All contributors are recognized:
- ✨ Listed in the README contributors section
- 🏆 Featured in the GitHub contributors graph
- 📢 Mentioned in release notes (for significant contributions)

---

## Questions?

- 💬 Open an issue for questions
- 📧 Contact maintainers for sensitive matters
- 📖 Check existing issues before creating new ones

---

## Getting Started Checklist

- [ ] I've read the contributing guidelines
- [ ] I've checked for duplicate entries
- [ ] My API meets the quality standards
- [ ] I've followed the required format
- [ ] All links work correctly
- [ ] The description is clear and concise
- [ ] I've placed it in the correct category

---

Thank you for contributing! Every addition helps developers discover great APIs. 🚀

**Happy Contributing!** 🎉