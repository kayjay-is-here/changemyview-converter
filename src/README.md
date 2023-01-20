# README

## Introduction

This program converts data obtained from the subreddit r/changemyview into a cleaner format for further data processing. The data is not clean enough to be used directly in a model yet, and additional preprocessing is required.

## Data Format

The cleaned data is stored in an Apache Parquet file with the following columns:

| Column Name | Description |
| --- | --- |
| INSTRUCTION | Post title + body text |
| RESPONSE | Arguments attempting to change OP's mind of `INSTRUCTION` |
| SOURCE | Permalink to the reddit post |

## Usage

To use the program, follow these instructions:

1. **Clone the repository** - `git clone https://github.com/LAION-AI/Open-Assistant.git`
2. **Navigate to the project directory** - `cd notebooks/data-augmentation/changemyview-builder`
3. **Open the Jupyter Notebook** - `jupyter notebook data_processor.ipynb`
4. **Run the program** - Go through the notebook and run the cells

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the Apache-2.0 License - see the [LICENSE](LICENSE) file for details.