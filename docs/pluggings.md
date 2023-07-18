<h1>MkDocs Plugins</h1>
---

### Installing Plugins

Before a plugin can be used, it must be installed on the system. If you are using a plugin which comes with MkDocs, then it was installed when you installed MkDocs. However, to install third party plugins, you need to determine the appropriate package name and install it using pip:
```
pip install mkdocs-foo-plugin
```

Once a plugin has been successfully installed, it is ready to use. It just needs to be enabled in the configuration file. The Best-of-MkDocs page has a large list of plugins that you can install and use.

### Using Plugins

The plugins configuration option should contain a list of plugins to use when building the site. Each "plugin" must be a string name assigned to the plugin (see the documentation for a given plugin to determine its "name"). A plugin listed here must already be installed.

```
plugins:
    - search
```