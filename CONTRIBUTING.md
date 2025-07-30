# Contributing to Crays Circle

Welcome to the Crays Circle community! 🎉 We're excited you want to contribute to building the future of offline-first human connection.

## 🌟 Getting Started

### Join Our Community
- **Discord**: [discord.gg/crays](https://discord.gg/crays) - Join #contributors channel
- **Weekly Calls**: Community calls every Wednesday (announced in Discord)

### First Steps
1. ⭐ Star this repository
2. 🍴 Fork the repository
3. 💬 Join our Discord and introduce yourself
4. 📖 Read our [Code of Conduct](#code-of-conduct)
5. 🔍 Browse [`good first issue`](../../labels/good%20first%20issue) labels

## 🤝 Ways to Contribute

### 💻 Code Contributions
- **Bug fixes** - Help make the app more stable
- **New features** - Implement items from our roadmap
- **Performance** - Optimize mesh networking and AI algorithms
- **Tests** - Improve our test coverage
- **Documentation** - Write guides and improve existing docs

### 🎨 Design & UX
- **UI/UX improvements** - Make the app more intuitive
- **Accessibility** - Ensure everyone can use Crays Circle
- **User research** - Help us understand our community better
- **Visual assets** - Icons, illustrations, animations

### 📝 Documentation
- **Technical guides** - Explain complex concepts
- **Tutorials** - Help new users and developers
- **Translations** - Make Crays Circle globally accessible
- **API documentation** - Keep our docs up to date

### 🌍 Community
- **Discord moderation** - Help maintain our community
- **Content creation** - Blog posts, videos, social media
- **Event organization** - Plan meetups and workshops
- **User support** - Help other community members

## 🔄 Development Workflow

### 1. Choose Your Contribution

#### For Beginners
Look for issues labeled:
- [`good first issue`](../../labels/good%20first%20issue) - Perfect for newcomers
- [`help wanted`](../../labels/help%20wanted) - We need assistance
- [`documentation`](../../labels/documentation) - Improve our docs

#### For Experienced Contributors
- [`feature request`](../../labels/feature%20request) - New functionality
- [`bug`](../../labels/bug) - Fix issues
- [`performance`](../../labels/performance) - Optimization work

### 2. Fork & Clone

```bash
# Fork on GitHub, then clone your fork
git clone https://github.com/YOUR_USERNAME/crays-circle.git
cd crays-circle

# Add upstream remote
git remote add upstream https://github.com/crays-ecosystem/crays-circle.git

# Install dependencies
npm install
```

### 3. Create a Branch

```bash
# Create a descriptive branch name
git checkout -b feature/mesh-network-optimization
# or
git checkout -b fix/personality-matching-bug
# or  
git checkout -b docs/api-examples
```

### 4. Make Your Changes

#### Code Quality Standards
- **TypeScript**: Use strong typing, no `any` types
- **Testing**: Write tests for new features
- **Linting**: Run `npm run lint` before committing
- **Privacy**: Ensure all data stays on-device when possible
- **Offline-first**: Features should work without internet

#### Commit Guidelines
Follow [Conventional Commits](https://conventionalcommits.org/):

```bash
# Good commit messages
git commit -m "feat: add personality-based matching algorithm"
git commit -m "fix: resolve mesh network connection timeout"
git commit -m "docs: update API documentation for matching engine"
git commit -m "test: add unit tests for DNC protocol"
```

### 5. Test Your Changes

```bash
# Run all tests
npm test

# Test on both platforms
npm run ios
npm run android

# Run linting
npm run lint

# Type checking
npm run type-check
```

### 6. Submit a Pull Request

```bash
# Push your branch
git push origin feature/your-feature-name

# Create PR on GitHub
```

#### PR Guidelines
- **Title**: Clear, descriptive title following conventional commits
- **Description**: Explain what you changed and why
- **Screenshots**: Include before/after for UI changes
- **Testing**: Describe how you tested your changes
- **Breaking Changes**: Highlight any breaking changes

#### PR Template
```markdown
## What does this PR do?
Brief description of changes

## Why is this change needed?
Explain the problem this solves

## How did you test this?
- [ ] Unit tests pass
- [ ] Manual testing on iOS
- [ ] Manual testing on Android
- [ ] Mesh network functionality tested

## Screenshots (if applicable)
[Add screenshots here]

## Checklist
- [ ] Code follows our style guidelines
- [ ] Tests added/updated
- [ ] Documentation updated
- [ ] No breaking changes (or clearly marked)
```

## 📋 Issue Guidelines

### Reporting Bugs

Use our bug report template:

```markdown
**Bug Description**
Clear description of what went wrong

**Steps to Reproduce**
1. Go to...
2. Click on...
3. See error...

**Expected Behavior**
What should have happened

**Environment**
- OS: [iOS 16.0 / Android 13]
- Device: [iPhone 14 / Pixel 7]
- App Version: [1.0.0]

**Screenshots**
Add relevant screenshots
```

### Suggesting Features

Use our feature request template:

```markdown
**Feature Description**
Clear description of the proposed feature

**Problem It Solves**
What user problem does this address?

**Proposed Solution**
How should this work?

**Alternatives Considered**
Other solutions you considered

**Additional Context**
Mockups, examples, technical considerations
```

## 🎯 Priority Areas

We especially need help with:

### High Priority
- **Mesh Network Optimization**: Improving connection reliability
- **Battery Efficiency**: Reducing power consumption
- **AI Matching Accuracy**: Better personality-based connections
- **Accessibility**: Making the app usable for everyone

### Medium Priority
- **Performance**: Faster app startup and navigation
- **Internationalization**: Support for more languages
- **Advanced Features**: Group matching, event integration
- **Documentation**: More comprehensive guides

### Always Welcome
- **Bug Reports**: Help us find and fix issues
- **User Feedback**: How can we improve the experience?
- **Community Building**: Growing our Discord and DAO
- **Testing**: Manual testing on different devices

## 🔒 Security

### Reporting Security Issues

**DO NOT** create public issues for security vulnerabilities.

Instead:
- Email: info@crays.world
- Use GitHub's private vulnerability reporting
- Include detailed reproduction steps
- We'll respond within 48 hours

### Security Guidelines

- Never commit secrets, API keys, or private keys
- Use environment variables for sensitive configuration
- Follow secure coding practices
- Keep dependencies updated

## 📝 Code of Conduct

### Our Pledge

We pledge to make participation in Crays Circle harassment-free for everyone, regardless of:
- Age, body size, disability, ethnicity
- Gender identity and expression
- Level of experience, nationality
- Personal appearance, race, religion
- Sexual identity and orientation

### Expected Behavior

- Use welcoming and inclusive language
- Respect differing viewpoints and experiences
- Accept constructive criticism gracefully
- Focus on what's best for the community
- Show empathy towards other community members

### Unacceptable Behavior

- Harassment, trolling, or discriminatory behavior
- Publishing others' private information
- Spam or excessive self-promotion
- Any conduct that would be inappropriate in a professional setting

### Enforcement

Community leaders will:
- Remove inappropriate comments/content
- Temporarily or permanently ban violators
- Report serious violations to appropriate authorities

Report violations to: info@crays.world

## 🎉 Recognition

We celebrate our contributors!

### Hall of Fame
Top contributors are featured in:
- README.md acknowledgments
- Monthly Discord highlights
- Annual community awards
- DAO governance roles

### Contribution Levels

- **🌱 Seed**: First contribution merged
- **🌿 Sprout**: 5+ contributions merged  
- **🌳 Tree**: 25+ contributions or major feature
- **🌟 Forest**: Long-term maintainer and community leader

## 📞 Getting Help

### Development Help
- **Discord**: #dev-help channel
- **GitHub**: Use issue templates

### General Questions
- **Discord**: #general channel
- **Email**: info@crays.world

---

## 🚀 Ready to Start?

1. Find a [`good first issue`](../../labels/good%20first%20issue)
2. Join our [Discord](https://discord.gg/crays)
3. Fork the repository
4. Start building the future!

**Thank you for helping build Crays Circle!** 🙏

*"Seek those who fan your flames"* 🔥
