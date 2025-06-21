# 🤝 Contributing to TEKKEN 8 Offline Setup Assistant

Welcome to the fighting game community! We're excited that you want to contribute to making TEKKEN 8 more accessible for offline players worldwide.

## 🎯 Ways to Contribute

### 🐛 Bug Reports
Found a bug? Help us squash it:
- Check [existing issues](https://github.com/TEKKEN-8-Offline-Setup-Assistant/tekken-offline-setup-assistant/issues) first
- Use our [bug report template](.github/ISSUE_TEMPLATE/bug_report.md)
- Include system specs, TEKKEN version, and reproduction steps
- Attach screenshots or videos if possible

### 💡 Feature Requests
Have an idea for improving the assistant?
- Check [discussions](https://github.com/TEKKEN-8-Offline-Setup-Assistant/tekken-offline-setup-assistant/discussions) for existing ideas
- Use our [feature request template](.github/ISSUE_TEMPLATE/feature_request.md)
- Explain the use case and how it benefits the community
- Consider the technical feasibility

### 🔧 Code Contributions
Ready to get your hands dirty?

#### Before You Start
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Check our [development setup guide](docs/development.md)
4. Join our [Discord](https://discord.gg/tekken-offline) for technical discussions

#### Development Guidelines
- **Language**: C# (.NET 6.0+) for the main assistant
- **Code Style**: Follow [Microsoft C# conventions](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)
- **Testing**: Add unit tests for new features
- **Documentation**: Update relevant docs and code comments

#### Pull Request Process
1. Ensure tests pass and code builds successfully
2. Update documentation if needed
3. Add changelog entry in `CHANGELOG.md`
4. Request review from maintainers
5. Address feedback promptly

### 📝 Documentation
Help other players and developers:
- Fix typos or unclear instructions
- Add tutorials for specific controllers or setups
- Translate documentation to other languages
- Create video guides or screenshots

### 🎨 Design & UX
Make the assistant more user-friendly:
- Improve the user interface design
- Suggest better user experience flows
- Create icons, graphics, or promotional materials
- Test usability with different user types

### 🌐 Translations
Help us reach global fighting game communities:
- Translate the interface to your language
- Localize documentation and guides
- Review existing translations for accuracy
- Add cultural context for specific regions

## 📋 Issue Templates

### 🐛 Bug Report
- **System Information**: OS, Hardware, TEKKEN version
- **Expected Behavior**: What should happen
- **Actual Behavior**: What actually happens
- **Steps to Reproduce**: Detailed reproduction steps
- **Additional Context**: Screenshots, logs, crash dumps

### 💡 Feature Request
- **Problem Statement**: What problem does this solve?
- **Proposed Solution**: How would you implement this?
- **Alternatives**: What other approaches did you consider?
- **Community Impact**: Who would benefit from this?

### ❓ Question/Support
- **Topic**: What are you trying to do?
- **Context**: Your current setup and goals
- **Attempts**: What have you already tried?
- **Resources**: What documentation have you checked?

## 🏆 Recognition

### Contributors Hall of Fame
Outstanding contributors get:
- Recognition in our README and releases
- Special Discord roles and access
- Beta testing privileges for new features
- Invitations to community events and tournaments

### Contribution Types
We recognize all forms of contribution:
- 💻 **Code**: Bug fixes, features, optimizations
- 📖 **Documentation**: Guides, tutorials, translations
- 🎨 **Design**: UI/UX improvements, graphics
- 🧪 **Testing**: Beta testing, bug reproduction
- 💬 **Community**: Support, moderation, events
- 🎮 **Domain Expertise**: Fighting game knowledge, frame data

## 🛠️ Development Setup

### Prerequisites
- Visual Studio 2022 or VS Code
- .NET 6.0 SDK or later
- Git for version control
- Windows 10/11 for testing

### Getting Started
```bash
# Clone your fork
git clone https://github.com/YOUR-USERNAME/tekken-offline-setup-assistant.git
cd tekken-offline-setup-assistant

# Add upstream remote
git remote add upstream https://github.com/TEKKEN-8-Offline-Setup-Assistant/tekken-offline-setup-assistant.git

# Install dependencies
dotnet restore

# Build the project
dotnet build

# Run tests
dotnet test
```

### Project Structure
```
src/
├── TekkenAssistant.Core/     # Core business logic
├── TekkenAssistant.UI/       # User interface (WPF)
├── TekkenAssistant.Config/   # Configuration management
├── TekkenAssistant.Input/    # Controller handling
└── TekkenAssistant.Graphics/ # Display optimization

tests/
├── Unit/                     # Unit tests
├── Integration/             # Integration tests
└── E2E/                     # End-to-end tests

docs/                        # Documentation
assets/                      # Images, icons, resources
```

## 📜 Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold this code.

### Our Standards
- **Respectful**: Treat everyone with respect, regardless of skill level
- **Inclusive**: Welcome newcomers and diverse perspectives  
- **Constructive**: Focus on solutions and positive outcomes
- **Patient**: Help others learn and grow in the community
- **Fun**: Remember we're all here because we love fighting games!

## 🔒 Security

Found a security vulnerability? Please don't open a public issue. Instead:
1. Email us at security@tekken-offline.com
2. Provide detailed reproduction steps
3. Allow us time to investigate and patch
4. We'll credit you in the security advisory

## 📞 Getting Help

### Technical Questions
- 💬 [Discord Community](https://discord.gg/tekken-offline)
- 💭 [GitHub Discussions](https://github.com/TEKKEN-8-Offline-Setup-Assistant/tekken-offline-setup-assistant/discussions)
- 📧 Email: support@tekken-offline.com

### Fighting Game Questions
- Join our Discord's #combo-lab channel
- Check out /r/Tekken on Reddit
- Visit Tekken Zaibatsu forums

## 🎮 Community Guidelines

### Fighting Game Etiquette
- Share knowledge freely
- Respect different playstyles and skill levels
- Encourage new players to join the community
- Keep discussions constructive and helpful
- Celebrate the diversity of the FGC

### Project-Specific Guidelines
- Test your changes with different controllers
- Consider accessibility for players with disabilities
- Maintain compatibility with various TEKKEN versions
- Document any breaking changes clearly
- Keep the offline focus of the project

---

**Thank you for contributing to the TEKKEN 8 Offline Setup Assistant! Together, we're making fighting games more accessible for everyone.** 🥋✨ 