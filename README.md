# cpk-code-style
Code style guidelines files

#### How to set different code indent for .php and .phtml files
Create file `.editorconfig` in your project root directory.
Write following rules to the file:

```
[*]
charset=utf-8

[*.php]
indent_style=space
indent_size=4

[*.phtml]
indent_style=space
indent_size=2
```
 
Go to PhpStorm settings: `File > Settings > Editor > Code Style > tab General > section EditorConfig` and enable checkbox `Enable EditorConfig support`.
 
Now, rules in the file will override rules in the PhpStorm Settings dialog.

More info about EditorConfig rules: https://editorconfig.org/
