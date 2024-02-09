# Hello, we are the Code Crafters

## Description

In today's digital age, the management of PDF documents is crucial for businesses and organizations across various sectors. A streamlined workflow is essential to handle the influx of information effectively. This introduction provides an overview of a systematic approach to managing PDF documents, encompassing data preprocessing, categorization, priority scheduling, and printing. By employing these strategies, organizations can optimize their document management processes, ensure timely handling of critical information, and enhance overall productivity. Let's delve into the key components of this workflow.

## Getting Started

# Dependencies

This project requires the following Python modules:

- `torch` - An open-source machine learning library, a scientific computing framework, and a script language based on the Lua programming language.
- `pandas` - A fast, powerful, flexible, and easy-to-use open-source data analysis and manipulation tool.
- `transformers` - A library that provides general-purpose architectures for Natural Language Understanding (NLU) and Natural Language Generation (NLG) with over thousands of pretrained models.
- `sklearn` (scikit-learn) - A simple and efficient tool for predictive data analysis.
- `os` - A standard Python module that provides a way to use operating system-dependent functionality.
- `joblib` - A set of tools to provide lightweight pipelining in Python, particularly suited for jobs involving large datasets.
- `fitz` - A Python library to create and manipulate PDF files (part of PyMuPDF).
- `shutil` - A Python module for high-level file operations, including copying and archiving.

To install the required modules (except for the standard library modules `os` and `shutil` which are included with Python), you can run the following command:

```bash
pip install torch pandas transformers scikit-learn joblib PyMuPDF
'''bash

### Installing

After cloning the repository and installing the required dependencies, you may need to make modifications to the file paths.

## Executing the Program

This project involves three main steps: training the model, testing the model, and prioritizing files to printer based on the assigned priority. Follow these steps in order to ensure the system functions correctly:

### Step 1: Training the Model

Begin by running the training script, which will train the machine learning model on your dataset.

```bash
python train.py

Once the model is trained, proceed to test its performance with the testing script.

```bash
python test+.py

After testing, run the prioritization script to organize your files based on the priority assigned by the model.

```bash
python priority+.py

## Contributors

This project exists thanks to all the people who contribute. A big thank you to:

- **D Ankith** - (https://github.com/ankithdadda)
- **Poornachandra A N** - (https://github.com/Heisenberg208)
- **Sri Vishnu VS** - (https://github.com/srivishnuvs)
- **Yashwanth M** - (https://github.com/yashwanthm998)

