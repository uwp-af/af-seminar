# App Factory Seminar Sessions

Welcome to the App Factory Seminar Repo. This will be a work in progress containing the markdown files for each class. I will be making it build its respective pdf files and a website from the sources.

## Building Latex (PDF)

To build on your machine you need latex installed along with pandoc. on windows you can install MikTex to achieve this and run:

```ps1
pandoc .\android.md -o android.pdf --pdf-engine xelatex --template ./eisvogel.latex
```

To build the pdfs (replace android with the file to build and pdf-engine with other latex distros as needed)

## Building Jekyll (Website)

Site will auto build on deploy. To build on your machine you will need to install Ruby, Jekyll, and Bundler. To serve for testing first run `bundle install` to grab dependencies and `bundle exec jekyll serve` to run the dev server. It will rebuild on file changes but you must reload the page to see those changes.