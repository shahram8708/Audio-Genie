# Audio Genie 🤖

Audio Genie is a Flask-based web application designed to analyze and generate insights from audio files. It utilizes Google’s Generative AI to process and create content based on user-uploaded audio files. This application provides a user-friendly interface for uploading audio files, adding custom prompts, and receiving processed content in Markdown format.

## Features

- **Audio Upload**: Upload audio files directly from your device.
- **Custom Prompts**: Add custom text prompts to guide the content generation.
- **Content Generation**: Generate insightful content based on the uploaded audio.
- **Markdown Rendering**: View the generated content in a formatted Markdown preview.
- **Interactive Elements**: Copy content to clipboard, read aloud with text-to-speech, and stop audio playback.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- An API key for Google Generative AI (set as an environment variable `API_KEY`)

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/shahram8708/audio-genie.git
    cd audio-genie
    ```

2. Create a virtual environment:

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies:

    ```sh
    pip install -r requirements.txt
    ```

4. Set up the API key for Google Generative AI:

    ```sh
    export API_KEY='your_google_generative_ai_api_key'  # On Windows use `set API_KEY=your_google_generative_ai_api_key`
    ```

### Running the Application

1. Run the Flask application:

    ```sh
    python app.py
    ```

2. Open your web browser and navigate to `http://127.0.0.1:5000` to access the application.

### Usage

1. **Upload Audio File**: Click the "Choose Audio File" button to select an audio file from your device.
2. **Add Custom Prompt**: Enter any specific instructions or questions in the textarea.
3. **Analyze Audio**: Click the "Analyze Audio" button to upload the file and process it.
4. **View Results**: The generated content will be displayed in Markdown format below the upload section.

### Project Structure

- `app.py`: The main Flask application file.
- `templates/`: Contains HTML files for rendering the web interface.
- `static/`: Contains CSS and JavaScript files used by the application.
- `uploads/`: Directory where uploaded audio files are temporarily stored.
- `requirements.txt`: Lists the dependencies for the project.

### Troubleshooting

- Ensure that your API key for Google Generative AI is correctly set as an environment variable.
- Check the logs for any error messages if the application fails to start or process files.

### Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome!

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy analyzing with Audio Genie! 🎉
