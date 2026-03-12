
# Vector Mapping Prototype v1.1

The Vector Mapping Prototype is a Python program that automates the process of capturing screenshots from specific weather-related websites at regular intervals. It utilizes Selenium for web automation, Tkinter for the graphical user interface (GUI), and includes logging functionality for tracking the program's execution.

## Features

- Automated screenshot capture of specific weather-related websites at configurable intervals.
- GUI for user interaction, allowing the user to start and stop the mapping analysis.
- Logging mechanism to track the program's execution, including events, errors, and relevant information.
- Scheduler to run the screenshot capture cycle in 5-minute increments.
- Retry mechanism to handle website loading issues.
- Customizable screenshot directory and interval settings.

## Dependencies

- Python 3.x
- Selenium
- Tkinter

## Setup

1. Install Python 3.x on your system.
2. Install the required dependencies by running:

   ```
   pip install selenium tkinter
   ```

3. Edit `config.py` to set `SCREENSHOT_DIR` and whether Chrome should run headless.
4. Install dependencies from `requirements.txt` (inside a venv):

   ```
   pip install -r requirements.txt
   ```

5. Run the program by executing main.py:

   ```
   python main.py
   ```

## Usage

1. Launch the program by running main.py.
2. The GUI window will appear, titled "Vector Mapping Prototype v1.1".
3. Enter the desired mapping interval (in minutes) in the provided entry field.
4. Click the "Start Mapping Analysis" button to begin the screenshot capture process.
5. The program will automatically capture screenshots of the specified websites at the configured interval.
6. To stop the mapping analysis, click the "Stop Mapping Analysis" button.
7. The captured screenshots will be saved in the specified directory.

## Logging

- The program logs various events, errors, and relevant information during its execution.
- Log files are stored in the "logs" directory, which is automatically created if it doesn't exist.
- Each log file is named after the respective module and has a maximum size of 5 MB. Up to 3 backup log files are maintained.

## Future Enhancements

- Implement additional error handling and recovery mechanisms.
- Allow customization of website links and screenshot naming conventions through the GUI.
- Provide options for selecting different screenshot formats and quality settings.
- Integrate data analysis and visualization capabilities to process the captured screenshots.

## Contact

For any issues or questions, please feel free to contact me.
