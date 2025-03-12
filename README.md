# CSYE7374: Applied Deep Learning and Generative Models in Healthcare

This repository contains the course website for CSYE7374: Applied Deep Learning and Generative Models in Healthcare at Northeastern University.

## Website Structure

The website includes:
- Course information and instructor details
- Course description and syllabus
- Weekly schedule with links to materials
- Links to slides, notebooks, assignments, and readings

## Deploying as a GitHub Page

To deploy this website as a GitHub Page, follow these steps:

### 1. Create a GitHub Repository

1. Sign in to your GitHub account
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository (e.g., `csye7374-course-website`)
4. Make it public
5. Click "Create repository"

### 2. Upload the Website Files

```bash
# Clone the repository
git clone https://github.com/yourusername/csye7374-course-website.git
cd csye7374-course-website

# Add all the website files to the repository
# Copy your index.html and create the following folders:
# - slides/
# - notebooks/
# - assignments/
# - materials/
# - syllabus/

# Add files to git
git add .
git commit -m "Initial commit with course website"
git push origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"

GitHub will provide you with a URL where your site is published (typically `https://yourusername.github.io/csye7374-course-website/`).

### 4. Organize Your Resources

Create the following folders in your repository to match the links in the HTML:
- `slides/` - For all presentation slides
- `notebooks/` - For Jupyter notebooks
- `assignments/` - For assignment PDFs
- `materials/` - For research papers and other readings
- `syllabus/` - For the course syllabus

Upload the respective files to each folder.

## Maintenance

To update the website:

1. Make changes to your local files
2. Commit and push changes to GitHub:
   ```bash
   git add .
   git commit -m "Update website with [description of changes]"
   git push origin main
   ```