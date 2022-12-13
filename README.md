# Example R project setup for Git

    1. Create new repo on GitHub/GitLab
    2. Include initial README.md & .gitignore (e.g. R template available on GitHub)
    3. "Clone" repo onto desktop using RStudio: File > New Project > Version Control > Git > Choose project location on disk and add https of repo
    4. Add subfolders, e.g.:
        * R - for scripts
        * data - for input data
        * output - for outputs of the analysis (including figures)
        * docs - for additional document outputs (e.g. Rmarkdown)
    5. Edit .gitignore to prevent syncing of reproducible files (preferably all but intial data and R scripts).
    6. Update README.md to provide guidance on the repo structure and use.
