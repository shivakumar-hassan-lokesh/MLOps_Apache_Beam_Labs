# Apache Beam Lab

This lab demonstrates a simple **WordCount pipeline** using **Apache Beam (Python SDK)**. The notebook reads a text file (`alice_large.txt`) located in the `data/` folder, extracts and counts words, and saves the output as a `.txt` file inside the `outputs/` directory.

## Features
- Apache Beam **DirectRunner**
- Reads input text file from `data/`
- Word extraction using a custom `DoFn`
- Word frequency counting using `Count.PerElement()`
- Output in tuple format: `('WORD', count)`
- Result saved as a `.txt` file in `outputs/`

## Project Structure
.
├── alice_large.txt
├── part-00000-of-00001.txt
├── Try_Apache_Beam_Python.ipynb
└── README.md

## How to Run the Lab

1. Install Apache Beam - pip install apache-beam

2. Open the Jupyter Noteboob- jupyter notebook Try_Apache_Beam_Python.ipynb

3. Run the notebook cells - Cell 1: Selects the input file and Cell 2: Runs the Apache Beam WordCount pipeline

4. View the output- The generated file will appear here:  outputs/part-00000-of-00001.txt

## Example Output

('CHAPTER', 200)

('ALICE', 160)

('RABBIT', 90)

...


## Technologies Used

Python 3

Apache Beam (DirectRunner)

Jupyter Notebook


