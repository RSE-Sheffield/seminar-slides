# Seminar Slides

This repository contains slides for the RSE Seminars, keeping large binary files out of the main site repository.


## Adding Files

1. Create a new branch
2. Add file(s) to this repository, in the root directory, or a sub-directory.
3. Commit files to the `seminar-slides` repository
4. Open a PR against the `gh-pages` branch.

## Linking to files

Files will be available at `https://rse.shef.ac.uk/seminar-slides/file.pdf` for `file.pdf`, or `https://rse.shef.ac.uk/seminar-slides/subdir/file.pdf` for `subdir/file.pdf`


## index.html

`index.html` is a simple placeholder to avoid a 404 error page if a user manually modifies their URL, although a custom 404 would also be acceptable. 

The placeholder simply redirects to the root of the RSE website, via `<meta http-equiv="refresh">`.


