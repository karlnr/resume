# Resume

Initial version of a single page, two-column resume written in LaTeX.  

## Overview

The main source file is resume.tex. Heading and column specific layout & content is imported from heading.tex, leftside.tex, and rightside.tex. Personal information is located in variables.tex. Future versions will use cv.cls to separate layout & formatting from `.tex` content files.  

## Requirements

XeLaTeX to compile, [FontAwesome5](https://fontawesome.com) for symbols, and [Corbel](https://docs.microsoft.com/en-us/typography/font-list/corbel) for the main font.  

The `fontspec` package is used to tap into system installed fonts. On macOS, Corbel can be installed with the FontBook application by locating the font files from path:  

`/Applications/Microsoft Word.app/Contents/Resources/DFonts`

## Build

From a command line:  

`xelatex resume.tex`

The compiled file is `resume.pdf`.  


