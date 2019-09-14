# Be an RSE Superhero with VS Code and Azure Pipelines

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://dev.azure.com/trallard/rse19-demo/_apis/build/status/trallard.rse19-demo?branchName=azure-pipelines)](https://dev.azure.com/trallard/rse19-demo/_build/latest?definitionId=7&branchName=azure-pipelines)

In this workshop, we will show you how you can incorporate VS Code and Azure
Pipelines into your day-to-day workflow as an RSE, helping you to be more
productive and accomplish common tasks with greater ease. 

VS Code is an
easily extensible, cross-platform code editor that has support for a
wide array of different languages and toolchains. We will show you how
extensions like Live Share (which let small groups edit the same files in
different editors), Azure Tools (which provides a rich suite of interactions
with Azure) and Remote Development (which lets you work locally
but run code remotely) can give you RSE superpowers in your day-to-day
work. We will also walk you through how to use Azure Pipelines to provide
simple yet powerful Continuous Integration and Deployment functionality
for your projects, from  multi environment testing to automated building and
deployment of your solutions. Come along and learn how VS Code and Azure
Pipelines can empower you to do more.

## Getting Started


### Windows
```
python -m venv .env
.env\Scripts\activate

pip install -r requirements.txt
bokeh serve iris
```

### Mac/Linux
```
python -m venv .env
source .env/bin/activate

pip install -r requirements.txt
bokeh serve iris
```

## Requirements

- Install [VSCode](https://code.visualstudio.com//?wt.mc_id=rse19-github-taallard)
- Once installed click on the following link to install the[VSCode Remote development extension pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack&WT.mc_id=rse19-github-taallard) and click on Install, this will launch VSCode and start the installation. You might be asked for further confirmation.
- Next install the Azure CLI, follow [this link](https://docs.microsoft.com/cli/azure/install-azure-cli?view=azure-cli-latest&WT.mc_id=rse19-github-taallard) for the detailed installation instructions.
- Finally, install [Azure CLI tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azurecli&WT.mc_id=rse19-github-taallard)


✨Note that you will need to clone this repository to follow along with the excercises. 

