# bigBang
A Python project that iterates through 1 to 100 and replaces any number divisible by 3 with the word BIG, any number divisible by 5 with the word BANG, and any number divisible by 3 and 5 with BIG BANG.

## Requirements

- Python 3.x

## How to Use

1. Clone this repository to your local machine using `git clone` or download the ZIP file.

2. Open a terminal or command prompt and navigate to the project directory.

3. Run the `main.py` file by executing the following command:

   python main.py

4. After running the script, the results will be saved in a file named `output.json` in the project directory. The `output.json` file will contain the array in JSON format with the replaced numbers.

## Sample Output

The output in `output.json` will be similar to the following:

```json
[1, 2, "BIG", 4, "BANG", "BIG", 7, 8, "BIG", "BANG", 11, "BIG", 13, 14, "BIG BANG", ... all the way to 100]

