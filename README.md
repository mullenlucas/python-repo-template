# {{ cookiecutter.project\_name }}

{{ cookiecutter.description }}

## Requirements

[!\[Python Version\](https://img.shields.io/badge/python-{{ cookiecutter.python\_version }}-blue.svg)]()
* Python {{ cookiecutter.python\_version }} or higher

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)

## Installation

Install `virtualenv` if you haven't already:

```bash
pip install virtualenv
```

### Create a Virtual Environment

```bash
python -m venv venv
```

### Activate the Virtual Environment

**Windows:**

```bash
./venv/Scripts/activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

**Git Bash (Windows):**

```bash
. venv/Scripts/activate
```

Ensure you're using the correct interpreter:

```bash
which python       # macOS/Linux
where python       # Windows
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Save Dependencies to `requirements.txt`

```bash
pip freeze > requirements.txt
```

### Optional: Deactivate the Virtual Environment

```bash
deactivate
```

## Usage

Run the entry point (adjust if necessary):

```bash
python src/main.py
```

Or if it's a module:

```bash
python -m module_name
```

## Contributing

Contributions are welcome! Please fork the repository, create a new branch for your changes, and submit a pull request.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
