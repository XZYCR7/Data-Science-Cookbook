> Written with [StackEdit](https://stackedit.io/).

## Jupyter Lab extension for Git


- [Jupyter extensions](https://github.com/jupyterlab)
- [`jupyterlab-git` extension](https://github.com/jupyterlab/jupyterlab-git)

To install `jupyterlab-git` extension:

First: follow this [article](https://www.taniarascia.com/how-to-install-and-use-node-js-and-npm-mac-and-windows/). 

1. Install `Node.js` from here https://nodejs.org/en/ on your Windows Machine
2. Using Windows Cmd console check if `Node.js` is installed: `node -v` and `npm -v`
3. Now follow the steps on -   [`jupyterlab-git`  extension](https://github.com/jupyterlab/jupyterlab-git) using Windows Cmd console:

To install preform the following steps:
```bash
jupyter labextension install @jupyterlab/git
pip install jupyterlab-git
jupyter serverextension enable --py jupyterlab_git
```
Finally, open a Jupyter Lab extension and you will see something like this:

![](https://docs.aws.amazon.com/sagemaker/latest/dg/images/jupyterlab-git.png)

[Here](https://annefou.github.io/jupyter_publish/02-git/index.html) there is nice explanation about how to start using  `jupyterlab-git` extension.


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQ4ODc5MDk4NSwtMTQ1MjA4MDA2MF19
-->