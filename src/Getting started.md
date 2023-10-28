Currently, Keyscript only distributes binaries. As it is still in the works, it is not open-source as of right now. You can still download the binaries from Github Releases though.

To get started, head over to https://github.com/keyscript/keyscript/releases and grab the latest release for your system and architecture. After that, you might want to check out the [CLI reference](CLI%20reference.md).

To use Keyscript, you need to serve the html file containing the JS code.
When running `keyscript init`, you will also generate the `index.html` file.  
Furthermore, running `keyscript ./file.kys gen` will generate the `file.html` containing the necessary JS code for importing all the keyscript functions you created.

> **Tip**  
> You can use the vscode extension `live server` to serve the html file easily.