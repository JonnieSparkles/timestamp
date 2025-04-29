# Unix Timestamp Converter

A simple, browser-based tool for converting between Unix timestamps and human-readable dates/times.

## Features

- Real-time display of current Unix timestamp with copy functionality
- Convert date/time to Unix timestamp
- Convert Unix timestamp to date/time
- Support for both local and UTC timezone conversions
- Light, dark, and system theme options
- Intelligent detection of millisecond vs. second timestamps
- Educational information about Unix timestamps and the Year 2038 problem
- Clean, responsive interface
- Copy-to-clipboard functionality for all results

## Usage

### Current Unix Timestamp
The current Unix timestamp is displayed at the top of the page and updates every second. Click the "Copy" button to copy it to your clipboard.

### Converting Time/Date to Unix Timestamp
1. Select a date and time using the datetime picker
2. Choose your timezone (Local or UTC)
3. Click "Convert" to see the corresponding Unix timestamp
4. Use the Copy button to copy the result

### Converting Unix Timestamp to Time/Date
1. Enter a Unix timestamp in the input field (in seconds)
2. Choose your desired timezone for the result (Local or UTC)
3. Click "Convert" to see the corresponding date and time
4. The converter will automatically detect if you've entered a millisecond timestamp by mistake

### Theme Options
Use the theme buttons in the top-right corner to switch between:
- Light theme (☀️)
- Dark theme (🌙)
- System theme (💻) - follows your device's preference

## Installation

Simply download the `timestamp.html` file and open it in any modern web browser. No additional dependencies or installation required - wild!

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- No external dependencies
- Modular code organization using modern JavaScript patterns
- Fully client-side processing
- Responsive design that works on both desktop and mobile devices
- Support for keyboard navigation (use Enter key to submit)
- Theme preference saved between sessions
- Includes meta tags for social media sharing

## Contributing

Feel free to submit issues and enhancement requests!

## Credits

Created by @JonnieSparkles

## License

This project is released into the public domain under the CC0 1.0 Universal (CC0 1.0) Public Domain Dedication.

To the extent possible under law, all copyright and related or neighboring rights to this work have been waived. You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

For more information: https://creativecommons.org/publicdomain/zero/1.0/