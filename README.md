
# Constructing the Corpus of Chinese Textual ‘Run-on’ Sentences (CCTRS)

## Project Description

This repository contains resources for the project "Constructing the Corpus of Chinese Textual ‘Run-on’ Sentences (CCTRS): Discourse Corpus Benchmark with Multi-layer Annotations". This study focuses on creating a specialized Chinese discourse corpus on “run-on” sentences, combining the annotation strengths of PDTB and RST.

## Motivation

“Run-on” sentences are a typical and prevalent form of discourse/text in Chinese. Despite their widespread use, previous studies have only explored “run-on” sentences using small-scale examples. To address this gap and facilitate computational tasks in realistic contexts, we have developed this discourse corpus.

## Corpus Details

- **Corpus Size**: 500 “run-on” sentences
- **Annotation Levels**: Discourse, Syntax, Semantics
- **Annotation Frameworks**: Rhetorical Structure Theory (RST), Penn Discourse Treebank (PDTB)
- **Validation**: Tested using three state-of-the-art discourse parsers

## Features

- **Integrated Annotation Pipeline**: Combines the strengths of RST and PDTB
- **Comprehensive Annotations**: Multi-layer annotations provide rich insights into Chinese discourse
- **Benchmark Dataset**: Serves as a benchmark for evaluating discourse parsing in Chinese

## Applications

The CCTRS can be used for various computational linguistics and linguistics research tasks, including:
- Co-referential zero anaphora resolution
- Predicting semantic leaps in sentences
- Evaluating discourse parsing performance

## Repository Structure

- `data/`: Contains the annotated corpus
- `scripts/`: Includes scripts for processing and analyzing the corpus
- `docs/`: Documentation and resources related to the project

## How to Use

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/CCTRS.git
   ```
2. **Navigate to the project directory**:
   ```sh
   cd CCTRS
   ```
3. **Explore the data and scripts**: The `data/` directory contains the annotated corpus, and the `scripts/` directory includes tools for processing and analysis.

## Contributors

- [Your Name](https://github.com/yourusername)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project was supported by [Your Organization/Institution].

---

Feel free to explore, contribute, and provide feedback. Thank you for your interest in the CCTRS project!

## Installation

To get started with the project, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/CCTRS.git
   ```
2. **Navigate to the project directory**:
   ```sh
   cd CCTRS
   ```
3. **Install dependencies** (if any):
   ```sh
   pip install -r requirements.txt
   ```

## Usage

### Data Preprocessing

Use the scripts provided in the `scripts/` directory to preprocess the data. Example:

```sh
python scripts/preprocess_data.py --input data/raw --output data/processed
```

### Running Analysis

Run the analysis scripts to process the annotated corpus:

```sh
python scripts/run_analysis.py --input data/processed --output results
```

## Documentation

Detailed documentation is available in the `docs/` directory. This includes the annotation guidelines, data schema, and usage examples.

## Contact

For any questions or issues, please open an issue on GitHub or contact [Your Email](mailto:youremail@example.com).

---

Feel free to explore, contribute, and provide feedback. Thank you for your interest in the CCTRS project!



