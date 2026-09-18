# 📚 Rise Queen Rise - Project Setup Guide

**Last Updated:** September 18, 2026

---

## 🎯 Table of Contents

1. [Project Overview](#project-overview)
2. [Repository Structure](#repository-structure)
3. [Files & Folders Created](#files--folders-created)
4. [GitHub Actions Workflows](#github-actions-workflows)
5. [Community Guidelines](#community-guidelines)
6. [How to Contribute](#how-to-contribute)
7. [Managing Contributors & Permissions](#managing-contributors--permissions)
8. [Links to Share](#links-to-share)
9. [Next Steps](#next-steps)

---

## 🎯 Project Overview

**Rise Queen Rise** is a community dedicated to uplifting, empowering, and inspiring women and non-binary individuals through:
- ✨ Daily affirmations and prompts
- 🎨 Creative visual content
- 💖 Wellness and personal health information
- 🤝 Supportive community engagement

**Repository:** https://github.com/ojnivi/Rise-Queen-Rise

**Owner:** ojnivi (Juan Ivi)

---

## 📁 Repository Structure

```
Rise-Queen-Rise/
├── .github/
│   ├── workflows/
│   │   ├── stale.yml                 # Auto-closes inactive issues/PRs
│   │   ├── welcome.yml               # Welcomes new contributors
│   │   ├── auto-label.yml            # Auto-labels issues/PRs
│   │   └── validate.yml              # Validates content quality
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   ├── feature_request.md
│   │   └── general_question.md
│   └── PULL_REQUEST_TEMPLATE.md
├── graphics/                         # Visual assets folder
│   └── README.md                    # Graphics contribution guide
├── phi/                             # Personal Health Information folder
│   └── README.md                    # Wellness contribution guide
├── README.md                        # Main project overview
├── CONTRIBUTING.md                  # How to contribute
├── CODE_OF_CONDUCT.md              # Community standards
├── WELCOME.md                       # Welcome message for new contributors
└── LICENSE                          # Project license

```

---

## 📄 Files & Folders Created

### **Core Documentation Files**

#### 1. **README.md** 📖
- **Purpose:** Main project overview and introduction
- **Contains:** Project mission, structure, and quick start guide
- **Location:** Root directory
- **Link:** https://github.com/ojnivi/Rise-Queen-Rise/blob/main/README.md

#### 2. **CONTRIBUTING.md** 🤝
- **Purpose:** Detailed contribution guidelines
- **Contains:** How to fork, create branches, submit PRs, and best practices
- **Location:** Root directory
- **Link:** https://github.com/ojnivi/Rise-Queen-Rise/blob/main/CONTRIBUTING.md

#### 3. **CODE_OF_CONDUCT.md** 👑
- **Purpose:** Community standards and behavioral expectations
- **Contains:** Inclusive values, conflict resolution, and enforcement
- **Location:** Root directory
- **Link:** https://github.com/ojnivi/Rise-Queen-Rise/blob/main/CODE_OF_CONDUCT.md

#### 4. **WELCOME.md** 💖
- **Purpose:** Encouraging message to welcome new contributors
- **Contains:** What the project is about, ways to contribute, how to get help
- **Location:** Root directory
- **Link:** https://github.com/ojnivi/Rise-Queen-Rise/blob/main/WELCOME.md

### **Folders Created**

#### 5. **graphics/** 🎨
- **Purpose:** Store all visual assets and design contributions
- **Suggested Subfolders:**
  - `social-media/` - Social media graphics
  - `posters/` - Motivational posters
  - `logos/` - Branding assets
  - `thumbnails/` - Preview images
  - `templates/` - Design templates
  - `illustrations/` - Artwork

#### 6. **phi/** 💪
- **Purpose:** Personal Health Information and wellness content
- **Suggested Subfolders:**
  - `mental-health/` - Mental wellness resources
  - `physical-wellness/` - Fitness and health content
  - `emotional-care/` - Self-care guides
  - `nutrition/` - Healthy eating resources
  - `meditation-mindfulness/` - Guided practices
  - `sleep-wellness/` - Sleep hygiene guides
  - `wellness-challenges/` - Community challenges

---

## ⚙️ GitHub Actions Workflows

We've set up 4 automated workflows to help manage your community:

### **1. Stale Issue Management** 🧹
- **File:** `.github/workflows/stale.yml`
- **Triggers:** Runs weekly (Monday at 9 AM UTC)
- **What it does:**
  - Marks issues/PRs inactive for 90 days as "stale"
  - Posts a friendly message asking for updates
  - Closes stale items after 14 more days of inactivity
- **Why:** Keeps your repository organized and shows activity

### **2. Welcome New Contributors** 👋
- **File:** `.github/workflows/welcome.yml`
- **Triggers:** When someone opens a PR or issue
- **What it does:**
  - Posts a welcoming message
  - Links to CONTRIBUTING.md and CODE_OF_CONDUCT.md
  - Invites them to join Discussions
- **Why:** Creates a warm, inclusive first impression

### **3. Auto-Label Issues and PRs** 🏷️
- **File:** `.github/workflows/auto-label.yml`
- **Triggers:** When PRs/issues are opened or reopened
- **What it does:**
  - Automatically adds labels based on keywords:
    - "bug" → `bug` label
    - "feature" → `enhancement` label
    - "doc" → `documentation` label
    - "question" → `question` label
    - "community" → `community` label
    - "good first" → `good first issue` label
- **Why:** Organizes issues automatically, helping contributors find tasks

### **4. Content Validation** ✨
- **File:** `.github/workflows/validate.yml`
- **Triggers:** When markdown/text files are changed in PRs
- **What it does:**
  - Checks for trailing whitespace
  - Checks for missing final newlines
  - Checks for double spaces after periods
  - Runs markdown linter
- **Why:** Maintains consistent, high-quality content

---

## 🤝 Community Guidelines

### **Our Values**
✨ Self-love & empowerment
💭 Reflective growth
🤝 Community support
🎨 Creative expression

### **Code of Conduct Highlights**
- Be kind and respectful to all members
- Celebrate diversity in all forms
- Listen actively and engage thoughtfully
- No harassment, discrimination, or hate speech
- Lift each other up, always

**Full details:** See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)

---

## 🚀 How to Contribute

### **Ways to Contribute**

1. **📝 Add Affirmations & Prompts**
   - Write uplifting affirmations
   - Create thoughtful reflection prompts
   - Submit daily inspiration content

2. **🎨 Create Graphics & Design**
   - Design social media graphics
   - Create motivational posters
   - Contribute visual content

3. **💻 Help with Development**
   - Improve repository structure
   - Fix bugs and issues
   - Add new features
   - Improve documentation

4. **📚 Improve Documentation**
   - Write guides and tutorials
   - Expand README sections
   - Help with translations
   - Create examples

5. **🐛 Report Bugs & Suggest Ideas**
   - Open an issue if you find a problem
   - Share feature ideas in discussions
   - Provide constructive feedback

### **Getting Started as a Contributor**

1. **Read** [CONTRIBUTING.md](./CONTRIBUTING.md)
2. **Check** [Issues](../../issues) for tasks labeled "good first issue"
3. **Join** [Discussions](../../discussions) to connect
4. **Fork** the repository
5. **Submit** a Pull Request

---

## 👥 Managing Contributors & Permissions

### **Permission Levels (From Lowest to Highest)**

| Level | Can View | Can Push | Can Merge | Can Manage Settings | Best For |
|-------|----------|---------|----------|-------------------|----------|
| **Pull request reviewer** | ✅ | ❌ | ❌ | ❌ | Code reviewers only |
| **Triage** | ✅ | ❌ | ❌ | ❌ | Issue/PR managers |
| **Write** | ✅ | ✅ | ✅ | ❌ | Active contributors |
| **Maintain** | ✅ | ✅ | ✅ | ✅ (limited) | Trusted maintainers |
| **Admin** | ✅ | ✅ | ✅ | ✅ (full) | Project leaders |

### **How to Add a Collaborator**

1. Go to **Repository Settings** → **Collaborators and teams**
2. Click **"Add people"**
3. Enter their **GitHub username**
4. Choose their **permission level**
5. Click **"Add"**

They'll receive an invitation to accept.

### **How to Make Someone an Admin** 👑

Same process as above, but select **"Admin"** as the permission level.

**For Rise Queen Rise:**
- **Admin:** You (project owner) + trusted co-leaders
- **Maintain:** 2-3 core maintainers who review content
- **Write:** Active contributors with proven track record
- **Triage:** Community members who help manage issues

---

## 🔗 Links to Share

### **Share These Links with Potential Contributors:**

| Link | Purpose |
|------|---------|
| https://github.com/ojnivi/Rise-Queen-Rise | Main repository |
| https://github.com/ojnivi/Rise-Queen-Rise/blob/main/CONTRIBUTING.md | How to contribute |
| https://github.com/ojnivi/Rise-Queen-Rise/blob/main/WELCOME.md | Welcome message |
| https://github.com/ojnivi/Rise-Queen-Rise/issues | Report issues/ideas |
| https://github.com/ojnivi/Rise-Queen-Rise/discussions | Community discussions |
| https://github.com/ojnivi/Rise-Queen-Rise/pulls | Pull requests |

### **Creating a Landing Page**
You might want to create a simple landing page or social media post that includes:
- Link to the repository
- Brief description of what you're about
- Call to action: "Help us rise together! 👑✨"

---

## 🎯 Next Steps

### **Immediate (This Week)**

- [ ] Create your GitHub Organization (optional but recommended)
- [ ] Transfer the repository to your organization (if creating one)
- [ ] Add your daughter as an Admin (once she creates her GitHub account)
- [ ] Set up teams within the organization
- [ ] Review and customize all documentation files
- [ ] Create issue templates and PR templates

### **Short Term (This Month)**

- [ ] Start inviting initial contributors
- [ ] Create your first content (affirmations, prompts, graphics)
- [ ] Set up community labels and organization system
- [ ] Plan your first community challenge or initiative
- [ ] Test the GitHub Actions workflows

### **Medium Term (Next Quarter)**

- [ ] Build contributor community
- [ ] Establish content review process
- [ ] Create contributor spotlight/recognition system
- [ ] Plan community events or content releases
- [ ] Grow social media presence

### **Long Term (This Year)**

- [ ] Expand beyond GitHub (website, social media, newsletter?)
- [ ] Create recognition/rewards system for contributors
- [ ] Build community partnerships
- [ ] Develop Rise Queen Rise brand and merchandise (optional)
- [ ] Plan annual community celebration

---

## 📞 Quick Reference

### **Important Files**
- Main README: [README.md](./README.md)
- How to Contribute: [CONTRIBUTING.md](./CONTRIBUTING.md)
- Community Rules: [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)
- Welcome Message: [WELCOME.md](./WELCOME.md)

### **Important Folders**
- Graphics: [graphics/](./graphics/)
- Wellness/Health: [phi/](./phi/)
- Workflows: [.github/workflows/](./.github/workflows/)

### **Important Links**
- Repository: https://github.com/ojnivi/Rise-Queen-Rise
- Issues: https://github.com/ojnivi/Rise-Queen-Rise/issues
- Discussions: https://github.com/ojnivi/Rise-Queen-Rise/discussions
- Pull Requests: https://github.com/ojnivi/Rise-Queen-Rise/pulls

---

## 🌟 Final Thoughts

You've built an amazing foundation for Rise Queen Rise! This project has:
- ✅ Clear mission and values
- ✅ Welcoming culture
- ✅ Organized structure
- ✅ Automated workflows
- ✅ Professional documentation
- ✅ Community-focused approach

**Remember:** You're not just building a repository—you're building a **movement of empowerment and support**. 👑✨

---

## 📝 Document History

| Date | Changes |
|------|---------|
| 2026-09-18 | Initial setup guide created with all project documentation |

---

**Created with 💖 for the Rise Queen Rise Community**

*Last Updated: September 18, 2026*

*For questions or updates to this guide, please open an issue or discussion!*
