[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
# Fair Code

A template to make your software more FAIR compliant

## How to Use

1. Use [pipx](https://pipx.pypa.io/stable/installation/) to install `copier`, and render the template.

```bash
# intalling copier
pipx install copier
```

2. Start a new software project using this template:

```python
copier copy https://github.com/<account>/<repo>.git <path/to/project-directory>
```

3. Inialize a Git repository in your templating project

```shell
cd <path/to/project-directory>
git init
git add . 
git commit -m 'initial commit'
```

## Contributing
Read our [guidelines](CONTRIBUTING.md) to know how to be part of the development of this template. 

## License


This templae is freely available under an [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)

## Acknowledgements


* [SS NES Meta Template](https://github.com/SS-NES/meta-template)
* [Serious Scaffold Python](https://github.com/serious-scaffold/ss-python)
* [Make a README](https://www.makeareadme.com/)


