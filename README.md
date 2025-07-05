# CV Gen

CV Gen is a Python script that generates a professional CV (Curriculum Vitae) in Microsoft Word format from a YAML configuration file. It uses the `python-docx` library to create and style the document, making it easy to customize and automate CV creation.

## Features
- Generate a CV from structured YAML data
- Customizable headings, sections, and formatting
- Outputs a `.docx` file with modern fonts and styles

## Requirements
- Python 3.7+
- [python-docx](https://python-docx.readthedocs.io/en/latest/)
- [PyYAML](https://pyyaml.org/)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/cv-gen.git
   cd cv-gen
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your `default.yaml` YAML file (see `template.yaml` for an example structure).
2. Run the script:
   ```bash
   python cv_gen.py
   ```
   To use a different YAML file, run:
   ```bash
   python cv_gen.py --yaml other_file.yaml
   ```
3. The generated CV will be saved in the `output` directory.
   - If `default.yaml` is used, the filename will be `CV - <your name> - YYYY-MM.docx`.
   - If a non-default YAML file is used, the filename will be `CV - <yaml filename> - YYYY-MM.docx`.


## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.
