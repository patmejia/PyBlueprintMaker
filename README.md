# PyBlueprintMaker

`PyBlueprintMaker` is a Python-based project scaffolding tool that helps you create well-organized project structures using best-practices, `fixtures`, `pytest`, and the Python Standard Library. With support for various folder configurations and comprehensive testing, PyBlueprintMaker is the ultimate solution for maintainable projects.

![scaffolds](assets/scaffolds.jpeg)

## Why is File Structure Important?

A well-organized file structure is crucial for any software project. It makes your code easier to understand, navigate, and maintain. Following best practices for file structure ensures consistency across projects, which can be especially helpful when collaborating with others or when you revisit your project after some time.

## Best Practices

Some best practices for organizing Python projects include:

- Separating source code and test code into different folders.
- Using meaningful and descriptive names for files and folders.
- Including a `README.md` file to provide an overview and usage instructions.
- Adding a `LICENSE` file to specify the terms under which the project can be used.
- Grouping related files together, such as scripts for different project structures.

## Installation

To install PyBlueprintMaker, you can use `pip`:

```sh
# WIP: Installing as package
pip install PyBlueprintMaker
```

Alternatively, you can install from source by cloning this repository and running:

```
python setup.py install
```

Make sure to also include any necessary dependencies that are not automatically installed.

## Usage

To use PyBlueprintMaker, run the following command:

```
python main.py [output_path] [structure]

```

Where `output_path` is the desired output path for the project structure and `structure` is the project structure to create. The supported structures are `web_app`, `data_science`, or `modular`.

For example, to create a `web_app` project structure in a folder named `my_project`, run the following command:

```
python main.py my_project web_app

```

## Outputs and Structures

PyBlueprintMaker supports four project structures: `etl`, `modular`, `ml`, and `web`.

- The `etl` structure is designed for data engineering projects and includes directories for src, tests, and data with subdirectories for extract, transform, and load. This structure helps ensure the separation of concerns and promotes modularity in data processing.

- The `modular` structure is intended for projects that consist of reusable modules that perform specific functions. It includes directories for src and tests, with the option to specify the module names as arguments. This structure helps facilitate code reuse and modular design.

- The `ml` structure is designed for machine learning projects and includes directories for src, tests, and data with subdirectories for data and models. This structure promotes good coding practices for machine learning, including separate data and model subdirectories, and separate preprocess, features, train, and evaluate scripts.

- The `web` structure is intended for web application projects and includes directories for src, tests, static, and templates. This structure follows best practices for web development, with src containing the application logic, static containing static files such as CSS and JavaScript, and templates containing the HTML templates.

## Contributing

If you find any issues or have suggestions, feel free to open an issue or submit a pull request.

## License

PyBlueprintMaker is licensed under the [MIT LICENSE](LICENSE).

## Support

If you like this project, please consider sharing a coffee. Thank you! 🦉

<a href="https://www.buymeacoffee.com/patimejiaS" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
