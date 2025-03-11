# PowerPoint Flashcard Creator

## Overview

The **PowerPoint Flashcard Creator** is a Python-based command-line application that allows users to generate digital flashcards in PowerPoint (.pptx) format. This tool improves studying, presentations, and knowledge reinforcement. Users can input questions and answers, and the program formats them as slides in a PowerPoint file.

## Functions

-   **Interactive Command-Line Interface**: Users create flashcards through a step-by-step guided process.

-   **Automatic PowerPoint Generation**: Questions and answers are neatly formatted and saved into slides.

-   **Incremental Set Numbering**: Flashcard sets are numbered sequentially (e.g., Set 001, Set 002, etc.).

-   **Auto-Save Feature**: The program saves the generated PowerPoint file to the ./output directory

-   **Screen Clearing**: The program clears the terminal screen before displaying the main menu for better readability.

### Installation Requirements

Python version 3.11 or newer.

Install the required packages using the following CLI command:

```bash
pip3 install -r requirements.txt
```

### Program Libraries

-   python-pptx: Enables PowerPoint slide creation.

-   Pillow: Used for handling images (potential future use).

## Usage

Run the program using the following CLI command:

```bash

python main.py

```

### Menu Options

1️⃣ **Create a New Set of Flashcards**

-   Please enter a question and its corresponding answer.
-   Repeat the process for multiple flashcards.
-   The flashcards save the filename output.pptx in the ./output directory.

2️⃣ **Exit**

-   The Exit option closes the program.

## File Structure

📂 Project Directory

├── main.py # Main script

├── requirements.txt # Required Python packages

├── output/ # Auto-generated PowerPoint files

## Notes

-   The program ensures that the ./output directory exists before saving files.
-   The current version supports text-based flashcards.

## Future Enhancements

-   Adding support for image-based flashcards.
    
-   Custom styling options for PowerPoint slides.
    
-   GUI-based version for enhanced user experience.

## License

This project is open-source and can be modified as needed. Contributions and improvements are welcome!
