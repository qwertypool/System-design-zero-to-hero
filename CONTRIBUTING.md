# Contributing to System Design Zero to Hero

First off, thank you for considering contributing to this project! 🎉

## How Can You Contribute?

### 1. Improve Documentation

- Fix typos or grammatical errors
- Clarify existing explanations
- Add missing information
- Improve formatting and readability

### 2. Add New Topics

- Suggest new system design topics
- Provide detailed explanations for existing topics
- Share real-world examples and case studies

### 3. Create Diagrams

- Design clear and informative diagrams
- Use consistent styling and colors
- Save diagrams in the `/diagrams` folder
- Use tools like Draw.io, Excalidraw, or similar

### 4. Share Resources

- Add helpful links and references
- Recommend books, courses, or articles
- Share video tutorials or blog posts

### 5. Report Issues

- Report broken links
- Point out incorrect information
- Suggest improvements

## Contribution Guidelines

### Before You Start

1. Check existing issues and pull requests to avoid duplication
2. Create an issue to discuss major changes before implementing them
3. Follow the existing structure and format

### Making Changes

1. **Fork the Repository**
   ```bash
   git clone https://github.com/qwertypool/System-design-zero-to-hero.git
   cd System-design-zero-to-hero
   ```

2. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Follow the existing markdown format
   - Use `<details>` tags for expandable sections
   - Include YouTube video placeholders: `📺 YouTube Video: [Coming Soon](#)`
   - Add diagrams to the appropriate `/diagrams/phaseX/` folder

4. **Test Your Changes**
   - Preview markdown rendering
   - Check all links work
   - Verify images load correctly

5. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "feat: add explanation for topic XYZ"
   ```
   
   Use conventional commit messages:
   - `feat:` - New feature or topic
   - `fix:` - Bug fix or correction
   - `docs:` - Documentation improvements
   - `style:` - Formatting changes
   - `refactor:` - Restructuring content

6. **Push and Create a Pull Request**
   ```bash
   git push origin feature/your-feature-name
   ```

### Pull Request Guidelines

- Provide a clear description of changes
- Reference related issues (if any)
- Keep changes focused and atomic
- Ensure markdown formatting is correct
- Update the Table of Contents if needed

## Style Guide

### Markdown Format

- Use proper heading hierarchy (`#`, `##`, `###`)
- Use `<details>` tags for collapsible sections
- Include emojis for visual organization (📘, 🔧, 🚀, 🏗️)
- Add horizontal rules (`---`) between major sections

### Content Structure

Each topic should include:

```markdown
<details>
<summary><b>Icon Phase.Number Topic Name</b></summary>

### Topic Title

Brief description of the topic.

**Topics Covered:**
- Point 1
- Point 2
- Point 3

**Resources:**
- 📺 YouTube Video: [Coming Soon](#)
- 📄 Diagram: `/diagrams/phaseX/topic-name.png`

**Key Takeaways:**
- Important point 1
- Important point 2

</details>
```

### Diagram Guidelines

- Use consistent colors and styling
- Keep diagrams simple and clear
- Save as PNG or SVG format
- Use descriptive filenames
- Store in appropriate phase folder: `/diagrams/phase1/`, `/diagrams/phase2/`, etc.

### Writing Style

- Use clear, concise language
- Explain technical terms when first used
- Provide real-world examples
- Include both theory and practice
- Make content beginner-friendly

## Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inspiring community for all.

### Expected Behavior

- Be respectful and inclusive
- Welcome newcomers and help them learn
- Accept constructive criticism gracefully
- Focus on what is best for the community

### Unacceptable Behavior

- Harassment or discrimination
- Trolling or insulting comments
- Publishing others' private information
- Other unprofessional conduct

## Questions?

Feel free to:
- Open an issue for discussion
- Reach out to maintainers
- Join community discussions

---

Thank you for helping make system design education more accessible! 🚀

---

**Note:** This is a documentation-focused repository. We do not accept code files (e.g., `.py`, `.js`, `.java`) unless they are example snippets within markdown documentation.
