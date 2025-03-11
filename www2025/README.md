# AI Paper Showcase Template

This is a static webpage template for showcasing academic papers in the AI field, developed based on Jekyll and AcademicPages theme.

## Project Structure

```
.
├── index.html          # Main page
├── assets/             # Static resource folder
│   ├── css/           # CSS style files
│   ├── js/            # JavaScript files
│   └── images/        # Image resources
└── README.md          # Project documentation
```

## Usage Instructions

### 1. Basic Information Modification

In the `index.html` file, you need to modify the following parts:

- `<title>`: Change to your paper title
- `<meta>`: Update related meta tag information
- Author information: Modify author names, affiliations, and contact information
- Paper abstract: Replace with your paper abstract

### 2. Adding Author Information

For each author in the author information section, use the following format:

```html
<div class="author__content">
    <h3 class="author__name">Author Name</h3>
    <p class="author__bio">Position @ Institution</p>
</div>
```

### 3. Adding Images

1. Place image files in the `assets/images/` directory
2. Reference images in HTML using relative paths:

```html
<img src="assets/images/your-image.jpg" alt="Image description">
```

### 4. Modifying Styles

To customize styles, modify the `assets/css/main.css` file.

## Deployment Instructions

1. Push the code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select main branch as the source branch
4. After a few minutes, your page will be live at `https://[username].github.io/[repository-name]`

## Important Notes

- Ensure all image resources are properly uploaded
- Maintain the integrity of the file structure
- Update content regularly to keep the page active

## Technical Support

For any questions, please refer to:
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)