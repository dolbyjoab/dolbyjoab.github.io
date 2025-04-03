# Dolbyto Personal Site
#
A minimal, responsive personal website built with Jekyll and hosted on GitHub Pages.

## Features

- Responsive design for all devices
- Automatic light/dark theme based on system preferences
- Manual theme toggle button
- Clean, modern interface
- GitHub Pages deployment ready

## Setup Instructions

1. **Fork or clone this repository**

2. **Install dependencies**
   ```
   bundle install
   ```

3. **Run locally**
   ```
   bundle exec jekyll serve
   ```
   This will start a local server at `http://localhost:4000`

4. **Deploy to GitHub Pages**
   - Push changes to your GitHub repository
   - GitHub Actions will automatically build and deploy your site
   - Make sure GitHub Pages is enabled in your repository settings

5. **Set up your custom domain**
   - The CNAME file is already configured with `dolbyto.dev`
   - Set up DNS records with your domain provider pointing to GitHub Pages
   - Configure your custom domain in the GitHub repository settings

## Customization

- Edit `index.html` to update content
- Modify styles within the `<style>` tag
- Update site configuration in `_config.yml`

## License

Feel free to use and modify this template for your personal website.
