# 🎓 PowerPoint Flashcard Creator 📑

## 💡 Overview

The PowerPoint Flashcard Creator is a Python-based command-line program that allows end-users to generate computerized flashcards in PowerPoint (.pptx) format. This tool enhances learning, studying, presentations, and memorization. End-users type questions and answers, and the program formats them as slide sets in the PowerPoint (.pptx) file.

---

## ⚙️ Functions

- **🖥️ Interactive Command-Line Interface** – End-users create flashcards through a guided process.

- **📑 Automatic PowerPoint Generation** – The program saves questions and answers to the main PowerPoint file.

- **🔢 Incremental Set Numbering** – Flashcard sets are numbered sequentially (e.g., Set 001, Set 002).

- **💾 Auto-Save Feature** – The program saves the generated PowerPoint file in the `./output` directory.

- **🧹 Screen Clearing** – The terminal screen clears before displaying the main menu for better readability.

---

## 🚀 Installation Requirements

🛠️ **Python Version:** 3.11 or newer  

---

📦 **Use the git command to clone this GitHub repository**  

```bash
git clone https://github.com/LinuxSystemsEngineer/pptx_flashcard_creator.git
```

---

📦 **Change Directories into your newly cloned GitHub repository:**

```bash
cd pptx_flashcard_creator
```  

--

📦 **Create a segmented python virtual environment:**

```bash
python3 -m venv .segment
```

---

📦 **Activate the segmented python virtual environment:**    

```bash
source .segment/bin/activate
```

---


📦 **Install Required Packages:**  

Run the following command:

```bash
pip3 install -r requirements.txt
```
---

📚 Program Libraries

---

🖼️ python-pptx – Enables PowerPoint slide creation.

🖌️ Pillow – Used for handling images (future enhancement).

---

⚙️ Usage

Run the program using:

```bash
python3 main.py
```
---

📜 Menu Options

---

1️⃣ Create a New Set of Flashcards

- Please enter a question and its corresponding answer.

- Repeat the process for multiple flashcard sets.

- The flashcard sets save to the output.pptx file located in the ./output directory.

---

2️⃣ Exit

- Exits and closes the program.

---



📂 File Structure

---

📂 Project Directory

 ├── 📝 main.py          # Main script
 
 ├── 📜 requirements.txt  # Required Python packages
 
 ├── 📁 output/          # Auto-generated PowerPoint files


---


💡 Notes

---

📁 The program automatically creates the ./output directory if it does not exist.

📝 The current version supports only text-based flashcards.

---

🌟 Future Enhancements

---
🔹 🖼️ Image-Based Flashcards – End-users can insert images into flashcards.

🔹 🎨 Custom Slide Styling – Options to modify font styles, colors, and layouts.

🔹 🖥️ GUI-Based Version – A graphical user interface for enhanced user experience.

---

📜 License

---

This project is free, open-source software and can be shared, reused, and modified as needed. Please see the MIT license.

---
