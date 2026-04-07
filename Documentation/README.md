# QuickLaTeX

QuickLaTeX is a LaTeX template project designed for fast and clean document creation, with a modern style and modular structure. It is ideal for reports, research papers, and other academic or professional documents.

## Features
- Modular template structure for easy customization
- Modern section and subsection styling
- Customizable headers and footers
- Predefined color schemes
- Ready-to-use preamble with common packages
- English comments for clarity
- Makefile for easy compilation and cleaning

## Project Structure
```
QuickLaTeX/
├── LICENSE
├── Makefile
├── README.md
├── main.tex
├── contents/
│   ├── researches.tex
│   └── title.tex
├── _Template/
│   ├── preambule.tex
│   ├── styles.tex
│   ├── footer.tex
│   ├── assets/
│   │   └── img/
```

## Usage
1. **Clone or copy the project.**
2. Edit `main.tex` to include your content and desired modules from the `contents/` and `_Template/` folders.
3. Add your images to `_Template/assets/img/` if needed.
4. Compile the document using the provided Makefile:
   ```sh
   make
   ```
   or for a clean build:
   ```sh
   make mrproper
   ```

## Customization
- Modify `_Template/styles.tex` to change colors, section styles, and page layout.
- Edit `_Template/preambule.tex` to add or remove LaTeX packages as needed.
- Update `_Template/footer.tex` for custom headers/footers or to add a logo.

## Requirements
- LaTeX distribution (TeX Live, MiKTeX, etc.)
- `make` utility (optional, for using the Makefile)

## License
This project is licensed under the terms of the LICENSE file provided.
