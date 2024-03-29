# SubtitleAI

SubtitleAI is a __local executable__ program that utilizes artificial intelligence to generate subtitles for videos. It uses advanced machine learning algorithms to analyze audio content and generate accurate and synchronized subtitles. Using WhisperAI and FFMPEG.

## Installation

To install SubtitleAI, follow these steps:

1. Clone the repository: `git clone https://github.com/BigMakCode/SubtitleAI.git`
2. Install the .NET 8.0: https://dotnet.microsoft.com/en-us/download
3. Build application from Sources: dotnet build --configuration Release --output ./build SubtitleAI.csproj
4. Run application: dotnet .\build\SubtitleAI.dll D:\Temp\daily\input.mp4

## Usage

To use SubtitleAI, follow these steps:

1. Navigate to the project directory: `cd SubtitleAI`
2. Run the program: `SubtitleAI path_to_input_video_file`

## What's next?

1. The program will download WhisperAI model and FFMPEG library in temporary folder.
2. Your media file will be converted to WAVE file.
3. WhisperAI will recognize text from this file.
4. Text will be created as subtitles file (.srt)


## Contact

For any questions or suggestions, please contact the project maintainer.
