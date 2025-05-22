# Fair Code
[![TUDelft DCC](https://img.shields.io/badge/tu_delft-DCC-black?style=flat&label=TU%20Delft&labelColor=%23000000%20&color=%2300A6D6)](https://dcc.tudelft.nl)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

A template to make your software more FAIR compliant with the [TU Delft Software Guidelines](https://zenodo.org/records/4629635)

## How to Use
This template requires [Python 3.8+](https://www.python.org/downloads/) 

### New Project
If starting a new project from scratch, you can follow these steps:
1. Use [pipx](https://pipx.pypa.io/stable/installation/) to install `copier`, and render the template.

```shell
# intalling copier
pipx install copier
```

2. Start a new software project using this template:

```python
copier copy https://github.com/manuGil/fair-code.git <path/to/project-directory>
```

3. Finally, initize a Git repository in your project directory:

```shell
cd <path/to/project-directory>
git init
git add . 
git commit -m 'initial commit'
```
### Existing Project

If you have an existing project and want to use this template, you can use the following command:

1. Use [pipx](https://pipx.pypa.io/stable/installation/) to install `copier`, and render the template.

```shell
# intalling copier
pipx install copier
```

2. Make sure your existing project is a Git repository. If not, you can initialize it with:

```shell
cd <path/to/existing-project-directory>
git init    
git add .
git commit -m 'initial commit'
```

3. apply the template to your existing project:
```shell
copier copy https://github.com/manuGil/fair-code.git <path/to/exiting-project-directory> 
```

4. Finally, commit the changes to your exising project:

```shell
git add . 
git commit -m 'apply template to existing project'
```

## Contributing
Read our [guidelines](CONTRIBUTING.md) to know how to be part of the development of this template. 

## License

This template is freely available under an [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)

## Acknowledgements

* [SS NES Meta Template](https://github.com/SS-NES/meta-template)
* [Serious Scaffold Python](https://github.com/serious-scaffold/ss-python)
* [Make a README](https://www.makeareadme.com/)
