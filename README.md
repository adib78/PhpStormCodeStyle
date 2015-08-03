# PhpStorm Code Style

## How to copying code style settings
---------------------------

In Ubuntu 14.04:
Copy CodingStandard.xml file to  PHPStorm directory
```sh
$ cp CodingStandard.xml /home/user/.WebIde90/config/codestyles/CodingStandard.xml
```

---------------------------

## How create a copy of code style settings

1. In the Code Style page, select the desired scheme from the drop-down list, and click Manage.
2. In the Code Style Schemes dialog box that opens, click Save As....
3. In the Save Code Style Scheme As dialog box, type the name of the new scheme.
WebStorm saves the new code style with the specified name in the config/codestyles/<code_style_name>.xml file under the WebStorm home directory.
4. Close the Code Style Schemes dialog box, and apply changes.


## How reformatting Source Code

### Reformatting code for module or directory

1. In the project tool window, select module or directory to which you want to apply your reformatting.
2. From the main menu, select Code | Reformat Code or press Ctrl+Alt+L.
Alternatively, in the project tool window, right-click the directory and from the context menu, select Reformat Code.
3. In the Reformat Code dialog box, specify the necessary options and filters for you reformatting and click Run.

### Reformatting code for the current file

1. In the editor of the currently opened file, press Ctrl+Shift+Alt+L.
Note that if you select Code | Reformat Code from the main menu or press Ctrl+Alt+L, PhpStorm will try to reformat the source code automatically without opening the Reformat File dialog.
2. In the Reformat File dialog, specify options for the reformatting and click Run.


## Link to documentation

* [Copying Code Style Settings](https://www.jetbrains.com/webstorm/help/copying-code-style-settings.html)
* [Reformatting Source Code](https://www.jetbrains.com/phpstorm/help/reformatting-source-code.html)



### Version
1.0