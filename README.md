# Project Name

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Description

A brief description of your project goes here.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

Instructions on how to install and set up your project.

## Usage

Instructions on how to use your project.

## Contributing

Guidelines on how others can contribute to your project.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or want to collaborate, feel free to reach out to me at [email@example.com](mailto:email@example.com).

## Annotations:

dvc stage add -n prepare -d src/prepare.py -o dataset/full_data.csv python3 src/prepare.py

dvc stage add -n training -d dataset/full_data.csv -d src/train.py python3 src/train.py