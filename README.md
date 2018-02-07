# Windows Debugging Resources

This repository contains many useful commands and files to use with Microsoft Windows Debugging tools (windbg and cdb)

## Tips

### Utilize "&" as alias to run scripts!


```shell
al & $>>a<
& <MyScript>\run.wd 
```

### Import the notepad++ user defined style to wd scripts

[This file](extras/notepadpp_wd.udl.xml) can be imported on notepad++ used defined style.
It will apply syntax color the files with "wd" extensions by default. You can change this and customized on your way.