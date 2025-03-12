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

## Modifying the Website

### Editing index.html Locally

1. Open `index.html`.

2. Make the desired changes to the file. Common modifications include:

   #### Adding a New Week to the Schedule
   ```html
   <tr>
       <td>16</td>
       <td>04/26</td>
       <td>New Topic Title</td>
       <td>Any assignments due</td>
       <td>
           <a href="slides/new-slides.pdf" target="_blank" class="resource-link"><i class="fas fa-file-pdf"></i> Slides</a>
           <a href="notebooks/new-notebook.ipynb" target="_blank" class="resource-link"><i class="fas fa-file-pdf"></i> Notebook</a>
       </td>
   </tr>
   ```

   #### Adding a New Section
   ```html
   <section id="new-section">
       <h2><i class="fas fa-icon-name"></i> New Section Title</h2>
       
       <p>Content for your new section goes here.</p>
       
       <!-- More HTML content as needed -->
   </section>
   ```

   #### Modifying Course Information
   To update instructor information or course details, locate the `course-info-grid` section:
   ```html
   <div class="info-card">
       <h3><i class="fas fa-user-tie"></i> Instructor</h3>
       <p>Updated Instructor Name<br>
       <i class="fas fa-envelope"></i> updated.email@northeastern.edu<br>
       <i class="fas fa-video"></i> Office: New Location<br>
       <i class="fas fa-clock"></i> Office Hours: New Hours</p>
   </div>
   ```

   #### Adding or Updating Resources
   ```html
   <a href="path/to/new-resource.pdf" target="_blank" class="resource-link">
       <i class="fas fa-file-pdf"></i> Resource Name
   </a>
   ```

3. Save your changes in the editor

4. Commit and push your changes to GitHub:
   ```bash
   git add index.html
   git commit -m "Updated index.html with [description of changes]"
   git push origin main
   ```

Your changes will be published automatically to your GitHub Pages site, typically within a few minutes.
