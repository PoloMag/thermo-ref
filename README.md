This is my collection of BibTeX files.

The main file, `Thermo-Foam-Ref.bib`, includes many papers and books related to my field of study, which was originally foam formation in oil and refrigerant mixtures. Now, this databases includes many other works on thermal sciences in general.

The other `.bib` files contains other books I read, mainly non-fiction and fiction books.

I'm keeping this repository public in case anyone uses the same sources I use.

## Biber

Different BibTeX front-ends (JabRef, BibDesk etc) save the files in different formatting styles. To normalize the file (changing the spacing, capitalization etc but not the file's contents), one can use the `biber` command, present in TeX distributions.

The script `biber-and-git-add` creates this normalized version and adds the file to the staging area. Python and the `biber` program are necessary, and the script is intended to be run from a Unix terminal or Git Bash session (in Windows).

After saving the file, instead of running `git add Thermo-Foam-Ref.bib`, run `biber-and-git-add Thermo-Foam-Ref.bib`, and proceed to commit the changes.
