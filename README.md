# CS Resume Template (LaTeX)

A one-page LaTeX resume template built for CS students hunting for internships and new grad roles. It's clean, ATS-friendly, and easy to edit.


## Getting Started

### Overleaf (easiest)

1. Create a free account at [overleaf.com](https://www.overleaf.com)
2. Start a new blank project
3. Copy the contents of `template.tex` into the editor and hit compile

No installation needed.

### Local Setup

You'll need TeX Live or MiKTeX installed on your machine, then:

```bash
git clone https://github.com/irtaza-shahzad/Resume-Template.git
cd cs-resume-template
```

---

## What to Edit

Open `template.tex` and swap in your own details. Here's what each section covers:

| Section | What goes here |
|---|---|
| **Heading** | Name, email, phone, LinkedIn, GitHub, portfolio link |
| **Education** | Degree, university, GPA, relevant courses |
| **Work Experience** | Internships or jobs with impact-driven bullet points |
| **Projects** | Things you've built, with tech stack and links |
| **Technical Skills** | Languages, frameworks, tools |

> Keep it to one page. It forces you to only include what actually matters, which is a good thing.

---

## Compiling

**Overleaf:** just hit the green Compile button.

**Locally:**

```bash
pdflatex template.tex
```

This will generate `resume.pdf` in the same directory.
