# VNR_Result_Retriever

VNR Result Retriever is a Python-based automation tool designed to streamline the process of collecting and storing student result screenshots from the VNRVJIET results portal. The tool automatically captures screenshots of student results based on their roll numbers, consolidates the images into a single PDF, and provides easy access to the final output.

### Key Features:
- Automatically captures **screenshots** of results by entering roll numbers from a user-defined list.
- Converts captured screenshots into a **PDF document** for easy sharing and storage.
- Supports adding roll numbers in **ranges (both numeric and alphanumeric)** and miscellaneous formats, with exclusion options.
- Allows users to choose the **destination folder** to save screenshots and PDFs.
- Adjustable **delay time** to accommodate slower computers or internet connections.
- **Fail-safe Mechanism**: Stops the process if the mouse pointer is moved to the top-left corner of the screen, ensuring user control at all times.

### Usage Instructions:

1. **Roll Number Input**:  
   - You can input roll numbers in various formats:
     - **Range**: Input a starting and ending roll number, and the tool will automatically generate all the roll numbers within that range.
     - **Miscellaneous Roll Numbers**: Manually input individual roll numbers separated by commas.
     - **Exclusion List**: Option to exclude specific roll numbers from the final list.

2. **Folder Selection**:  
   - After finalizing the roll numbers, select a folder to save the screenshots and PDF document. The script will open a file dialog box for folder selection.

3. **Results Automation**:  
   - Once the results page is opened, simply click the link to start the script. It will:
     - Enter each roll number.
     - Capture and save a screenshot of the results.
     - Consolidate all screenshots into a PDF at the end of the process.

4. **PDF Generation**:  
   - The final PDF will be saved in the selected folder, with the name being a combination of the first and last roll numbers in the list.

5. **Fail-Safe Mechanism**:  
   - Move the mouse to the top-left corner of the screen to stop the script at any time.

### How to Run:
Download the EXE file from the releases section, and double click to run it.

### Future Scope (RUST VERSION):

VNR Result Retriever (Rust) - Alpha Pre-release
- The RUST version of this project is available in the releases section as an alpha pre-release.
- This release offers a simplified feature set, allowing you to automatically capture student result screenshots from the VNRVJIET portal based on a single range of roll numbers.
- While PDF generation and advanced roll number handling (misc rolls, exclusion list, multiple ranges) are not yet available, this version provides a very fast and lightweight solution for batch result retrieval, making it 70% efficient.
- Stay tuned for future updates with more features!

---

This tool is specifically designed for students & faculty of VNRVJIET but can be adapted to similar web-based result portals with modifications.
