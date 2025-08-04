# Contributing to Retro Synth Dark

Thanks for your interest in contributing to **Retro Synth Dark**! 🎮 We welcome contributions from the cyberpunk coding community.

## 🚀 Quick Start

1. **Fork** the repository on GitHub
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/retro-synth-dark.git
   cd retro-synth-dark
   ```
3. **Install** dependencies:
   ```bash
   npm install
   ```
4. **Test** the extension:
   - Open the project in VS Code
   - Press `F5` to launch a new Extension Development Host window
   - Test your changes in the development window

## 🎨 Theme Development

### Theme File Structure
The main theme file is located at `themes/retro-synth-dark.json`. This contains all the color definitions for:
- Editor colors (syntax highlighting)
- Workbench colors (UI elements)
- Terminal colors
- Git integration colors

### Color Guidelines
- **Neon Colors**: Use electric purples, cyans, and magentas
- **High Contrast**: Ensure readability with sufficient contrast ratios
- **Consistency**: Follow the existing color palette and naming conventions
- **Accessibility**: Test with color blindness simulators when possible

### Testing Your Changes
1. Make changes to `themes/retro-synth-dark.json`
2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P`) in the development window
3. Select "Developer: Reload Window" to see your changes
4. Test across different file types (JS, Python, HTML, etc.)

## 🔧 Development Scripts

```bash
# Lint all files
npm run lint

# Validate extension manifest
npm run lint:manifest

# Build VSIX package
npm run package

# Prepare a release (local)
npm run release patch|minor|major
```

## 📝 Making Changes

### 1. Create a Branch
```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/issue-description
```

### 2. Make Your Changes
- **Theme colors**: Edit `themes/retro-synth-dark.json`
- **Documentation**: Update `README.md`, `CHANGELOG.md`, etc.
- **Scripts**: Modify files in the `scripts/` directory
- **Workflows**: Update `.github/workflows/` files

### 3. Test Thoroughly
- Test the theme with multiple programming languages
- Ensure all UI elements look correct
- Verify no colors are broken or missing
- Run `npm run lint` to catch any issues

### 4. Commit Your Changes
```bash
git add .
git commit -m "feat: add neon blue accent for active tabs"
# or
git commit -m "fix: improve contrast for warning messages"
```

**Commit Message Format:**
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation changes
- `style:` for formatting/style changes
- `refactor:` for code refactoring
- `test:` for adding tests
- `chore:` for maintenance tasks

### 5. Push and Create PR
```bash
git push origin feature/your-feature-name
```
Then create a Pull Request on GitHub with:
- Clear description of changes
- Screenshots (for visual changes)
- Testing notes

## 🐛 Reporting Issues

**Before creating an issue:**
1. Check existing issues to avoid duplicates
2. Test with the latest version
3. Disable other themes/extensions to isolate the issue

**Include in your issue:**
- VS Code version
- Operating system
- Theme version
- Steps to reproduce
- Screenshots (if relevant)

## 💡 Feature Requests

We love new ideas! When suggesting features:
- Explain the use case
- Provide mockups or examples if possible
- Consider how it fits with the synthwave/cyberpunk aesthetic
- Check if it's technically feasible with VS Code's theming APIs

## 🎯 Areas for Contribution

### High Priority
- **Color refinements** for better readability
- **New language support** (syntax highlighting)
- **Accessibility improvements**
- **Documentation enhancements**

### Medium Priority
- **Performance optimizations**
- **Additional theme variants** (light mode, different color schemes)
- **Integration improvements** (better Git colors, etc.)

### Nice to Have
- **Community showcases** (user setups, screenshots)
- **Tool integrations** (terminal themes, etc.)
- **Educational content** (theme development tutorials)

## 📋 Code Standards

- **JSON formatting**: Use 2-space indentation for theme files
- **Comments**: Add comments for complex color choices
- **Testing**: Ensure changes work across major file types
- **Documentation**: Update relevant docs for significant changes

## 🏆 Recognition

Contributors will be:
- Listed in release notes for significant contributions
- Mentioned in the README contributors section
- Invited to the Discord VIP channel (if available)
- Credited in GitHub releases

## 📞 Getting Help

- **Discord**: [Join our community](https://discord.gg/KnkFg3aca8)
- **Discussions**: [GitHub Discussions](https://github.com/BuckedUnicorn/retro-synth-dark/discussions)
- **Issues**: [Report bugs](https://github.com/BuckedUnicorn/retro-synth-dark/issues)

## 📄 License

By contributing, you agree that your contributions will be licensed under the same [MIT License](LICENSE) that covers the project.

---

**🌈✨ Let's make VS Code more cyberpunk together! ✨🌈**
