<div align="center"><h1> KTR/KJB Java Highlighter </h1></div>

Syntax highlighting for Java code embedded in Pentaho Data Integration (PDI) `.ktr` and `.kjb` files.

## Features

✨ **Java Syntax Highlighting** - Full Java syntax highlighting inside `<class_source>` blocks  
🔍 **Code Folding** - Collapse/expand `<class_source>` blocks for easier navigation  

## Usage Tips

### Local installation
1. Clone the repo
2. `npm install -g @vscode/vsce`
2. `vsce package` 
3. `code --install-extension pdi-java-highlighter-0.0.1.vsix`
4. Reload VS Code

### Uploading to Marketplace
1. `vsce login ArmanGrewal007`
2. `vsce publish`
