# Contributing to Modern Red Team Infrastructure

Thank you for your interest in contributing to this curated list of red team tools, platforms, and resources! This document provides guidelines to ensure high-quality contributions.

## How to Contribute

### 1. Fork and Clone
```bash
git fork https://github.com/YOUR_USERNAME/Red-Team-Infrastructure
git clone https://github.com/YOUR_USERNAME/Red-Team-Infrastructure.git
cd Red-Team-Infrastructure
```

### 2. Create a Branch
```bash
git checkout -b add-new-tool-name
```

### 3. Make Your Changes
Edit the appropriate section in `README.md` following the guidelines below.

### 4. Submit a Pull Request
- Provide a clear description of what you're adding
- Explain why it's valuable for red team professionals
- Include any relevant links or documentation

## Contribution Guidelines

### What to Contribute

**We welcome:**
- ✅ New tools, platforms, or resources relevant to red team operations
- ✅ Updates to existing descriptions with more accurate information
- ✅ Corrections of outdated links or information
- ✅ New categories that don't fit existing sections
- ✅ Improvements to documentation or organization

**We generally don't accept:**
- ❌ Tools that are purely theoretical without practical implementation
- ❌ Duplicate entries already covered by existing tools
- ❌ Commercial tools without free tier or trial (unless industry-standard)
- ❌ Malware or illegal tools (educational/research frameworks only)
- ❌ Promotional content without technical merit

### Quality Standards

#### 1. Tool/Resource Requirements
- **Relevance**: Must be directly applicable to red team operations, adversary simulation, or offensive security
- **Availability**: Should be publicly accessible (link must work)
- **Legitimacy**: Official sources only (no mirrors, reuploads, or unauthorized copies)
- **Activity**: Prefer actively maintained projects (exceptions for industry standards)

#### 2. Description Requirements

Each description must be:
- **Specific**: State what the tool does, not generic marketing language
- **Concise**: 15-40 words maximum
- **Technical**: Include key features, protocols, or capabilities
- **Accurate**: Based on actual functionality, not assumptions
- **Professional**: Written in clear, technical English

**Good Description Example:**
```markdown
|[Sliver](https://github.com/BishopFox/sliver)|Cross-platform open-source C2 by Bishop Fox supporting mTLS/WireGuard/HTTP/DNS, dynamic code generation, multiplayer mode, and compile-time obfuscation.|
```

**Poor Description Examples:**
```markdown
|[Tool X](https://example.com)|Great tool for hacking.| ❌ Too vague
|[Tool Y](https://example.com)|The best, most amazing, revolutionary C2 framework ever created with unparalleled capabilities that will change red teaming forever.| ❌ Marketing fluff
|[Tool Z](https://example.com)|Tool for extracting Chrome's App-Bound Encryption to extract cookies...| ❌ Wrong description (copy-paste error)
```

#### 3. Formatting Requirements

Follow this exact markdown table format:
```markdown
|[Tool Name](https://official-url.com/)|Description goes here with specific features and capabilities.|
```

**Important:**
- Use official URL or primary GitHub repository
- Tool name should match official branding/capitalization
- No trailing spaces or extra line breaks
- Descriptions end with a period

### Description Writing Tips

1. **Lead with the tool's primary purpose**
   ```
   "Advanced C2 framework..." or "Open-source phishing platform..."
   ```

2. **Include 2-4 key technical features**
   ```
   "...supporting mTLS/WireGuard/HTTP/DNS, dynamic code generation, multiplayer mode..."
   ```

3. **Specify unique differentiators**
   ```
   "...with superior EDR evasion" or "...featuring GPT-powered analysis"
   ```

4. **End with use case context**
   ```
   "...for red team operations." or "...for adversary simulation."
   ```

### Section-Specific Guidelines

#### AI Agent / AI Model/LLM Server
- Focus on security/development use cases
- Mention multi-LLM support if applicable
- Specify if open-source vs. commercial API

#### OSINT Platform
- Highlight automation capabilities
- Mention data sources or collection methods
- Note any AI/ML-powered features

#### C2 Platform
- List supported communication protocols
- Mention key evasion techniques
- Specify cross-platform support if available
- Note if collaborative/multi-operator

#### Phishing Platform
- Clarify MFA/2FA bypass capabilities
- Distinguish simulation vs. real attack framework
- Mention campaign management features

#### Beacon/Implant
- Specify programming language
- List key evasion or injection techniques
- Note if educational vs. production-ready

## Review Process

1. **Automated Checks**: PR must pass basic formatting validation
2. **Manual Review**: Maintainers will verify:
   - Description accuracy
   - Link validity
   - Appropriate categorization
   - No duplicates
3. **Feedback**: You may be asked to revise descriptions or provide additional context
4. **Merge**: Once approved, your contribution will be merged

## Code of Conduct

- Be respectful and professional
- Focus on technical merit
- Provide constructive feedback
- Use these resources ethically and legally
- Only submit contributions for authorized security testing

## Questions?

If you're unsure about anything:
1. Check existing entries for formatting examples
2. Open an issue to discuss before submitting PR
3. Ask for clarification in your PR description

## License

By contributing, you agree that your contributions will be licensed under the same license as this repository.

---

**Thank you for helping build a valuable resource for the red team community!** 🔴⚔️
