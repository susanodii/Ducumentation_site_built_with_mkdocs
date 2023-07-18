<h1>Customizing Your Theme</h1>


If you would like to make a few tweaks to an existing theme, there is no need to create your own theme from scratch. For minor tweaks which only require some CSS and/or JavaScript, you can use the docs_dir. However, for more complex customizations, including overriding templates, you will need to use the theme custom_dir setting.

<h2>Using the docs_dir</h2>

The extra_css and extra_javascript configuration options can be used to make tweaks and customizations to existing themes. To use these, you simply need to include either CSS or JavaScript files within your documentation directory.

For example, to change the color of the headers in your documentation, create a file called extra.css and place it next to the documentation Markdown. In that file add the following CSS.