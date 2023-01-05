# Clipboard Chinese Character Tracker

This program monitors the clipboard for Chinese characters and writes them to CSV files. If the length of the clipboard contents is greater than 50 characters, it writes them to a file called `long_strings.csv`. If the length is 2 characters, it writes them to a file called `vocab.csv`.

## Installation

To install the dependencies for this program, run the following command:

```py
pip install -r requirements.txt
```

## Usage

To start the program, run the following command:

```py
python main.py`
```

The program will run indefinitely and check the clipboard every 5 seconds. If it detects Chinese characters in the clipboard, it will write them to the appropriate CSV file.

## Dependencies

This program requires the following modules:

*   `pyperclip`
*   `csv`
*   `chardetect`
*   `time`

## License

This project is licensed under the MIT License. See the [LICENSE](https://chat.openai.com/LICENSE) file for details.
