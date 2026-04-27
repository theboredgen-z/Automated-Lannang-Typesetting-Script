# Yuji-s-Automated-Lannang-Typesetting-Python-Script

**My Intention for this Project (The "Why")**
This project was born out of a massive logistical challenge faced by my friend while compiling a dictionary with over 10,000 entries. He realized that the encoding process was a primary target for human error; manual typesetting would inevitably lead to typos, inconsistent formatting, and broken sorting. To transfer every entry from an Excel file into a Word document one-by-one would have taken months, or more, of tedious work, and would likely result in a flawed final product. 

My approach to this project is not as an expert in linguistics or typography, but as a problem-solver. Thus, I built this script to act as a "Digital Editor" that takes raw spreadsheet data and transforms it into a production-ready Word document in seconds, following the specific order and formatting my friend required for publication.

**Tools & Libraries**
The pipeline is built on a sequence of lightweight but important and essential tools. Firstly, it begins with (1) pandas and (2) openpyxl, which act as the engines for the "Data Ingestion Phase." Thus allowing the script to read and interpret the structure of the Excel spreadsheets. To handle the delicate work of identifying specific language markers within the text (such as phonetic notations inside brackets) I used the standard (3) re (Regular Expressions) library. Finally, the "Generation Phase" is powered by (4) python-docx, which I used to programmatically "draw" the dictionary layout, creating a document object where every bold headword and italicized part of speech is placed with mathematical precision.

For more details and the specifics of the underlying logic, formatting, or orders of the following entries and data, you may contact me here directly.
