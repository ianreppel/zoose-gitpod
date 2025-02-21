# Gitpod workspace for [Zoose](https://github.com/ianreppel/zoose)

Do you want to run Zoose or [Zoose Quantum](https://ianreppel.org/zoose-2.0/#zoose-quantum) without installing _anything_, not even Docker?

1. Create an account on [Gitpod](https://gitpod.io).
1. Click "Use this template" at the top right to create a copy of this repository in your GitHub account.
1. [Create a workspace](https://www.gitpod.io/docs/introduction/getting-started#start-your-first-workspace) in Gitpod from the repository you created in the previous step.
1. Enjoy a hosted notebook experience with VSCode and JupyterLab from your browser.

If you do not want to include any quantum libraries, change `databaseline/zoose-quantum-gitpod:3.0.1` to `databaseline/zoose-base-gitpod:3.0.1` in `.gitpod.yml`.

It is not recommended that you switch the image tag to "latest", as that may have unintended consequences on existing notebooks.
