## Password Generator

A stylish password generator with a cyberpunk-inspired GUI built using Flet. This project allows you to generate secure, random passwords of varying lengths and save them to a .docx file for future use. It combines functionality with an aesthetic, futuristic design.

# Features
	•	Random Password Generation: Supports lengths of 10, 12, or 15 characters.
	•	Password List Management: Displays a table of generated passwords within the app.
	•	Save to File: Exports generated passwords to a passwords.docx file.
	•	Customizable UI:
	•	Dark theme with a cyberpunk aesthetic.
	•	Neon accents in yellow and cyan.

# Tech Stack
	•	Python: Core programming language.
	•	Flet: For building the GUI.
	•	python-docx: For creating .docx files to save passwords.
	•	secrets: For secure password generation.

# How It Works
	1.	Set Password Length: Input your desired password length (10, 12, or 15 characters).
	2.	Generate Passwords: Click the Generate Passwords button to create a batch of 10 random passwords.
	3.	Save Passwords: Save the generated passwords to a .docx file with a single click.

# Installation
	1.	Clone the repository:
```bash
git clone https://github.com/yourusername/cyberpunk-password-generator.git
```

	2.	Navigate to the project folder:
```bash
cd cyberpunk-password-generator
```

	3.	Install dependencies:
```bash
pip install -r requirements.txt
```

	4.	Run the app:
```bash
python app.py
```
# Dependencies
```bash
	pip install flet
  pip install python-docx
```

# Preview

## Customization

# The colors, layout, and styles can be easily modified by tweaking the main() function in the code. For instance:
	•	Change background colors via page.bgcolor.
	•	Modify button styles through their bgcolor and color properties.

# Contributing

Feel free to open issues or submit pull requests to enhance functionality or improve the design!
