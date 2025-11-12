Overleaf / LaTeX skeleton for NPSS Individual Project

Files in this folder:
- main.tex            : Top-level LaTeX file (report class)
- sections/task1.tex  : Placeholder for Task 1 (ER diagram)
- sections/task2.tex  : Placeholder for Task 2 (relational schemas)
- sections/task3.tex  : Placeholder for Task 3 (storage structures)
- sections/task4.tex  : Placeholder for Task 4 (SQL statements + screenshots)
- sections/task5.tex  : Placeholder for Task 5 (SQL queries and Java program)
- sections/task6.tex  : Placeholder for Task 6 (program execution screenshots)
- images/             : Put ER diagram PNG/SVG and screenshots here

How to use
1) Open this folder in VS Code or zip the folder and upload it to Overleaf.
   - Overleaf: "Upload Project" -> select the contents of this folder (or zip) and Overleaf will create a new project.
   - Local compile: Run `pdflatex main.tex` twice (or use latexmk) to build the PDF.

2) Replace the placeholders in the section files with your content. Add figures to `images/` and reference them with \includegraphics{images/...}.

3) Recommended compile commands (Windows cmd.exe):

```cmd
rem If using MikTeX or TeX Live and pdflatex is on PATH
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
```

Or use latexmk (if installed):

```cmd
latexmk -pdf main.tex
```

Notes
- Make sure your images are not too large for Overleaf; resize if necessary.
- If you prefer Overleaf Git integration, see Overleaf docs (may require a paid plan).
