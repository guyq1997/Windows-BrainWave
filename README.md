# BrainWave-Windows

A Windows application that helps reorganize and improve your natural language expression through voice input, inspired by [grapeot's BrainWave project](https://github.com/grapeot/brainwave). This Windows version transforms the original web-based implementation into a native desktop application for enhanced integration with the Windows ecosystem.

## Features

- Quick activation through hotkey (Ctrl+Alt+M)
- Real-time voice recognition and processing
- Floating window interface with drag-and-drop positioning
- Background operation for seamless workflow
- Integration capabilities with other automation tools and agents
- Sophisticated text processing and readability enhancement
- Error correction and improved punctuation
- Multilingual support

## Installation Requirements

1. System requirements:
   - Windows 10 or higher
   - Python 3.8 or higher (if installing from source)

2. Installation Methods:

   1. Clone the repository:
      ```bash
      git clone https://github.com/guyq1997/Windows-BrainWave.git
      cd BrainWave-Windows
      ```

   2. Install dependencies:
      ```bash
      pip install -r requirements.txt
      ```
   3. create .env file with OPENAI_API_KEY

   4. Run the build script:
      ```bash
      python build_app.py
      ```

   5. Find the packaged application in the `dist` directory

## Usage Guide

1. First-time setup requires configuring environment variables (in the `.env` file)
2. The application runs in the background after launch
3. Use hotkey `Ctrl+Alt+M` to open the recording window
4. Click the red button to start recording
5. Click again or press `Esc` to stop recording
6. Use `Ctrl+Alt+Q` to exit the application

## Hotkeys

- `Ctrl+Alt+M`: Toggle recording window
- `Ctrl+Alt+Q`: Exit application

## Key Features and Benefits

- Improves natural language expression and readability
- Serves as an interface for computer interaction
- Can be integrated with other automation tools and agents
- Enables voice-controlled task automation
- Potential for expanding functionality through additional agents

## Troubleshooting

Please check the following if you encounter issues:
1. Microphone permissions are enabled
2. Environment variables are correctly configured
3. System meets minimum requirements

## Future Potential

This application can serve as a foundation for:
- Creating voice-controlled automation scripts
- Developing personal digital assistants
- Building task-specific agents
- Integrating with other productivity tools
- Extending the original BrainWave capabilities with Windows-specific features

## Credits

This project is inspired by and builds upon [grapeot's BrainWave project](https://github.com/grapeot/brainwave), transforming it into a native Windows application while maintaining its core functionality of real-time speech recognition and text enhancement.

## License

[Add License Information]

## Contributing

Contributions are welcome! Please feel free to submit pull requests or create issues for bugs and feature requests.
