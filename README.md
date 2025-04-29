# 📘 Odoo 17 Converge Modules Documentation

Welcome! This repository contains a curated, cherry-picked selection of documentation for **Odoo 17**, focusing specifically on the **Converge** modules.

Whether you're here to read, build, or contribute—this guide has you covered.

## Build the documentation locally

### Requirements

- Git
- Python 3.6, 3.7, or 3.8
- Python dependencies listed in the file `requirements.txt`.
- Make
- A local copy of the [odoo/odoo repository](https://github.com/odoo/odoo) (optional)
- A local copy of the [odoo/upgrade-util repository](https://github.com/odoo/upgrade-util) (optional)

## 🚀 Getting Started

1. In a terminal, navigate to the root directory of the documentation and build it `make`.
   Additional commands are available with `make help`.
2. Open the file `documentation/_build/html/index.html` in your web browser.
3. See [this guide](https://www.odoo.com/documentation/latest/contributing/documentation.html)
   for more detailed instructions.

Optional: place your local copy of the `odoo/odoo` and `odoo/upgrade-util` repositories in
the parent directory or in the root directory of the documentation to build the latter
with the documented Python docstrings.

## 🛠️ Editing the Layout

To customize the look and feel of the documentation (such as headers, structure, or layout components), you can modify the layout templates located at:

`extensions/odoo_theme/layout_templates/`

These templates are written using Jinja2 and HTML, and control the overall structure of the generated pages.

## 📄 Notes

This documentation is built using Sphinx.
Make sure to install the required dependencies (if any) using:

`pip install -r requirements.txt`

## Learn More

To learn more about Odoo, in addition to the documentation, have a look at
[the official eLearning](https://odoo.com/slides) and
[Scale-up, The Business Game](https://www.odoo.com/page/scale-up-business-game).
