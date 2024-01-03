# Installation

To activate your virtual environment, you would use different commands depending on your operating system.

`python3.11 -m venv .venv`

For Unix or MacOS, use:

`source .venv/Scripts/activate`

For Windows, use:

`.\.venv\Scripts\activate`

These commands will activate the virtual environment, which means that your Python-related terminal commands will now run within this isolated environment, rather than using your system-wide Python installation.

## Install packages

`pip install pandas matplotlib numpy scikit-learn ipykernel`
`pip list`