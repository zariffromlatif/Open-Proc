# OpenProc Python Project

## Overview

This Python project demonstrates how to use the `ctypes` library to interact with the Windows API, specifically by opening a handle to a process using the `OpenProcess` function from `Kernel32.dll`.

## Features

- Opens a handle to a specified process by its ID.
- Handles and reports any errors that occur during the process.
- Validates the creation of the handle and provides feedback.

## Requirements

- Python 3.x
- A Windows operating system (required to use `Kernel32.dll`).

## Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/zariffromlatif/OpenProc-Python.git
   cd OpenProc-Python
   ```

2. **Run the Script:**

   Make sure you have Python installed. Run the script by navigating to the project directory and executing:

   ```bash
   python OpenProc.py
   ```

## Usage

When you run the script, it attempts to open a handle to the process with the specified process ID (`0x22b8`). The script will print whether the handle was successfully created or if an error occurred.

## Error Handling

If there is an issue with calling the Windows API functions, the script will print the error code and exit.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue.

## Contact

For any inquiries or feedback, please reach out to zariffromlatif@gmail.com

---

Feel free to customize the details to your liking!
