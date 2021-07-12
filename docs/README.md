# Write Documentation for you Code

Clear and organized documentation about the code will help users to reuse the code and collaborators to easily understand the code.
Split documentation in two types: end-user documentation and developer's documentation.

- **End-user's documentation** must include steps for installing and use the code via examples.
- **Devoper's documentation** must describe the insides of the code in detailed, or at least good enough such that a collaborator (developer) can quickly set a development environment and get start change the code.

## How to Document?

- Use Docstrings, a.k.a **in-code documentation**. Programming languages usually allow you to include comment; make good use of them while you're typing a program. Avoid using comments to explain what is obvious in the code, or to keep zombie code. Read some recommendations on [how to use in-code documentation.](https://coderefinery.github.io/documentation/in-code-documentation/)
- Write lengthy explanations, how to guides, or tutorials using dedicated **documentation generators**, e.g. [Sphinx](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html), [JupyterBook.](https://jupyterbook.org/). Usually, a large or complex code base required documentation outside the code itself. Reading about how to [write good software documentation](https://documentation.divio.com/) will get you started.


> This file should be removed once you have understood the importance of documenting for your code.