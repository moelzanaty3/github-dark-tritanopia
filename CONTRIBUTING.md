# Contributing to GitHub Dark Tritanopia

Thank you for considering contributing to GitHub Dark Tritanopia! We're excited to have you help improve this theme.

## 📋 Code of Conduct

Be respectful, inclusive, and constructive in all interactions. We're building a welcoming community for developers of all backgrounds.

## 🐛 Reporting Issues

Found a color that doesn't look right or a feature that's missing? We'd love to hear about it!

### Before Submitting an Issue
1. Check the [existing issues](https://github.com/moelzanaty3/github-dark-tritanopia/issues) to avoid duplicates
2. Ensure the issue is related to the theme colors or VS Code/Cursor compatibility
3. Gather relevant information:
   - Your editor (VS Code or Cursor) version
   - Operating system
   - Screenshot of the issue
   - File type/language being edited

### Issue Template
```
**Description:**
Brief description of the issue

**Steps to Reproduce:**
1. Step one
2. Step two
3. ...

**Expected Behavior:**
What should happen

**Actual Behavior:**
What actually happens

**Environment:**
- Editor: VS Code / Cursor
- Version: X.X.X
- OS: macOS / Windows / Linux
```

## 💡 Suggesting Enhancements

Have an idea to improve the theme? We'd love to hear it!

### Enhancement Suggestions Should Include
- Clear description of the improvement
- Rationale for why this would benefit users
- Proposed color hex values (if color-related)
- Visual mockup or example if applicable

## 🎨 Color Contributions

### Guidelines for Color Modifications

1. **Accessibility First**
   - All color combinations must maintain WCAG AA contrast ratios
   - Test with tritanopia color vision deficiency in mind
   - Use accessibility testing tools

2. **Consistency**
   - Follow the existing color palette structure
   - Ensure colors work across light and dark backgrounds
   - Match GitHub's design language where possible

3. **Testing**
   - Test syntax highlighting across multiple file types
   - Verify UI elements render correctly
   - Check contrast in both default and high-DPI displays

### Adding Colors

1. Locate the relevant section in `themes/github-dark-tritanopia-color-theme.json`
2. Add your color definition following the existing format
3. Test thoroughly with real code files
4. Submit a pull request with a clear description

## 🔧 Development Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Git

### Local Setup
```bash
# Clone the repository
git clone https://github.com/moelzanaty3/github-dark-tritanopia.git
cd github-dark-tritanopia

# Install dependencies (if any)
npm install

# Open in VS Code for testing
code .
```

### Testing Your Changes

1. Open the project folder in VS Code/Cursor
2. Press `F5` to launch the Extension Development Host
3. Open a file and select the theme to test
4. Test across different file types (JS, TS, Python, etc.)
5. Verify all UI elements display correctly

## 📝 Submitting Changes

### Before Submitting a Pull Request
1. Create a feature branch: `git checkout -b feature/your-feature-name`
2. Make your changes
3. Test thoroughly
4. Update documentation if needed
5. Commit with clear, descriptive messages

### PR Description Template
```markdown
## Description
Brief description of what this PR accomplishes

## Changes
- Change 1
- Change 2
- Change 3

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Color improvement
- [ ] Documentation update

## Testing
How you tested the changes

## Screenshots (if applicable)
Before and after screenshots

## Related Issues
Closes #XXX
```

## 📚 File Structure

```
github-dark-tritanopia/
├── themes/
│   └── github-dark-tritanopia-color-theme.json  # Main theme file
├── package.json                                  # Extension metadata
├── README.md                                     # User documentation
├── CHANGELOG.md                                  # Version history
└── CONTRIBUTING.md                              # This file
```

## 🎯 Priority Areas for Contributions

- **Language Support**: Improving syntax highlighting for specific languages
- **Accessibility**: Testing and refining colors for various color vision deficiencies
- **Documentation**: Improving guides and examples
- **Bug Reports**: Identifying and documenting issues
- **User Feedback**: Sharing experiences and suggestions

## 🚀 Release Process

We follow semantic versioning. Contributors don't need to worry about version numbers—maintainers handle releases.

**Version Format:** `MAJOR.MINOR.PATCH`
- `MAJOR`: Breaking changes
- `MINOR`: New features
- `PATCH`: Bug fixes

## 📞 Getting Help

- Check existing documentation and issues first
- Feel free to ask questions in pull requests
- Connect with maintainers for complex contributions

## ✅ Contribution Checklist

Before submitting your PR, ensure:
- [ ] Changes follow the existing code style
- [ ] All colors tested for accessibility
- [ ] Documentation updated (if applicable)
- [ ] No duplicate functionality
- [ ] Changes tested in both VS Code and Cursor
- [ ] Descriptive commit messages used
- [ ] No merge conflicts with the main branch

## 🙏 Thank You

Your contributions make GitHub Dark Tritanopia better for everyone. We genuinely appreciate your effort and dedication to improving this project!

---

**Questions?** Feel free to open an issue or reach out to the maintainers. Happy contributing! 🎉
