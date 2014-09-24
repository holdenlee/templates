This folder contains the following.

diags.tex: template for making asy diagrams
formatting.tex: formatting for how sections are displayed
lecture_macros.tex: commands for taking lectures on a class
macros.tex: macros
macros2.tex: macros with \cir omitted (forget which package this comes in)
other.tex: not sure what this is
packages_only.tex: package imports
packages_book.tex: define articleclass as book, package imports, and set up TOC
packages_article.tex: define articleclass as article, package imports
pset template.tex: for psets
template.tex: usage example
theorem_num.tex: put last if you want numbering Thm (chapter).(section).(subsection). Else it will be (section).(subsection).
theorems_only.tex: theorem definitions
theorems_with_boxes.tex: theorems with pretty boxes. TikZ required.
titlepage.tex: make a title page (You must \def\name{TITLE NAME} first.)

Templates:
reading_template.tex: template for reading notes

Standard usage:
%You MUST DEFINE THE FILEPATH

\def\filepath{C:/Users/Owner/Dropbox/Math/templates}

\input{\filepath/packages_book.tex}
\input{\filepath/theorems_with_boxes.tex}
\input{\filepath/macros.tex}
\input{\filepath/formatting.tex}
\input{\filepath/other.tex}

This is so that there is only 1 copy of the template on the computer. To export, make a local copy of the templates folder and change the \filepath.

Where to find things:
* Section labelling - formatting.tex
* Theorem numbering - theorem_num.tex
* TOC and section numbering depth - packages_book.tex, etc.