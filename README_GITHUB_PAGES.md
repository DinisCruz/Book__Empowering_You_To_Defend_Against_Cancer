# Taking Control - GitHub Pages Site

This branch contains a GitHub Pages site for the book **"Taking Control: A Lifestyle Medicine Approach to Cancer Prevention and Treatment"** by Deb Brewer.

## About This Site

This site provides a user-friendly, web-based version of the book content, allowing readers to navigate through chapters easily with a clean, responsive interface.

## Site Structure

- **Home Page**: Introduction and table of contents
- **22 Chapters**: Organized into two parts:
  - Part 1: Understanding Cancer and The ReachVitality Program (Chapters 1-11)
  - Part 2: The Six Pillars of Lifestyle Medicine - Nutrition & Supplementation (Chapters 12-22)
- **Sources Page**: All references and citations

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Easy Navigation**: Sidebar navigation with active chapter highlighting
- **Previous/Next Navigation**: Move between chapters seamlessly
- **Clean Typography**: Optimized for reading comfort
- **Styled Callout Boxes**: Success, warning, and tip boxes for important information

## Technology

This site is built using:
- **Jekyll**: Static site generator
- **GitHub Pages**: Free hosting
- **Markdown**: Content format from the original Leanpub manuscript
- **Custom CSS**: User-friendly styling

## Local Development

To run this site locally:

1. Install Jekyll and Bundler:
   ```bash
   gem install jekyll bundler
   ```

2. Create a Gemfile if it doesn't exist:
   ```ruby
   source "https://rubygems.org"
   gem "jekyll"
   gem "github-pages", group: :jekyll_plugins
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Run the site:
   ```bash
   bundle exec jekyll serve
   ```

5. Open your browser to `http://localhost:4000`

## Deployment

This site is configured to deploy automatically via GitHub Pages. Once pushed to the `github-pages` branch, GitHub will build and publish the site.

To enable GitHub Pages:
1. Go to repository Settings
2. Navigate to Pages section
3. Select source: Deploy from branch
4. Select branch: `github-pages`
5. Select folder: `/ (root)`
6. Save

Your site will be available at: `https://[username].github.io/[repository-name]/`

## License

This book is licensed under Creative Commons CC-BY 4.0.

## Contact

For more information, visit [ReachVitality.com](https://www.ReachVitality.com) or email [reachvitality@gmail.com](mailto:reachvitality@gmail.com).
