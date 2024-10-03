# Use markdown and Mkdocs for documentation

MkDocs is a powerful tool that generates static HTML sites from Markdown files. If you want developers to document their work effectively, it's important to keep the documentation close to the code. Markdown is a natural fit for this purpose, as it integrates seamlessly with code repositories. To learn more, visit [mkdocs.org](https://www.mkdocs.org)

## Prerequisite

You need phyton installed. You can install Python using:

- Chocolatey (on Windows)
- Homebrew (on macOS)
- APT (on Linux)
- Python's official installer (from Welcome to Python.org )

Note! This guide works on Windows.

## Steps
### 1 Install Mkdocs
Use pythons package manager pip to install mkdocs

```
$ pip install mkdocs
```
You are now ready to create the document.


### 2 Create site
MkDocs should now be in your path. If not
Locate the mkdocs.exe file in the python installation (C:\ProgramData\chocolatey\lib\python3\tools\Scripts)
Create documentation by Running: mkdocs.exe new my-project
Host the documentation by running: mkdocs.exe serve