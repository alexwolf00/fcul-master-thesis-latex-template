# Master's Thesis Template

This is a $\LaTeX$ template for a FCUL Master's thesis written in English.

The structure of this template is loosely inspired by the [`templates_latex_fcul`](https://github.com/dpavot/templates_latex_fcul) GitHub repository.


## How To Use This Template

Get a copy of [src](src) and edit the `*.tex` files in [chapters](src/chapters) as needed. If your thesis structure differs from the generic one in [template_output.pdf](src/template_output.pdf), edit [main.tex](src/main.tex) and add, remove, and/or rename the other `*.tex` files as needed.
Once you're ready to get a `.pdf` output, compile `main.tex`.


## Document Norms

This template follows the official FCUL layout norms for the **2024/2025** academic year, which I have preserved in [normas_trabalho_final_2025.pdf](normas_trabalho_final_2025.pdf). It is your responsibility to verify whether these norms have been updated. As of date of the last commit, the official FCUL norms can be found [here](https://ciencias.ulisboa.pt/pt/node/12432/#toc2) or [here](https://ciencias.ulisboa.pt/en/academic-examination-admission-2nd-cycle#toc2).

If you'd like to see this template updated, feel free to make a pull request.


## VSCode Workspace Settings
To be able to compile your document in VSCode, include the settings provided in [settings.json](src/.vscode/settings.json) in your workspace `settings.json` file. If you copied [src](src) as is, this is already taken care of.
