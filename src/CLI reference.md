
> **Tip**  
> You may have to run `keyscript.exe` on Windows.  
> On both \*NIX and Windows, if the file is not on PATH, you'll have to prefix it with it's path. If it is located in the current working directory, run `./keyscript`.

- Run `keyscript init` to generate the starter files.
- Run `keyscript ./file.kys` to compile a Keyscript file.
- Run `keyscript ./file.kys debug` to compile the file and generate a readable .wat file.
- Run `keyscript ./file.kys gen` to compile the file and generate the necessary JS code to import the functions automatically.
- You can also add `gen` after `debug` for JS code generation.