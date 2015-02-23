This is a set of BibTeX files related to research in Thermodynamics and Foam Formation.

## Biber

Different BibTeX front-ends (JabRef, BibDesk etc) save the files in different formatting styles. To normalize the file (changing the spacing, capitalization etc but not the file's contents), one can use the `biber` command, present in TeX distributions.

The script `biber-and-git-add` creates this normalized version and adds the file to the staging area. Python and the `biber` program are necessary, and the script is intended to be run from a Unix terminal or Git Bash session (in Windows).

After saving the file, instead of running `git add Thermo-Foam-Ref.bib`, run `biber-and-git-add Thermo-Foam-Ref.bib`, and proceed to commit the changes.
