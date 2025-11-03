# LeanPub Setup Instructions

This guide will help you publish this book on LeanPub using GitHub integration.

## Prerequisites

1. A GitHub account with this repository
2. A LeanPub account (create one at https://leanpub.com)

## Step-by-Step Setup

### 1. Create a New Book on LeanPub

1. Log in to LeanPub
2. Click "Create a Book"
3. Enter book details:
   - **Title**: Taking Control: A Lifestyle Medicine Approach to Cancer Prevention and Treatment
   - **Subtitle**: ReachVitality's 6-Pillar Program for Fighting Cancer
   - **Author**: Deb Brewer

### 2. Configure GitHub Writing Mode

1. In your LeanPub book settings, go to "Settings" → "Writing Mode"
2. Select **"GitHub"** as your writing mode
3. Click "Connect to GitHub" and authorize LeanPub to access your GitHub account
4. Select the repository: `DinisCruz/Book__Deb__Taking_Control`
5. Choose the branch: `main` (or your default branch)
6. Set the manuscript folder: `manuscript`

### 3. Configure Book Settings

In your LeanPub book settings:

#### Pricing
- Set your desired pricing (can be free or paid)
- Consider offering a variable pricing model (e.g., minimum $0, suggested $9.99)

#### License
- In the book description, mention: "Licensed under CC-BY 4.0"
- Consider adding this to the book cover or landing page

#### Categories
- Health & Fitness
- Self-Help
- Medical

#### Book Description
Use this or similar:

```
Taking Control is a comprehensive guide to using lifestyle medicine to prevent and fight cancer. Written by Stage 4 cancer survivor Deb Brewer, who holds certification in Lifestyle Medicine from Harvard Medical School Executive Education, this book presents the ReachVitality 6-Pillar Program based on personal experience, cutting-edge research, and proven lifestyle interventions.

Whether you're facing a cancer diagnosis, seeking to prevent cancer, or supporting a loved one, this book empowers you with practical, evidence-based strategies to strengthen your body's natural defenses and create an internal environment where cancer struggles to survive.

Learn how to:
- Strengthen your immune system and DNA repair mechanisms
- Create an alkaline, oxygen-rich internal environment
- Support your body through targeted nutrition and supplementation
- Reduce inflammation and oxidative stress
- Build resilience through stress reduction and restorative sleep
- Take control of your health with sustainable lifestyle changes

Licensed under CC-BY 4.0 - Share and adapt freely with attribution.
```

### 4. Generate Your First Preview

1. Make sure all files are committed and pushed to GitHub
2. In LeanPub, go to "Preview" → "Create Preview"
3. LeanPub will pull from GitHub and generate PDF, EPUB, and MOBI versions
4. Review the preview to ensure formatting looks correct

### 5. Publish Your Book

Once you're satisfied with the preview:

1. Go to "Publish" in your LeanPub dashboard
2. Click "Publish New Version"
3. Your book will be available for purchase/download

## Updating the Book

To update the book after it's published:

1. Make changes to the Markua files in the `manuscript/` folder
2. Commit and push to GitHub
3. LeanPub will automatically detect changes (or you can manually trigger a rebuild)
4. Generate a new preview to review changes
5. Publish the new version

## Tips for Success

### Generating a Sample
The `Sample.txt` file defines which chapters appear in the free sample. Currently includes:
- Front matter (title, copyright, TOC)
- Chapter 1: What is Cancer?
- Chapter 2: Our Core Defense Systems
- Chapter 3: Background for Deb's Cancer Story

You can add more chapters to the sample by adding their filenames to `Sample.txt`.

### Markua Formatting
- Use `{class: tip}` for tip boxes
- Use `{class: warning}` for warning boxes
- Use `{class: success}` for success/positive boxes
- Headers: Use `#` for chapters, `##` for sections
- Bold: `**text**`
- Italic: `*text*`
- Lists: Use `-` or `*` for bullets, `1.` for numbered lists

### Images
If you want to add images (like the ReachVitality logo):
1. Create a `resources/` folder in the manuscript directory
2. Add images there
3. Reference in Markua: `![Alt text](resources/image.png)`

### Book Metadata
Consider adding to frontmatter:
- ISBN (if you have one)
- Publication date
- Version number

## Troubleshooting

### Build Fails
- Check that all filenames in `Book.txt` exist in the `manuscript/` folder
- Ensure all Markua syntax is valid
- Review the build log in LeanPub for specific errors

### Formatting Issues
- Preview the book before publishing
- Test on multiple formats (PDF, EPUB, MOBI)
- Adjust Markua syntax as needed

### GitHub Sync Issues
- Verify the GitHub integration is still active
- Check that you're pushing to the correct branch
- Manually trigger a sync in LeanPub if automatic detection fails

## Additional Resources

- **LeanPub Documentation**: https://leanpub.com/help
- **Markua Manual**: https://leanpub.com/markua/read
- **GitHub Writing Mode Guide**: https://help.leanpub.com/en/articles/2916385-getting-started-using-leanpub-s-git-and-github-writing-mode-to-write-and-publish-a-book

## Support

If you need help with the book content or ReachVitality program:

**Deb Brewer**  
Email: deb@reachvitality.com  
Phone: 617-429-0600

For LeanPub technical support:  
Email: hello@leanpub.com
