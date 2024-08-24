# Basic Keylogger

**Basic Keylogger** is a simple Python script designed to log keystrokes and save them to a file. This tool uses the `pynput` library to capture and record keyboard events.

**Note:** This project is intended for educational purposes only. Ensure you have explicit permission to use this keylogger and comply with all legal and ethical guidelines.

## Features

- **Keystroke Logging**: Records each key pressed on the keyboard.
- **Log File**: Saves keystrokes to a text file with timestamps.

## Installation

### Prerequisites

Make sure you have Python 3.x installed on your machine.

### Install Required Libraries

Install the `pynput` library using pip:

```bash
pip install pynput
```

## Usage

1. **Clone the Repository**

   Clone this repository to your local machine:

   ```bash
   git clone https://github.com/DevRaas/BasicKeylogger.git
   cd BasicKeylogger
   ```

2. **Run the Script**

   Execute the keylogger script:

   ```bash
   python keylogger.py
   ```

3. **Log File**

   The keylogger will start running and log keystrokes to `keylog.txt`. The log file will be created in the same directory as the script.

4. **Stopping the Keylogger**

   To stop the keylogger, press the `Esc` key. This will terminate the script.

### Example

After running the script, you can check the `keylog.txt` file for recorded keystrokes.

```
2024-08-25 12:34:56: a
2024-08-25 12:34:57: b
2024-08-25 12:34:58: c
```

## Important Considerations

- **Ethical Use**: This tool should only be used with explicit permission on systems you own or have authorization to monitor. Unauthorized use of keyloggers is illegal and unethical.
- **Privacy**: Handle logged data with care to respect privacy and data protection laws.
- **Anti-Virus Software**: Some anti-virus programs may flag this script due to its nature. This is a common precaution for tools that can be used maliciously.

## Disclaimer

**Use of this keylogger is at your own risk.** The creators of this tool are not responsible for any misuse or legal consequences arising from its use. Always ensure you have proper authorization before deploying this tool, and respect all applicable laws and privacy regulations. This keylogger is intended for educational purposes and should only be used in ethical and legal contexts.

## Contributing

Contributions to this project are welcome. If you have suggestions for improvements or bug fixes, please follow these steps:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## Contact

For questions or feedback, please contact [roshanajith7911@gmail.com](mailto:roshanajith7911@gmail.com).

## Acknowledgements

- Thanks to the `pynput` library for handling keyboard events.
