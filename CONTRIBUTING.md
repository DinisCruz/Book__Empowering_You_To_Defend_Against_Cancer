# Contributing to "Taking Control"

Thank you for your interest in contributing to this book! This book is licensed under CC-BY 4.0, which means you're welcome to contribute improvements, corrections, and enhancements.

## How to Contribute

### Reporting Issues

If you find errors, typos, or have suggestions for improvements:

1. Open an issue on GitHub describing the problem or suggestion
2. Include the chapter and section where the issue appears
3. If possible, suggest how to fix or improve it

### Submitting Changes

To contribute content changes:

1. Fork this repository
2. Create a new branch for your changes (`git checkout -b fix/typo-chapter-3`)
3. Make your changes to the appropriate Markua files in `manuscript/`
4. Test your changes by previewing in a Markdown viewer
5. Commit your changes with a clear commit message
6. Push to your fork
7. Open a Pull Request describing your changes

### Contribution Guidelines

#### What to Contribute

We welcome contributions that:
- Fix typos, grammar, or formatting errors
- Improve clarity of explanations
- Add relevant, properly cited scientific sources
- Enhance the organization or structure
- Update outdated information

#### What NOT to Contribute

Please avoid:
- Medical advice that contradicts the book's approach
- Promotional content for competing products/services
- Content that is not properly sourced or cited
- Changes that alter the fundamental message or author's voice

### Source Citations

When adding new content that references research or sources:

1. Add the full citation to `backmatter.md` in the Sources section
2. Use the next available number in the sequence
3. Include a working URL when available
4. Follow the existing citation format

Example:
```markdown
29. **National Library of Medicine: [Article Title]**  
    https://pmc.ncbi.nlm.nih.gov/articles/PMCXXXXXXX
```

### Markua Formatting Standards

Please follow these formatting conventions:

#### Headers
```markdown
# Chapter Title (only one per file)
## Major Section
### Subsection
```

#### Emphasis
- Bold: `**important text**`
- Italic: `*emphasis*`

#### Lists
```markdown
- Bullet point
- Another point
  - Sub-point (indent with 2 spaces)

1. Numbered item
2. Another numbered item
```

#### Special Boxes
```markdown
{class: tip}
B> **Title**
B>
B> Content of the tip box

{class: warning}
B> **Warning Title**
B>
B> Warning content

{class: success}
B> **Success Title**
B>
B> Success content
```

#### Links
```markdown
[Link text](https://example.com)
```

## Code of Conduct

### Our Standards

Contributors are expected to:
- Be respectful and constructive in discussions
- Focus on what's best for the book and its readers
- Accept constructive criticism gracefully
- Show empathy toward other contributors

### Unacceptable Behavior

- Harassment, discrimination, or hostile comments
- Publishing others' private information
- Trolling or deliberately inflammatory remarks
- Other conduct inappropriate in a professional setting

### Enforcement

Violations of the code of conduct may result in:
1. A warning from maintainers
2. Temporary ban from contributing
3. Permanent ban from the project

Report violations to: deb@reachvitality.com

## Questions?

If you have questions about contributing:

1. Check existing issues and pull requests
2. Review the `LEANPUB_SETUP.md` for technical details
3. Open a GitHub issue with your question
4. Contact Deb Brewer at deb@reachvitality.com

## Recognition

Contributors will be acknowledged in the book's frontmatter (unless they prefer not to be). Significant contributions may be highlighted in release notes.

## License

By contributing, you agree that your contributions will be licensed under the same CC-BY 4.0 license as the book.

---

Thank you for helping make this book better and more accessible to those who need it!
