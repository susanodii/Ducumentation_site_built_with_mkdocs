<h1> Translations</h1>
---
The built-in themes that are included with MkDocs provide support for translations. This is a guide for translators, which documents the process for contributing new translations and/or updating existing translations. For guidance on modifying the existing themes, see the Contributing Guide. To enable a specific translation see the documentation about the specific theme you are using in the User Guide. For translations of third-party themes, please see the documentation for those themes. For a third-party theme to make use of MkDocs' translation tools and methods, that theme must be properly configured to make use of those tools.

### Localization tooling prerequisites

Theme localization makes use of the babel project for generation and compilation of localization files. You will need to be working from the git working tree on your local machine to make use of the translation commands.

See the Contributing Guide for direction on how to Install for Development and Submit a Pull Request. The instructions in this document assume that you are working from a properly configured development environment.

Make sure translation requirements are installed in your environment:
```
pip install mkdocs[i18n]
```

### Adding language translations to themes