# Lab 1: HTML Resume/CV Page

## 📋 Project Overview

Create a professional HTML resume/CV page that showcases your skills, education, and projects. This lab focuses on semantic HTML structure and proper Git workflow using Pull Requests for each feature addition.

## 🎯 Learning Objectives

- Practice semantic HTML markup
- Learn proper Git workflow with branching and Pull Requests
- Understand project structure and version control
- Create a professional web presence
- Practice collaborative development workflow

## 📁 Project Structure

```
resume-project/
├── index.html          # Main resume page
├── README.md          # This file
└── .gitignore         # Git ignore file (optional)
```

## ✅ Requirements

### 🚀 Getting Started

1. **Fork this repository** to your GitHub profile
2. **Clone your forked repository** to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/resume-project.git
   cd resume-project
   ```

### 📄 HTML Resume Requirements

Create an HTML page (`index.html`) with the following sections:

#### 1. Basic Information Section
- Full Name
- Contact details (email, phone, location)
- Professional links (LinkedIn, GitHub, portfolio)

#### 2. Personal/Professional Description
- 2-3 sentences describing yourself
- Career aspirations or interests
- Example: *"I enjoy drawing and creating digital art. I aspire to become a specialized front-end developer with expertise in modern web technologies."*

#### 3. Education Section
- Schools/Colleges attended
- Degrees and graduation dates
- **Special requirement**: For each educational institution, include:
  - A favorite course you took
  - A pleasant memory from that period

#### 4. Projects Section
- Projects you've worked on
- **Required for each project**:
  - Project title and description
  - Technologies used
  - Link to live demo or repository

#### 5. Additional Sections (Choose at least one)
- Work Experience
- Skills & Technologies
- Certifications
- Volunteer Work
- Hobbies & Interests
- Languages

### 🌟 Technical Requirements

- Use semantic HTML5 tags (`<header>`, `<main>`, `<section>`, `<article>`, etc.)
- Include proper meta tags and page title
- Use the provided HTML template as starting point
- Ensure valid HTML structure
- Make content accessible and well-structured

### 📝 HTML Template

Start with this basic template:

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Your Name - CV/Resume</title>
  </head>
  <body>
    <!-- Your resume content goes here -->
  </body>
</html>
```

## 🔄 Git Workflow Requirements

### Pull Request Strategy

**⚠️ IMPORTANT**: Each section must be added in a separate Pull Request (PR)

#### Required Pull Requests:

1. **PR #1**: `Add basic index.html` - Initial HTML structure with template
2. **PR #2**: `Add basic information section` - Name, contact details
3. **PR #3**: `Add personal description section` - Professional summary
4. **PR #4**: `Add education section` - Schools, courses, memories
5. **PR #5**: `Add projects section` - Project showcase
6. **PR #6**: `Add [additional section name]` - Your chosen extra section

### Git Best Practices

#### ✅ DO:
- Create feature branches for each section
- Use descriptive commit messages
- Rebase or squash commits when merging PRs
- Review your own PRs before merging

#### ❌ DON'T:
- **NEVER** create PRs to the original course repository (📉 -1 point penalty)
- Don't use merge commits
- Don't work directly on the main branch
- Don't create oversized commits

### Step-by-Step Workflow

1. **Create a feature branch**:
   ```bash
   git checkout -b feature/basic-info
   ```

2. **Make your changes** and commit:
   ```bash
   git add index.html
   git commit -m "Add basic information section with contact details"
   ```

3. **Push to your fork**:
   ```bash
   git push origin feature/basic-info
   ```

4. **Create Pull Request** on GitHub:
   - Go to your forked repository
   - Click "New Pull Request"
   - Select your feature branch
   - Add descriptive title and description

5. **Review and merge**:
   - Review your own PR
   - Use "Squash and merge" or "Rebase and merge"
   - Delete the feature branch after merging

6. **Repeat for each section**

## 🏆 Assessment Criteria

### Required Elements (80%)
- [ ] All required sections implemented
- [ ] Proper HTML structure and semantics
- [ ] Each section in separate PR
- [ ] Proper Git workflow followed
- [ ] No PRs to original repository

### Code Quality (15%)
- [ ] Clean, readable HTML
- [ ] Proper indentation and formatting
- [ ] Meaningful commit messages
- [ ] Valid HTML5 markup

### Bonus Points (5%)
- [ ] GitHub Issues used for task tracking
- [ ] Exceptional content organization
- [ ] Creative additional sections
- [ ] Professional presentation

## 🎁 Bonus: GitHub Issues

**Earn extra points** by using GitHub Issues to track your work:

1. **Create issues** for each section before starting:
   - "Create basic HTML structure"
   - "Add personal information section"
   - "Add education section"
   - etc.

2. **Link PRs to issues** using keywords:
   ```
   Closes #1: Add basic HTML structure
   ```

3. **Use labels** to organize issues:
   - `enhancement`
   - `documentation`
   - `in-progress`

## 🛠️ Development Tips

### HTML Best Practices
- Use semantic elements for better accessibility
- Include alt text for images
- Use proper heading hierarchy (h1, h2, h3...)
- Validate your HTML using [W3C Validator](https://validator.w3.org/)

### Content Writing Tips
- Keep descriptions concise but informative
- Use action verbs for project descriptions
- Include specific technologies and tools
- Make it personal but professional

### Git Tips
- Commit early and often
- Write descriptive commit messages
- Use present tense ("Add section" not "Added section")
- Keep commits focused on single changes

## 📚 Resources

### HTML References
- [MDN HTML Guide](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [W3C HTML Validator](https://validator.w3.org/)

### Git Resources
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [GitHub Flow](https://guides.github.com/introduction/flow/)
- [Writing Good Commit Messages](https://chris.beams.io/posts/git-commit/)

### Resume Writing
- [Resume Best Practices](https://www.indeed.com/career-advice/resumes-cover-letters/how-to-make-a-resume)
- [Tech Resume Examples](https://github.com/resume/resume.github.com)

## ⚠️ Important Notes

- **Complete this lab during class time**
- **Do not create PRs to the original course repository** (penalty: -1 point)
- **Each student works on their own fork**
- **Ask questions if Git workflow is unclear**
- **Focus on learning the process, not just completing the task**

## 🆘 Common Issues & Solutions

### Issue: Can't create PR
**Solution**: Make sure you're creating PR in your own fork, not the original repository

### Issue: Merge conflicts
**Solution**: Keep your main branch updated with upstream changes

### Issue: Wrong commit in PR
**Solution**: Use interactive rebase to clean up commit history

### Issue: Forgot to create branch
**Solution**: Create branch from current state, then reset main branch

## 📞 Getting Help

1. **Check the documentation** first
2. **Ask classmates** for Git workflow help
3. **Raise hand during class** for immediate assistance
4. **Create GitHub issue** in your repo describing the problem

---

**Good luck with your first web development lab!** 🚀

*Remember: This is about learning the process as much as creating the final product.*
