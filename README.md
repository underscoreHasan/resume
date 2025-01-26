# Resume displayed [here](https://underscorehasan.github.io/resume/resume.pdf)! 📜

I have successfully managed to overengineer my resume

Deployment workflow based on jonhue/pubtex

Since LaTeX code can't be rendered in a GitHub README, this repo instead publicly hosts a compiled LaTeX file as a PDF on GitHub Pages.

It roughly works as follows:

- The LaTeX file is written as normal.
- Whenever changes are pushed to `main`, the LaTeX file is compiled to a PDF by a custom workflow.
- The compiled PDF is then pushed to the `gh-pages` branch.
- The `gh-pages` branch is then published by the default GitHub Pages workflow!
