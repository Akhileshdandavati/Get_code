# Code Context Generator

## Description
This script generates a text file containing the content of all files within specified directories in the project directory, excluding certain file types. The generated text file provides a context of the code structure within the project.

## Usage
1. Place the script (`get_code`) in the root directory of your project.
2. Customize the `directories` and `ignore_files` arrays in the script to specify the directories to include and the file types to ignore, respectively.
3. Run the script by executing `./get_code` in your terminal.
4. The generated `code_context.txt` file will be saved in the project directory, containing the concatenated content of all non-ignored files.

## Example
```bash
./get_code

```

## Note
Ensure that the script has execute permissions (`chmod +x get_code`) before running it.
Review the generated `code_context.txt` file to understand the code structure and context within your project.