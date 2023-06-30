**File Integrity Checker**

This script provides a simple command-line tool for calculating the MD5 and SHA-256 hashes of a file. It utilizes the hashlib library in Python to perform the hash calculations. The script takes a single argument, which is the path to the file for which you want to calculate the hashes. After processing the file, it prints the MD5 and SHA-256 hashes to the console.

To use the script, run it in the following format:

```
python file_integrity_checker.py <file_path>
```

**Arguments:**
- `file_path`: Path to the file for which to calculate the MD5 and SHA-256 hashes.

**Example:**
```
python file_integrity_checker.py /path/to/file
```

The script handles various scenarios, such as file not found, permission denied, and general errors while reading the file. If any of these issues occur, an appropriate error message is displayed.

This script can be helpful in verifying the integrity of files, especially when you want to compare hash values with the original file to ensure it hasn't been tampered with. It can be incorporated into other automation or security-related workflows.

*Author: Djefferson Saintilus*