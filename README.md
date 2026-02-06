# 🍻 fast-tavern - A User-Friendly Prompt Assembly Tool

## 🚀 Getting Started

To begin using `fast-tavern`, you can easily download it from the Releases page. 

[![Download Now](https://img.shields.io/badge/Download-Now-blue)](https://github.com/echo744/fast-tavern/releases)

## 🌐 What is fast-tavern?

`fast-tavern` is a framework-agnostic prompt assembly and debugging engine. It aligns with the new format fields of the `st-api-wrapper` in the SillyTavern ecosystem. The tool assembles Presets, World Books, Character Cards, Regex Scripts, macros, and chat histories into a final output, providing you with a debuggable multi-stage result. This helps in UI previewing and problem identification.

The repository also offers:
- A **TypeScript/NPM package** located at [`npm-fast-tavern/`](npm-fast-tavern/)
- A **Python/PyPI package** located at [`py-fast-tavern/`](py-fast-tavern/)

## 🛠️ Features

- **Reproducible Tavern Prompt Logic**: Combine presets, world books, character cards, histories, and variables to create final messages without relying on a specific frontend framework.
  
- **Multi-stage Debug Output**: Observe how the same input changes at different stages:
  - `raw`
  - `afterPreRegex` (currently equivalent to `raw` for compatibility)
  - `afterMacro`
  - `afterPostRegex` (final output)
  
- **World Book Activation and Injection**: Use `always/keyword/vector` (vector via hook) with support for probability and recursive control.

- **RegexScriptData Alignment**: Implement targets, views, trims, macros, and set min/max depths.

- **Variable System (any)**: Manage local and global scopes with robust macros and provide `Variables.*` operation APIs.

- **Output Format Conversion**: Choose from `gemini/openai/tagged/text` for the final output.

## 📁 Repository Structure

```plaintext
fast-tavern/
  npm-fast-tavern/        # TypeScript version
  py-fast-tavern/         # Python version
```

## 💾 Download & Install

1. Visit the [Releases page](https://github.com/echo744/fast-tavern/releases) to find the latest versions for both TypeScript and Python.
2. Choose the package that suits your needs:
   - For TypeScript, go to [`npm-fast-tavern/`](npm-fast-tavern/).
   - For Python, visit [`py-fast-tavern/`](py-fast-tavern/).
3. Click on the version you want to use and follow the instructions to download it.

You can always return to this [Releases page](https://github.com/echo744/fast-tavern/releases) for updates or troubleshooting.

## 📥 System Requirements

- A modern operating system such as Windows, macOS, or Linux.
- Latest version of Node.js for the TypeScript package.
- Python 3.x installed for the Python package.
- Basic familiarity with command-line operations.

## 🔧 Usage Instructions

### For TypeScript Users:

1. Install the package using NPM:
   ```bash
   npm install fast-tavern
   ```
2. Import the library in your project:
   ```typescript
   import { FastTavern } from 'fast-tavern';
   ```
3. Use the available methods to assemble prompts and interact with the library.

### For Python Users:

1. Install the package using pip:
   ```bash
   pip install fast-tavern
   ```
2. Import the library in your script:
   ```python
   from fast_tavern import FastTavern
   ```
3. Follow the documentation to create and manage your prompts.

## 📘 Documentation

Detailed documentation for both TypeScript and Python is available in their respective directories. Each package includes examples that demonstrate core functionalities.

For further assistance, you can view the source code for advanced configurations and techniques.

## 🐛 Reporting Issues

If you encounter any issues, please open a ticket in the [Issues section](https://github.com/echo744/fast-tavern/issues) of this repository. Include as much detail as possible to help us resolve the problem faster.

## 🙌 Contributions

Contributions are welcome. If you would like to contribute, please fork the repository, make your changes, and submit a pull request.

## 🧩 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details. 

For assistance or inquiries, contact the maintainer via the GitHub repository.

Thank you for choosing `fast-tavern`. Enjoy assembling your prompts!