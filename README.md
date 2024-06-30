# my_package

![Read the Docs](https://img.shields.io/readthedocs/my_package?style=flat-square)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/my_package?style=flat-square)

**my_package** is a python library to ...

<p align="center">
  <img src="docs/images/my_package.png" alt="Your Image" width="200">
</p>

Check the [documentation](https://my_package.readthedocs.io/en/latest/) for more information about the installation and the complete user guide.

# Installation

You can install the library via pip:

```bash
pip install my_package
```

Although it is recommended to install it following the [installation guide](https://my_package.readthedocs.io/en/latest/install.html).


# Generate favicon

[Favicon generator](https://favicon.io/favicon-generator/)

# Workflows

- add_assets.yml: automatically create release and add assets when a tag is pushed to remote. To automatically include tags on pushes, run:

```bash
git config --global push.followTags true
```

- python_publish.yml: automatically publish the package to PyPI when a tag is created. As releases are created from github actions, it has to run on ``workflow_run`` instead of on ``push``.


# Bump my version

```bash
bump-my-version bump {major, minor, patch}
```

