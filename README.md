# UVA Data Science Core Extension Pack

This VS Code extension pack supports students in the University of Virginia School of Data Science.

## Extensions Included

The following extensions are installed in this pack:

- AutoDocstring
- ChatGPT
- Claude Code
- Code Spell Checker
- Docker
- GitHub Codespaces
- IntelliCode
- Jupyter
- Jupyter Renderers
- Magic Python
- Markdown All In One
- MongoDB
- MySQL
- Pylance
- Python
- Python Debugger
- Python Environment Manager
- Quarto
- R
- Rainbow CSV
- Remote Development
- Remote Containers
- Remote SSH
- Remote WSL
- Remote Explorer
- Remote Server
- SQL Tools
- VS Live Share
- YAML

## Installation

- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=uva-school-of-data-science.sds-vscode)
- Within the VS Code extension pane search for "UVA Data Science".

## Publish a New Version

The text file version in the repo does not get increased with each publication
or version no. since that is now enabled via `git tag` and the GitHub Action.

To publish a version that is ready, simply tag the commit with the next ticked
version number (`0.1.11`, `0.2.4`, etc.) and then push that tagged commit back
to origin:

    git add / commit / etc.
    git tag 0.1.11
    git push origin main 0.1.11

The build process will create the binary artifact and publish it to the VS Code
Marketplace. Look for the new version to be available within 5-10 minutes, as it
must be verified before it is visible.

Publishing uses a PAT assigned to nem2p@virginia.edu.
