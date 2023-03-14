# myjettools.github.io


# Prepare your laptop to Develop in Rust

## First of all

* [Rust itself](https://www.rust-lang.org/tools/install)
* Visual code




### Must have visual studio plugins
<img src="https://rust-lang.gallerycdn.vsassets.io/extensions/rust-lang/rust-analyzer/0.4.1436/1678755432954/Microsoft.VisualStudio.Services.Icons.Default" width="32" height="32">[Rust-analyzer - To develop](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)<br/>
<img src="https://vadimcn.gallerycdn.vsassets.io/extensions/vadimcn/vscode-lldb/1.9.0/1678521297683/Microsoft.VisualStudio.Services.Icons.Default" width="32" height="32">[lldb - to debug](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb)<br/>
<img src="https://serayuzgur.gallerycdn.vsassets.io/extensions/serayuzgur/crates/0.5.10/1633510597451/Microsoft.VisualStudio.Services.Icons.Default" width="32" height="32">[crates - to make sure that last versions of crates are injected](https://marketplace.visualstudio.com/items?itemName=serayuzgur.crates)<br/>

### Better to have
* [Todo-tree - to highlight todo!("Implement lines")](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
* [Github copilot - to boost your productivity](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) 
* [Better toml - to handle toml file better](https://marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml)
* [Error lens - to handle errors better](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
* [Code-spell-checker - Not to misspell words](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
* [Bookmarks - to handle bookmarks in code](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
* [vscode-proto3 - to handle proto files better](https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3)



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
