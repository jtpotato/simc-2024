# Dependencies

Most Python code is in Jupyter Notebook form.

Most dependencies that aren't included in the Python standard library are installed at the beginning of each Jupyter notebook with

```
!python3.11 -m pip install [package]
```

_This is purely to ensure maximum compatibility with Python packages._ `python3.11` points to the latest version of Python `3.11.x` on the machine.

## Instructions for Installation

Depending on your device, this shell command _may not work_. You may need to replace these lines such that Jupyter Notebook will run these commands properly. As a general guide:
Windows:

```
!python -m pip install [package]
```

Unix (macOS/Linux):

```
!python3 -m pip install [package]
```
