# Whisperkey Fork with OpenAI Integration

## Overview

This repository is a fork of the original [Whisperkey](https://github.com/original-repo/Whisperkey) Swift package. In this fork, I have added functionality to send transcribed text to the OpenAI API.

## Changes Made

1. **OpenAI Integration**: Added code to send transcribed text to the OpenAI API for further processing.
2. **Credentials Removal**: Removed OpenAI API key credentials from this repository to ensure security and privacy. 

## Setup Instructions

To use this fork, you need to configure your own OpenAI API key. Follow these steps to set it up:

1. **Obtain an API Key**:
   - Sign up or log in to [OpenAI](https://www.openai.com/).
   - Go to the API section and generate a new API key.

2. **Configure Your API Key**:
   - Clone this repository to your local machine.
   - Open the project in Xcode.
   - Add your OpenAI API key to the project. You can do this by:
     - Adding the API key to your app's configuration file or
     - Setting it as an environment variable.

3. **Build and Run**:
   - Build the project in Xcode.
   - Run your application to test the new OpenAI integration.

## Contribution

If you have any questions, find bugs, or want to contribute to this project, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Note**: Please remember to keep your API keys secure and do not hard-code them in your source files.