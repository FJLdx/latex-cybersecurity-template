# LaTeX Template for Cybersecurity Reports

This repository contains a customizable LaTeX template designed specifically for cybersecurity reports. The template includes features tailored for professional, clean, and structured documentation, ideal for penetration testing, vulnerability assessments, or any other related reporting.

## Features

- **Customizable Headers**: Personalized headers for every page, excluding the cover page.
- **Dynamic Pagination**: Starts numbering from the index, skipping the cover page.
- **Hyperlink Styling**: Internal and external hyperlinks with professional styling for readability.
- **Chapter Titles**: Simplified chapter headers without "Chapter" labels, providing a cleaner look.
- **Integrated Package Support**:
  - `titlesec`: For header customization.
  - `hyperref`: For hyperlink management.

## Requirements

To use this template, ensure you have the following installed:

- **LaTeX Distribution**: Recommended: [TeX Live](https://tug.org/texlive/) or [MiKTeX](https://miktex.org/).
- PDF Viewer for previewing the compiled reports.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/FJLdx/latex-template.git
   cd latex-template
   ```

2. Open the main LaTeX file `report_template.tex` in your preferred editor (e.g., VS Code, Overleaf).

3. Modify the sections as needed:
   - **Cover Page**: Update title, author, and date.
   - **Content**: Add your report content within the provided structure.

4. Compile the document:
   ```bash
   pdflatex report_template.tex
   ```

   Repeat the compilation if references or hyperlinks are used.

## File Structure

- `report_template.tex`: Main LaTeX file.
- `sections/`: Folder for modular content sections (e.g., Introduction, Findings).
- `images/`: Folder for storing diagrams, charts, or any visual elements.
- `output/`: Folder for compiled PDFs.

## Usage Tips

- Use `\include{}` for organizing content into modular files within the `sections/` directory.
- For troubleshooting LaTeX errors, refer to the `.log` file generated during compilation.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

Special thanks to the Hack4u community and @S4vitar for their inspiration and support in creating this template.

---

**Created by:** Franco Lazzarini

