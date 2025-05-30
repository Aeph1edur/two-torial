!!! info ""    

    You'll need to manually edit `App\bin\segatools.ini` as segatools has no graphical configuration tool.
    
    We recommend using a text editor with syntax highlighting such as [Notepad++](https://notepad-plus-plus.org/).

    The following sections match those found in `segatools.ini` - skip any sections not listed below.

    If a key already exists in a section, simply change its value after `=`, do not add another key.

    ```ini
    [system]
    dipsw2=1
    dipsw2=1 ; WRONG!
    ```