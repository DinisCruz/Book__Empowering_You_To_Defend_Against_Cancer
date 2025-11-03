# Repository Structure

This document explains the organization of this LeanPub book repository.

## Directory Structure

```
Book__Deb__Taking_Control/
├── manuscript/              # Book content (Markua format)
│   ├── Book.txt            # Defines chapter order for full book
│   ├── Sample.txt          # Defines chapters for free sample
│   ├── frontmatter.md      # Title, copyright, TOC
│   ├── chapter01.md        # What is Cancer?
│   ├── chapter02.md        # Our Core Defense Systems
│   ├── chapter03.md        # Background for Deb's Cancer Story
│   ├── chapter04.md        # Unhealthy Lifestyle + Trigger = Cancer
│   ├── chapter05.md        # Deb's Journey to Healing
│   ├── chapter06.md        # An Important Note About Mutations
│   ├── chapter07.md        # Take the First Step & Take Back Control
│   ├── chapter08.md        # Prevent, Fight, and Heal
│   ├── chapter09.md        # Lifestyle Medicine Benefits
│   ├── chapter10.md        # The Power of Moderation
│   ├── chapter11.md        # Create an Environment for DNA Healing
│   └── backmatter.md       # Sources, about author, disclaimer
├── README.md               # Main repository documentation
├── LICENSE                 # CC-BY 4.0 license details
├── LEANPUB_SETUP.md       # How to publish on LeanPub
├── CONTRIBUTING.md         # Contribution guidelines
├── STRUCTURE.md           # This file
└── .gitignore             # Git ignore rules
```

## File Descriptions

### Core Book Files

**manuscript/Book.txt**
- Lists all files to include in the full book
- Order determines chapter sequence
- Plain text file with one filename per line

**manuscript/Sample.txt**
- Defines which chapters appear in the free sample
- Useful for giving readers a preview before purchase
- Currently includes first 3 chapters

**manuscript/frontmatter.md**
- Contains `{frontmatter}` directive for LeanPub
- Includes title page, copyright notice, contact info
- Ends with `{mainmatter}` to start main content

**manuscript/chapter*.md**
- Individual chapter files in Markua format
- Numbered for easy sorting and organization
- Each starts with a single `#` header (chapter title)

**manuscript/backmatter.md**
- Contains `{backmatter}` directive
- Includes all source citations
- Author biography and disclaimer

### Documentation Files

**README.md**
- Overview of the book project
- License information
- Quick start guide
- Contact information

**LICENSE**
- Full text of CC-BY 4.0 license
- Copyright notice
- Attribution guidelines

**LEANPUB_SETUP.md**
- Step-by-step LeanPub configuration
- GitHub integration instructions
- Publishing workflow
- Troubleshooting tips

**CONTRIBUTING.md**
- How to contribute improvements
- Code of conduct
- Formatting standards
- Pull request process

**STRUCTURE.md** (this file)
- Explains repository organization
- File and directory descriptions
- Workflow overview

**.gitignore**
- Specifies files Git should ignore
- Excludes generated files (PDFs, EPUBs, etc.)
- Ignores OS and editor-specific files

## Workflow

### For Authors/Editors

1. Edit content in `manuscript/*.md` files
2. Commit changes to Git
3. Push to GitHub
4. LeanPub automatically detects changes and can rebuild
5. Generate preview to review changes
6. Publish new version when satisfied

### For Readers

1. Read the book on LeanPub (PDF, EPUB, or MOBI)
2. View source content on GitHub
3. Report issues or suggest improvements
4. Fork and contribute improvements (see CONTRIBUTING.md)

### For Contributors

1. Fork this repository
2. Make changes in your fork
3. Test locally with a Markdown viewer
4. Submit pull request
5. Maintainer reviews and merges

## Markua Format

This book uses Markua, LeanPub's enhanced Markdown format for books.

### Key Features Used

**Headers**
```markdown
# Chapter Title
## Section Title
### Subsection Title
```

**Special Boxes**
```markdown
{class: tip}
B> Tip content

{class: warning}
B> Warning content

{class: success}
B> Success content
```

**Emphasis**
```markdown
**bold text**
*italic text*
```

**Lists**
```markdown
- Bullet point
1. Numbered item
```

**Links**
```markdown
[Link text](https://example.com)
```

For complete Markua documentation: https://leanpub.com/markua/read

## Adding New Content

### New Chapter

1. Create new file: `manuscript/chapterXX.md`
2. Start with single `#` header for chapter title
3. Add content using Markua formatting
4. Add filename to `manuscript/Book.txt` in desired position
5. Optionally add to `manuscript/Sample.txt` if it should be in preview

### New Section

1. Edit existing chapter file
2. Add `##` header for new section
3. Add content below

### New Source/Citation

1. Edit `manuscript/backmatter.md`
2. Add numbered entry in Sources section
3. Include full citation and URL
4. Reference in chapter text if needed

## Version Control Best Practices

### Commit Messages

Use clear, descriptive commit messages:

```
Good:
- "Fix typo in Chapter 3, section on somatic mutations"
- "Add new source citation for inflammation research"
- "Improve clarity of alkaline pH explanation in Chapter 9"

Avoid:
- "Update"
- "Changes"
- "Fix stuff"
```

### Branching

For significant changes:
1. Create feature branch: `git checkout -b feature/chapter-revision`
2. Make changes
3. Commit frequently
4. Push to GitHub
5. Open pull request
6. Merge after review

For minor fixes:
- Can commit directly to main branch

## Questions?

If you have questions about the structure or how to work with this repository:

1. Check the other documentation files
2. Open an issue on GitHub
3. Contact Deb Brewer: deb@reachvitality.com

---

Last updated: November 2025
