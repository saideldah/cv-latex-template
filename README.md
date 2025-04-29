# CV LaTeX Template

A sleek, professional LaTeX CV/resume template with customizable sections for skills, work experience, education, and languages.

## Description

This CV template is designed for tech professionals who want a clean, modern resume that effectively showcases their experience and skills. Key features include:

- Clean typography with customizable color schemes
- Hyphenation disabled for improved readability
- Multi-column skill section for compact presentation
- Organized work experience with company-first format
- Horizontal language section with proficiency levels
- Education section with institution-first format
- Page numbers at bottom center

## Prerequisites

To build this CV, you'll need:

**A LaTeX distribution:**
- **macOS:** MacTeX
- **Windows:** MiKTeX or TeX Live
- **Linux:** TeX Live via your package manager

**Required LaTeX packages** (most are included in standard distributions):
- `fontspec`
- `hyperref`
- `fancyhdr`
- `multicol`
- `textcomp`

**XeLaTeX compiler** (included in the LaTeX distributions above)

## Building the CV

### Command Line

Navigate to the project directory:

```bash
cd /path/to/cv
```

Compile using XeLaTeX:

```bash
xelatex resume.tex
```

The output will be `resume.pdf` in the same directory.

### Using an IDE

**VS Code:**
- Install the **LaTeX Workshop** extension
- Open the project folder
- Open `resume.tex`
- Click the "Build LaTeX Project" button or use the shortcut

**TeXShop (macOS):**
- Open `resume.tex`
- Ensure XeLaTeX is selected as the typesetting engine
- Click "Typeset"

**Overleaf:**
- Create a new project
- Upload all files
- Set compiler to **XeLaTeX** in the menu
- Click "Compile"

## Customization

- **Personal Information:** Edit the header section to include your details
- **Summary:** Modify the summary text to highlight your expertise
- **Skills:** Add or remove skills in the itemized lists
- **Work Experience:** Use the `\cventry` command for each position
- **Languages:** Update language proficiencies
- **Education:** Use the `\eduentry` command for each degree or certificate

## File Structure

- `resume.tex`: Main template file
- `awesome-cv.cls`: Class file containing the template styling
- `fonts/`: Directory containing required fonts
- `.gitignore`: Git ignore file for LaTeX projects

## License

This template is available under the [MIT License](LICENSE).