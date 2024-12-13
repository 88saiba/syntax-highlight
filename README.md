# Mojo Syntax Highlighting for Micro Editor

This explains how to set up syntax highlighting for Mojo files in the Micro editor. It supports files with extensions `.mojo` or `.🔥` and uses Rust syntax highlighting rules as a base.

## Installation

1. Create a syntax configuration directory for Micro (if it doesn’t already exist):
   ```bash
   mkdir -p ~/.config/micro/syntax
   ```

2. Create a `mojo.yaml` file in the directory you just created:
   ```bash
   nano ~/.config/micro/syntax/mojo.yaml
   ```

3. Copy the Mojo syntax rules into the file. Use the following [Mojo Syntax File](path/to/mojo.yaml).

4. Restart Micro for the changes to take effect:
   ```bash
   micro --version # restart your editor
   ```

## Usage

- Open any `.mojo` or `.🔥` file, and Micro will automatically apply syntax highlighting.
- If the highlighting doesn't load automatically, you can manually set the filetype with:
  ```bash
  set filetype mojo
  ```

## Notes

- This configuration uses Rust syntax rules as a base for Mojo, which provides effective syntax highlighting while specific Mojo rules are under development.
- If you encounter issues or have suggestions, feel free to open an issue on this repository.
