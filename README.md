# CV

This repository contains the LaTeX source code and PDF output of my CV, created using the [Awesome CV LaTeX Template for Cover Letter](https://github.com/posquit0/Awesome-CV). Awesome CV is a LaTeX template for a CV (Curriculum Vitae), Résumé or Cover Letter inspired by Fancy CV.

## Documents

The documents directory contains all the essential LaTeX documents and the generated PDF views:

- [CV (Curriculum Vitae)](https://github.com/thebughuntress/CV/blob/main/cv.pdf)
- [Résumé](https://github.com/thebughuntress/CV/blob/main/resume.pdf)
- [Cover Letter](https://github.com/thebughuntress/CV/blob/main/coverletter.pdf)

## Changes Against the Template

In this project, I have made several modifications to the template to enhance its functionality and make it easier to maintain and update. The key changes are outlined below:

### Constants for Configurations and Personal Information
To centralize global configurations and personal information, I introduced a constants directory. The file [configurations.tex](https://github.com/thebughuntress/CV/blob/main/constants/configurations.tex) file contains constants for colors, styles, and other visual configurations. The file [personal-information.tex](https://github.com/thebughuntress/CV/blob/main/constants/personal-information.tex) contains constants such as name, email, GitHub profile, and other personal data.

### Importing Constants in LaTeX Files
When importing the constants, we can easily access and display the required personal data throughout the CV without duplicating the information. By this approach, a uniform appearance throughout the different CV files is ensured and updating the CV with new information becomes a breeze, as it only requires making changes in one place. Moreover, this approach ensures consistency across the entire CV and reduces the chances of errors when updating personal information.
