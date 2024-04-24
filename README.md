<img
  src="https://raw.githubusercontent.com/kube/vscode-42header/master/42.png" 
  width=128>

# Costum 42 Header for VSCode

This extension provides a costum header integration in VS Code forked from the offical 42 header repo

```bash
#*--------------------------------------------------------------------------------------*#
#*                                                                                .|    *#
#*     $FILENAME__________________________________    /     (__)          |/            *#
#*                                                          (oo)------/'   ,__,    ,    *#
#*     By: $AUTHOR________________________________       |  (__)     ||    (oo)_____/   *#
#*                                                             ||---/||    (__)    ||   *#
#*     Created: $CREATEDAT_________ by $CREATEDBY_    |/                 ,    ||--w||   *#
#*                                                  ,,       !              |'          *#
#*                                                       ,           ,|             |/  *#
#*----------------8<------------------[ mooooooo ]--------------------------------------*#



#.~"~._.~"~._.~"~._.~"~.__.~"~._.~"~._.~  EOF  ~._.~"~.__.~"~._.~"~._.~"~._.~"~._.~"~._.~#
```

## Install

Launch Quick Open with <kbd>⌘</kbd>+<kbd>P</kbd> and enter
```
ext install 42header
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.


## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "42header.username": string,
  "42header.email": string
}
```


## Issues

In case of a bug, or missing feature, please create a [Github Pull Request](https://github.com/kube/vscode-42header/pulls).

## License

MIT
