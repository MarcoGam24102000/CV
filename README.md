# CV
To create a CV, one can use the website LiveCareer. However, this service requires payment. Additionally, whenever updates are needed, you must upload the CV, make changes, and pay again (as far as I know). Therefore, I created a LaTeX template based on one of the layouts from this site.

# LaTeX CV Template

This LaTeX template is designed to create a professional and customizable Curriculum Vitae (CV) based on the layout of one of the templates presented on LiveCareer. This template allows for easy updates and modifications without additional costs.

## Features

- **Customizable sections**: Easily edit sections such as Contact, Summary, Skills, Experience, Education, and Sports and Volunteering.
- **Professional layout**: A clean and organized format that highlights key information.
- **Easy updates**: Make changes directly in the LaTeX file without needing to re-upload and pay on external websites.

## Prerequisites

- LaTeX distribution (e.g., TeX Live, MiKTeX)
- LaTeX editor (e.g., TeXShop, TeXworks, Overleaf)

## Files Included

- `cv_template.tex`: The main LaTeX file containing the CV template.
- `Images/`: A directory to store your profile photo and icons.

## Usage

1. **Download the Template**: Download the `cv_template.tex` file and the `Images` directory.
2. **Edit the Template**: Open `cv_template.tex` in your LaTeX editor and replace the placeholders with your information.
3. **Compile the Document**: Compile the LaTeX file to generate the PDF of your CV.

## Sections

### Contact

Replace the placeholders in the Contact section with your personal information:

```latex
\node at (0.9,18.5) {\includegraphics[width=6pt]{path_to_location_icon}};
\node at (2.9,18.5){City, State, ZIP Code};
\node at (0.9,18) {\includegraphics[angle=-90, width=6pt]{path_to_phone_icon}};
\node at (2.4,18){+123 456 7890};
\node at (0.9,17.5) {\includegraphics[width=9pt]{path_to_email_icon}};
\node at (3.1,17.5){\small your_email@example.com};
```

### Summary

Provide a brief summary about yourself:

```latex
\node at (2.8,16){Short summary about yourself};
```

### Skills

List your skills in the Skills section:

```latex
\node at (2.8,13){\tiny{Skill 1, Skill 2, Skill 3}};
```

### Experience

Detail your professional experience:

```latex
\node at (8.9,21){\color{bluedark}{\textbf{Job Title}}};
\node at (12.8,20.95){\color{bluedark}{\tiny (Company Name, Location)}};
\node at (10.3,20.7){\color{bluedark}{\small Start Date - End Date}};
```

### Education

Include your educational background:

```latex
\node at (11.7,11.2){\color{bluedark}{\textbf{Degree}}};
\node at (11.8,10.9){\color{bluedark}{\small\textbf{"Field of Study"}}};
\node at (11.7,10.6){\color{bluedark}{\tiny (Institution Name, Location)}};
\node at (11.7,10.3){\color{bluedark}{\tiny{Start Date - End Date}}};
```

### Sports and Volunteering

Describe your sports and volunteering activities:

```latex
\node at (11.5,2.3) {\small{ - Description of your sports and volunteering achievements}};
```

## Notes

- Ensure the paths to images/icons are correct.
- Customize colors and fonts as needed.

## License

This template is free to use and modify for personal or commercial purposes.

