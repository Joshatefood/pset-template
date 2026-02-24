# LaTeX Physics Problem Set Template

Modular LaTeX template for clean, structured physics and mathematics problem sets.

Designed for reusable problems, consistent formatting, and fast compilation across assignments.

---

## Features

* Modular layout (`main.tex` + `preamble.tex`)
* Separate `problems/` directory for content
* Consistent headers and spacing
* Math-friendly environments
* Reusable across courses

---

## Repository Structure

```
pset-template/
├── main.tex
├── preamble.tex
├── problems/
│   ├── problem1.tex
│   ├── problem2.tex
│   └── …
├── example.pdf
<<<<<<< HEAD
=======
├── references.bib 
>>>>>>> 962b28f (Moved header settings to main.tex)
└── README.md
```

---

## Usage

Clone the template:

```
git clone https://github.com/Joshatefood/pset-template.git
```

Edit or add problems in:

```
problems/
```

Compile:

```
pdflatex main.tex
```

(or `latexmk -pdf`)

---

## Design Philosophy

The template separates responsibilities:

* **Structure** → `main.tex`
* **Formatting** → `preamble.tex`
* **Content** → `problems/`

This keeps problem sets readable, consistent, and easy to reuse across courses.

---

## Customization

Common edits:

* Packages and macros → `preamble.tex`
* Header and problem order → `main.tex`
* New problems → `problems/`

---

## Author

Joshua Adrian G. Lontoc
Undergraduate Physics Student
