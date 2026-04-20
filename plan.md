# Project Plan
This file has my plans for two things: (1) the HW #4.3 data analysis 
project itself, and (2) setting up and keeping this GitHub repo organized.

## Part 1: HW #4.3 Project Plan

### Goals
- Finish a Quarto report that can be rendered to a PDF without errors.
- Cover all three sections required in HW #4.3: the airport analysis, 
  the Monte Carlo part, and the AI prompting comparison.
- Make sure all the plots and text are correct.

### Needs
- RStudio with Quarto installed, plus TinyTeX so the PDF can render.
- The `tidyverse` and `kableExtra` R packages.
- The `calcium.csv` file.
- An AI tool (for me is Claude) for the prompting comparison.

### Steps
1. Start with Section 1 (airports). Put the passenger numbers into a 
   tibble, make a summary table with `kableExtra`, and then plot the 
   trends over 2020–2025 with `ggplot2`.
2. Do Section 2 (Monte Carlo). Write a function to generate random 
   points inside a box, run it for n = 10, 100, 1000, and 10000, then 
   use `facet_wrap` to show all four in one figure.
3. Section 3 (GenAI comparison). Write a detailed plan for cleaning 
   `calcium.csv`, give it to Claude, and save the result. Then try a 
   generic prompt and compare.
4. Add all the extra stuff Quarto needs: YAML header, figure captions, 
   alt text and section headings.
5. Render to PDF and check everything looks right.

## Part 2: Repo Setup Plan

### Goals
- Using GitHub skillfully.
- Show that I know how to use branches, issues, commits, and pull 
  requests properly.
- Keep the repo clean and easy for others to understand.

### Needs
- A GitHub account.
- GitHub Desktop installed.
- A public repo.

### Steps
1. Create the repo on GitHub with a README and an R `.gitignore`.
2. Clone it to my laptop using GitHub Desktop.
3. Open a couple of issues for the things I need do.
4. Make a dev branch instead of working on main.
5. Add the files and commit each change with a clear message. 
6. When everything is on the dev branch, open a pull request and 
    merge it into main.
7. Close the issues after the PR is merged.
8. Check the repo and make sure nothing is missing on the main branch.