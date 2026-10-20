# university-latex-cv-template

A customizable LaTeX template for creating professional academic and technical CVs, featuring a clean layout and flexible styling.

Features
- Custom layout: Headers, footers, and background watermarks.

- Flexible styling: Configurable colors, branding, and contact information.

- Font Awesome icons: Visual elements for section headings.

- Multi-page support: A structured layout suitable for detailed CVs.

- Clickable links: Integrated email and GitHub links.

- Example content: A starting point for tailoring your CV to academic or technical positions.

## Preview

![CV Preview](preview/cv-preview.jpg)

[📄 Download the full PDF](preview/cv-example.pdf)

## Requirements
A LaTeX distribution, such as TeX Live or MiKTeX
XeLaTeX or LuaLaTeX
The TeX Gyre Heros font
The LaTeX packages used by the template, including TikZ, Font Awesome, and fontspec
Getting Started
Clone or download this repository.
Make sure the images/ directory contains all required image assets.
Edit main.tex to customize your personal information, education, experience, skills, and other sections.
Update NAstyle.sty to customize the colors, header, footer, watermark, and visual layout.
Compile the document using XeLaTeX or LuaLaTeX.

For example, using XeLaTeX:

xelatex main.tex

## Project Structure
```
├── main.tex
├── NAstyle.sty
├── images/
│   ├── na_header.png
│   ├── footer.png
│   ├── na_logo_background.png
│   └── example_avatar.png
├── preview/
│   └── cv-example.pdf
├── README.md
├── LICENSE
└── .gitignore
```
## Customization
Contact Information

Edit the following commands in main.tex:

\providecommand{\CVEmail}{your.email@example.com}
\providecommand{\CVPhone}{+00 000 000 0000}
\providecommand{\CVGitHubURL}{https://github.com/yourusername}
\providecommand{\CVGitHubLabel}{GitHub Profile}

Background and other University pictures

Edit the following commands in NAstyle.sty:

\newcommand{\CVHeaderImage}{images/na_header.png}
\newcommand{\CVFooterImage}{images/footer.png}
\newcommand{\CVWatermarkImage}{images/na_logo_background.png}

University pictures

You can edit the immagines directely in Canva, to get an inspire you can look at this for references:
https://canva.link/9lxqtxd0bnu7ibg

Colors and Branding

Edit the color definitions and image paths in NAstyle.sty to customize the appearance of the CV.

Content

Replace the example information in main.tex with your own education, experience, technical skills, languages, and other relevant sections.

## License

See LICENSE for information about permitted use and redistribution.

## Contributing

Suggestions, bug reports, and improvements are welcome. Feel free to open an issue or submit a pull request.
