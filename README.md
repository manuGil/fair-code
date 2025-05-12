# Fair Code

[![TUDelft DCC](https://img.shields.io/badge/tu_delft-DCC-black?style=flat&label=TU%20Delft&labelColor=%23000000%20&color=%2300A6D6)](https://dcc.tudelft.nl)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-black.json)](https://github.com/copier-org/copier)

A template to make your software project FAIR and compliaint with the [TU Delft Guidelines.](https://zenodo.org/records/4629635)

## How to Use

This template requires [Python 3.8+](https://www.python.org/downloads/) 

1. Use [pipx](https://pipx.pypa.io/stable/installation/) to install `copier`, and render the template.

```bash
# intalling copier
pipx install copier
```

2. Start a new software project using this template:

```python
copier copy https://github.com/manuGil/fair-code.git <path/to/project-directory>
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
