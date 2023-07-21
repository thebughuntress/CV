# CV

This repository contains the LaTeX source code and PDF output of my CV, created using the [Awesome CV LaTeX Template for Cover Letter](https://github.com/posquit0/Awesome-CV). Awesome CV is a LaTeX template for a CV(Curriculum Vitae), Résumé or Cover Letter inspired by Fancy CV.

## Documents

The documents directory contains all the essential LaTeX documents and the generated PDF views:

- [CV (Curriculum Vitae)](https://github.com/thisisfrey/CV/blob/main/documents/cv.pdf)
- [Résumé](https://github.com/thisisfrey/CV/blob/main/documents/resume.pdf)
- [Cover Letter](https://github.com/thisisfrey/CV/blob/main/documents/coverletter.pdf)

## Changes Against the Template

In this project, I have made several modifications to the template to enhance its functionality and make it easier to maintain and update. The key changes are outlined below:

### Constants File for General Configurations and Personal Information
To centralize global configurations and personal information, I introduced a constants directory. The file [configurations](https://github.com/thisisfrey/CV/blob/main/documents/constants/configurations.tex) file contains constants for colors, styles, and other visual configurations. The file [personal-information](https://github.com/thisisfrey/CV/blob/main/documents/constants/personal-information.tex) contains constant information such as name, email, GitHub profile, and other personal data.

By this approach, a uniform appearance throughout the different CV files is ensured and updating the CV with new information becomes a breeze, as it only requires making changes in one place.

### Importing Constants in Application Files
By importing the constants from the constants directory, we can easily access and display the required personal data throughout the CV without duplicating the information. Moreover, this approach ensures consistency across the entire CV and reduces the chances of errors when updating personal information.
