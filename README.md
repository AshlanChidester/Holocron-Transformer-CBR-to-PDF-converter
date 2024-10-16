# Holocron-Transformer-CBR-to-PDF-converter
# 

Transform your comic book archives with the power of the Force! Holocron Transformer is a Python-based command-line tool that converts CBR files to PDF format, designed specifically for macOS (including Apple Silicon).

```
    _    _       _                          _____                      __                            
   | |  | |     | |                        |_   _|                    / _|                           
   | |__| | ___ | | ___   ___ _ __ ___  _ __ | | _ __ __ _ _ __  ___| |_ ___  _ __ _ __ ___   ___ _ __ 
   |  __  |/ _ \| |/ _ \ / __| '__/ _ \| '_ \| || '__/ _` | '_ \/ __|  _/ _ \| '__| '_ ` _ \ / _ \ '__|
   | |  | | (_) | | (_) | (__| | | (_) | | | | || | | (_| | | | \__ \ || (_) | |  | | | | | |  __/ |   
   |_|  |_|\___/|_|\___/ \___|_|  \___/|_| |_\_\_|  \__,_|_| |_|___/_| \___/|_|  |_| |_| |_|\___|_|   
```

## Features

- Batch convert multiple CBR files to PDF format
- Maintains image quality and order
- Supports nested directories
- macOS optimized (including M1/M2 chips)
- Star Wars themed progress messages
- Simple command-line interface

## Prerequisites

Before you begin your Jedi training, ensure you have:

- Python 3.x installed
- macOS operating system
- Homebrew package manager

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/holocron-transformer.git
cd holocron-transformer
```

2. Install the required system dependencies using Homebrew:
```bash
brew install unar
```

3. Install the required Python packages:
```bash
pip3 install Pillow
```

## Usage

### Convert a Directory of CBR Files

```bash
python3 holocron_transformer.py /path/to/your/comics
```

The script will:
- Process all CBR files in the specified directory
- Create PDF versions with the same names
- Preserve the original CBR files
- Display progress with Star Wars-themed messages

### Example

```bash
python3 holocron_transformer.py ~/Downloads/Comics
```

## Output

The converter will create PDF files in the same directory as your CBR files:
- `comic1.cbr` → `comic1.pdf`
- `comic2.cbr` → `comic2.pdf`

## Important Notes

- Existing PDF files with the same names will be overwritten
- The script processes files sequentially
- Large files may take some time to process
- Make sure you have sufficient disk space for both CBR and PDF files

## Troubleshooting

### Common Issues

1. If you see "command not found: unar":
```bash
brew install unar
```

2. If you see "ModuleNotFoundError: No module named 'PIL'":
```bash
pip3 install Pillow
```

3. If the script can't find your directory:
- Make sure to use the full path
- Check for spaces in the path (use quotes if necessary)

## Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License

## Acknowledgments

- Inspired by the Jedi Archives
- Built for comic book enthusiasts
- Special thanks to the open-source community

