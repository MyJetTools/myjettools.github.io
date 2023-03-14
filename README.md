# myjettools.github.io


# Prepare your laptop to Develop in Rust

## First of all

* [Rust itself](https://www.rust-lang.org/tools/install)
* Visual code

### Must have visual studio plugins
* [Rust-analyzer - To develop](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
* [lldb - to debug](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb)
* ![Image](https://serayuzgur.gallerycdn.vsassets.io/extensions/serayuzgur/crates/0.5.10/1633510597451/Microsoft.VisualStudio.Services.Icons.Default)[crates - to make sure that last versions of crates are injected](https://marketplace.visualstudio.com/items?itemName=serayuzgur.crates)

### Better to have
* [Todo-tree - to highlight todo!("Implement lines")](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
* [Github copilot - to boost your productivity](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) 
* [Better toml - to handle toml file better](https://marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml)
* https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens - to handle errors better;
* https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker - Not to misspell words;
* https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks - to hansle bookmarks in code;
* https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3 - to handle proto files better;



### Just good to know they are exists
* https://marketplace.visualstudio.com/items?itemName=ms-vscode.hexeditor - To observe information in Hex;
* https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory - working with git history;
* https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph - other git tool;
* https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio - to keep diagrams inside your project


# When you develop

if you code does not compule - before you go to blame person who updates library just try:

* to delete target follder;
* then execute
```bash
cargo update
cargo build
```
