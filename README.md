# emlab-manual

A manual for all things emLab: <https://emlab-ucsb.github.io/emlab-manual/)>

## Table of Contents

1. Welcome
2. Mission and research identity
3. emLab culture and values
4. Code of conduct
5. Expectations
6. Feedback and growth
7. Project scoping and selection
8. emLab workflow and platforms
9. Project management
10. Communications and outreach
11. Onboarding
12. Offboarding
13. Housekeeping
14. Parent resources

## Contributing

The website is built using the `bookdown` package for R. After pulling the latest updates and adding or revising content, use the following command to render the website:

`bookdown::render_book(input = "index.Rmd")`

To produce a clean build of the website, simply delete the 'docs' folder before rendering, which is where generated files are stored. Once rendered, then commit the changes and push to the repo. The GitHub website will automatically update with the new changes.
