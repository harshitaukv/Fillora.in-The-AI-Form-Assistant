Fillora.in- The AI Form Assistant

Description:
Fillora AI Form Assistant is a Python-based program that demonstrates the use of AI for extracting information from text and auto-filling forms. It uses a Named Entity Recognition (NER) model from Hugging Face to detect entities such as Name, State, Date of Birth, 
Aadhaar Number, University, and Email. Additionally, the program creates and displays an image of the filled form for visualization.

Features:
1. Loads a pre-trained NER model (dslim/bert-base-NER) for entity extraction.
2. Processes input text (simulated document content) to detect key personal information.
3. Prints recognized entities and auto-fill suggestions in the console.
4. Generates a visual representation of the form as an image using Pillow (PIL).
5. Displays the filled form image in a separate window.

Requirements:
1. Python 3.x
2. Libraries:
   - transformers
   - torch (for model backend)
   - pillow (PIL)
   - warnings (standard library)

Usage:
1. Open the Python file `fillora_demo.py' and execute the code
2. The console will display:
- Input text
- Detected entities
- Auto-filled form suggestions
3. An image window will open displaying the filled form.

Notes:
- The NER model may take some time to load initially (internet connection required for the first run).
- The form image uses a simple design; it can be enhanced with tables, borders, and fonts.
- For GPU usage, change `device=-1` to `device=0` in the NER pipeline initialization.


