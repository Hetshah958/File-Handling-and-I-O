# File Line Extractor

This is a simple Python project for Experiment 8 on file handling and input/output operations.

The program reads a text file, counts the total number of lines, extracts the first two lines, and saves them in a new file.

## Aim

To read data from an input file, count its lines, extract the first two lines, and write the extracted data to a new file.

## Requirements

- Python 3
- No additional libraries required

## How to Run

1. Download or clone this repository.
2. Keep `file_handler.py` and `input.txt` in the same folder.
3. Open a terminal in that folder.
4. Run the command:

```bash
python file_handler.py
```

## Example

The sample input file contains four lines:

```text
This is the first line.
This is the second line.
This is the third line.
This is the fourth line.
```

### Output

```text
Total number of lines: 4
Extracted lines written to output.txt
```

The program creates `output.txt` with the following content:

```text
This is the first line.
This is the second line.
```

## Concepts Used

- File handling in Python
- `open()` for reading and writing files
- `readlines()` to read lines into a list
- `len()` to count lines
- `writelines()` to write the selected lines
- `with` statements to manage files safely

## Conclusion

This experiment demonstrates how Python can read data from a file, count its lines, and copy selected content into another file.

