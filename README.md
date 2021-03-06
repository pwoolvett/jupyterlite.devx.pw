# JupyterLite

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://jupyterlite.devx.pw)


JupyterLite deployed as a static site. [Reference Implementation](https://github.com/jupyterlite/demo)


## Requirements

JupyterLite is being tested against modern web browsers:

- Firefox 90+
- Chromium 89+



### Further Information and Updates

For more info, keep an eye on the JupyterLite documentation:

- Configuring: https://jupyterlite.readthedocs.io/en/latest/configuring.html
- Deploying: https://jupyterlite.readthedocs.io/en/latest/deploying.html

### Deploy a new version of JupyterLite

To change the version of the prebuilt JupyterLite assets, update the `jupyterlite` package version in the [requirements.txt](./blob/main/requirements.txt) file.

The `requirements.txt` file can also be used to add extra prebuilt ("federated") JupyterLab extensions to the deployed JupyterLite website.

## Development


_Add any additional requirements as required to the `requirements.txt` file.__

*You can do this via the Github website by selecting the `requirements.txt` file, clicking to edit it, making the required changes then saving ("committing") the result to the `main` branch of your repository.*

__Modify the contents of the `contents` folder to include the notebooks you want to distribute as part of your distribution.__

*You can do this by clicking on the `contents` directory and dragging notebooks from your desktop onto the contents listing. Wait for the files to be uploaded and then save them ("commit" them) to the `main` branch of the repository.*

Check that you have Github Pages enabled for your repository: from your repository [*Settings*](./settings) tab, select the [*Pages*](./settings/pages) menu item and ensure that the source is set to `gh-pages`.

When you commit a file, an updated release will be built and published on the Github Pages site. Note that it may take a few minutes for the Github Pages site to be updated. Do a hard refresh on your Github Pages site in your web browser to see the new release.

Then follow the steps documented in the [Configuring](https://jupyterlite.readthedocs.io/en/latest/configuring.html) section.
