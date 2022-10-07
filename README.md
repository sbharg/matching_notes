#  $\LaTeX$ Report Template

To add a new section to the paper, create a `(name).tex` file in the `sections` folder. Then, in `main.tex`, use the macro
`\input{sections/(name).tex}` to place the section in its relevant place relative to the other sections. 

Note: When creating `(name).tex`, you don't have to include any preamble information (like documentclass, packages, etc.) or the 
`\begin{document} ... \end{document}` environments. 

To modify a section, simply modify the relevant `.tex` file in the `sections` folder. 
