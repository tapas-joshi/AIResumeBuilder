# AIResumeBuilder

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Usage](#usage)
4. [Dependencies](#dependencies)
5. [Documentation](#documentation)
6. [Troubleshooting](#troubleshooting)
7. [How to Contribute](#how-to-contribute)
   - [Web Designers](#web-designers)
   - [Prompt Engineers](#prompt-engineers)
   - [Software Engineers](#software-engineers)
   - [Other Contributions](#other-contributions)
8. [License](#license)
9. [Disclaimer](#disclaimer)

## Introduction

`AIResumeBuilder` is a Python lib designed to simplify the creation of personalized, professional resumes. By integrating with GPT models, this library allows you to generate resumes that are tailored to specific job descriptions and formatted in various styles. It provides a flexible approach to resume building with minimal effort.

## Features

- **Dynamic Resume Styling:** Use different pre-defined styles to create visually appealing resumes.
- **Job Description Integration:** Customize resumes based on job description URLs.
- **Flexible Configuration:** Set up resume details using YAML configuration files.
- **Interactive CLI:** Easily generate resumes via an interactive command-line interface.

## Dependencies

`AIResumeBuilder` requires the following Python packages:

- `langchain`
- `langchain-community`
- `langchain-core`
- `langchain-openai`
- `langchain-text-splitters`
- `langsmith`
- `openai`
- `regex==2024.7.24`
- `selenium==4.9.1`
- `webdriver-manager==4.0.2`
- `inquirer`
- `faiss-cpu`


## Documentation

Here’s a detailed documentation for each module in the `AIResumeBuilder` library:

## Build Locally

To build the project locally, follow these steps:

1. **Clone the Repository**:
   - If you haven't already, clone the repository to your local machine:
     ```bash
     git clone https://github.com/tapas-joshi/AIResumeBuilder
     cd AIResumeBuilder
     ```

2. **Set Up a Virtual Environment (Optional but Recommended)**:
   - Create a virtual environment to isolate your project dependencies:
     ```bash
     python -m venv venv
     ```
   - Activate the virtual environment:
     - On **Windows**:
       ```bash
       venv\Scripts\activate
       ```
     - On **macOS/Linux**:
       ```bash
       source venv/bin/activate
       ```

3. **Install Dependencies**:
   - Install the necessary dependencies listed in `requirements.txt` (if present):
     ```bash
     pip install -r requirements.txt
     ```

4. **Build and Install the Package Locally**:
   - Use `pip` to build and install the package locally:
     ```bash
     pip install .
     ```

   - Alternatively, for development purposes, you can install the package in "editable" mode, which reflects changes to your code immediately:
     ```bash
     pip install -e .
     ```

5. **Verify the Installation**:
   - To verify that the package has been installed correctly, try importing it in a Python shell:
     ```python
     python
     >>> import your_package_name
     ```

6. **Run the Application**:
   - Once installed, you can run the application or use the package in your projects as needed.


## Troubleshooting

For issues, open an issue on GitHub

## Contributors

- [feder-cr](https://github.com/feder-cr) - Creator and Lead Developer
- [tapas-joshi] (https://github.com/tapas-joshi) - Developer

## How to Contribute

We welcome contributions to `AIResumeBuilder`! Whether you are a designer, prompt engineer, software engineer, or have other skills, here’s how you can help:

### Web Designers

Enhance resume templates with improved visual design. [Learn more.](how_to_contribute/web_designer.md)

### Prompt Engineers

Help refine prompts for better resume customization. [Learn more.](how_to_contribute/prompt_engineer.md)

### Software Engineers

Submit pull requests to improve functionality or fix bugs. [Learn more.](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)

### Other Contributions

You can also contribute by:
- Reporting issues
- Suggesting new features
- Improving documentation


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

`AIResumeBuilder` is designed to assist with resume creation. While it aims to be helpful, the service may not cover all specific requirements for every job application. We assume no responsibility for the quality or accuracy of the generated resumes.

