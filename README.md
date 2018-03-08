# Thesis Cover Page LaTeX Template

This template imitates the [official cover page](https://www.tuwien.ac.at/dekanate/dekanatszentrum_3/formulare/) of diploma theses submitted at the faculty for physics at the TU Wien, Vienna, Austria.

## Getting started

Clone this repository and compile the file `main.tex` with pdflatex. Your output should look like [this](main.pdf).

## Personalizing the template

In order to personalize this template, just redefine the corresponding commands in `titlepage.tex` accordingly.
```
\newcommand{\thesistitle}{Titel der Diplomarbeit (Deutsch/Englisch)}
\newcommand{\thesisdegree}{Diplom-Ingenieur/in}
\newcommand{\thesisstudies}{Bezeichnung des Studiums}
\newcommand{\thesisauthor}{Martina Muster}
\newcommand{\thesisstudentnumber}{01234567}
\newcommand{\thesisinstitute}{XYZ}
\newcommand{\thesisfaculty}{XYZ}
\newcommand{\thesisuniversity}{Technischen Universit\"{a}t Wien}
\newcommand{\thesiscollaboration}{XYZ}
\newcommand{\thesissupervisor}{Titel Dr. Vorname Familienname}
\newcommand{\thesiscosupervisor}{Univ.-Ass. Dr. Vorname Familienname}
\newcommand{\thesisplace}{Wien}
\newcommand{\thesisdate}{TT.MM.JJJJ}
```

> If you want to make further changes to the title page (e.g., adapt the text to the gender of the author/supervisor/...), the above definitions will not suffice and you have to find the corresponding locations in the document.

## Contributing

Improvements to this template are always welcome! Feel free to open a pull request or an issue anytime.