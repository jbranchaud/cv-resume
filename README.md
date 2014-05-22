# CV/Resume

because I'm qualified.

## Using this repo

The `cv.tex` file is a template that contains all the standard information
that I might want to include in a CV. From there, I can add a job-specific
Objective statement and anything else that is relevant. As well as remove
anything that isn't relevant to the job or doesn't fit within space
restrictions.

Run

    pdflatex cv.tex

to build and generate the PDF for `cv.tex`. It will be named `cv.pdf` by default.

To create a CV for a specific job,

- create a new directory for that CV (e.g. `mkdir ninja-developer2014`)
- make a copy of `cv.tex` in that directory (e.g. `cp cv.tex
  ninja-developer2014/cv.tex`)
- modify this new `cv.tex` to your hearts contents
- build and generate an appropriately named PDF within that directory (e.g.
  `pdflatex -jobname="JoshBranchaud-CV-NinjaInc2014" cv.tex`)

## Built CVs and Résumés

### Current CV

- Download [YAGM-2013-CV.pdf](https://github.com/jbranchaud/cv-resume/raw/master/yagm2013/YAGM-2013-CV.pdf)

### Past CVs

- Download [Google-Internship-2012-CV.pdf](https://github.com/jbranchaud/cv-resume/raw/master/google2012/Google-Internship-2012-CV.pdf)

## License

&copy; 2014 Josh Branchaud

The contents of this repository are under the MIT license. See `LICENSE` for
details.
