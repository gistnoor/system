While saving the project, in your ``sublime-project`` file, a ``syntax_override`` section need to be added to get a specic syntax for the overall project.

```javascript
{
    "folders":
    [
        // Your project folders
    ],

    "syntax_override": {
        "\\.html$": ["Handlebars", "grammars", "Handlebars"],
        "\\.js$": ["Babel", "JavaScript (Babel)"]
    }
}
```
