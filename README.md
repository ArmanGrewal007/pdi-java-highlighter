# KTR/KJB Java Highlighter

Syntax highlighting for Java code embedded in Pentaho Data Integration (PDI) `.ktr` and `.kjb` files.

## Features

✨ **Java Syntax Highlighting** - Full Java syntax highlighting inside `<class_source>` blocks  
🔍 **Code Folding** - Collapse/expand `<class_source>` blocks for easier navigation  
⚡ **Quick Snippets** - Type `class_source` to insert a new Java code block  
🎯 **Symbol Search** - Use Cmd+Shift+O to navigate to `<class_source>` blocks quickly

## Usage Tips

### Navigate Large XML Files

1. **Fold Everything**: Press `Cmd+K Cmd+0` to fold all sections
2. **Unfold Class Source**: Click the fold arrows next to `<class_source>` tags
3. **Symbol Navigation**: Press `Cmd+Shift+O` and type "class_source" to jump between blocks

### Insert New Java Code

Type `class_source` and press Tab to insert a new `<class_source>` block with cursor ready for coding.

### Search for Java Blocks

Use `Cmd+F` and search for `<class_source>` to quickly jump between Java code sections in large files.

## Installation

1. Download the `.vsix` file
2. Run: `code --install-extension pdi-java-highlighter-0.0.1.vsix`
3. Reload VS Code

## Supported Files

- `.ktr` - Kettle Transformation files
- `.kjb` - Kettle Job files

## License

MIT License - see LICENSE file for details
