# Shadow Download Manager (SDM)

A modern, fast, and user-friendly download manager with a sleek dark theme and powerful features, including an experimental quantum-accelerated download mode.

## Features

- Clean and modern dark theme UI
- Multiple concurrent downloads
- Pause/Resume downloads
- Real-time download speed monitoring
- Customizable download location
- Auto-start downloads option
- Configurable concurrent downloads limit
- Experimental quantum-accelerated download mode for maximum speed
- Sound notifications for download events
- System tray integration
- Automatic dark/light theme detection

## Installation

### Windows

1. Download and run the installer:
   ```bash
   install.bat
   ```
   This will:
   - Create a virtual environment
   - Install all dependencies
   - Create an executable
   - Create a desktop shortcut

### Manual Installation

1. Make sure you have Python 3.7+ installed
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Running from Source
```bash
python sdm.py
```

### Using the Executable
Simply double-click `SDM.exe` in the `dist` folder or use the desktop shortcut.

## Features Guide

### Basic Usage
1. Enter a URL in the download field
2. Click "Start Download" or press Enter
3. Choose save location (or use default)
4. Monitor progress in the downloads list

### Quantum Mode
The experimental quantum mode uses advanced techniques to maximize download speed:
- Multi-connection downloading
- TCP optimization
- System-level tuning
- Adaptive chunk sizing

To enable:
1. Click the quantum mode toggle in the top-right
2. The UI will indicate when quantum mode is active
3. Start your download as normal

Note: Quantum mode works best with:
- Fast internet connections (100Mbps+)
- Modern CPUs
- SSDs for storage

### Settings
Configure various options in the Settings page:
- Default download location
- Maximum concurrent downloads
- Auto-start downloads
- Sound notifications
- Theme preferences
- Network optimizations

## Development

- Version: 1.0.0
- Developer: Tanjil Software
- License: MIT

### Building from Source

1. Install PyInstaller:
   ```bash
   pip install pyinstaller
   ```

2. Create the executable manually:
   ```bash
   pyinstaller --onefile --windowed --icon=sdm_icon.png --name=SDM --add-data "sounds/*;sounds/" sdm.py
   ```

## Requirements

- Python 3.7+
- Modern Windows/Linux/macOS
- 4GB RAM recommended
- SSD recommended for best performance

### Dependencies
- PyQt5 - UI framework
- Requests - HTTP client
- tqdm - Progress bars
- darkdetect - Theme detection
- aiohttp - Async HTTP
- aiofiles - Async file operations
- cryptography - Secure downloads
- psutil - System monitoring

## Troubleshooting

### Common Issues

1. "Download speed is slow"
   - Try enabling quantum mode
   - Check your internet connection
   - Ensure no other downloads are running

2. "Application won't start"
   - Verify Python installation
   - Reinstall dependencies
   - Check system requirements

3. "Quantum mode not working"
   - Verify all dependencies are installed
   - Check system resources
   - Try restarting the application

For more help, please open an issue on GitHub. 
