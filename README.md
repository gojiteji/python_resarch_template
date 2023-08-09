# Python Research Template

This repository serves as a standardized template for organizing and conducting Python-based research projects. It's optimized for ensuring code quality and facilitating collaboration.

This template was designed for academic research purposes during m master's and PhD journey.

## Directory Structure
```
├── data/                # Raw and processed data
├── .github/
│   ├── PULL_REQUEST_TEMPLATE.md    # Template for pull requests
│   └── workflows/
│       └── ruff.yml      # Workflow for Ruff linting on push and pull requests
├── .gitignore            # List of files and directories to ignore in git
├── LICENSE               # Licensing details
├── logs/                 # Logs for debugging and performance checks
├── models/               # Trained machine learning models and their metadata
├── notebooks/            # Jupyter notebooks
├── pyproject.toml        # Project configurations and settings
└── README.md             # Project documentation
```

markdown
Copy code

## Coding Standards
- The project enforces linting rules using [Ruff](https://github.com/ambv/ruff), with specific rules outlined in `pyproject.toml`.
- When submitting code, please ensure that it adheres to these standards.

## Contributing

1. Clone the repository.
2. Create a new branch.
3. Make your changes.
4. Ensure your code adheres to the coding standards mentioned above.
5. Open a pull request, using the template provided in `.github/PULL_REQUEST_TEMPLATE.md`.

## License

This project is licensed under the terms of the [MIT License](LICENSE).
