Certainly! Here’s a description you could use for your GitHub repository:

---

# Quote Generator

A simple Python application that fetches and displays random quotes using the `requests` library and `ttkbootstrap` for the GUI.

![image](https://github.com/user-attachments/assets/763806dd-d2f2-43ee-a2bd-0f40eb205ece)


## Overview

This project is a basic GUI application built with Python that allows users to fetch and display random quotes. It uses the `requests` library to interact with the Quotable API and `ttkbootstrap` to provide a modern look and feel for the user interface.

## Structure of the program
 1. Import the necessary libraries: requests, ttk and ttkbootstrap
 2. Define the API endpoint to fetch quotes and create a function to get the quotes from the API
 3. Create the GUI application using Tkinter
 4. Create a frame in the GUI and add a label to display the quote and another label to display the author
 5. Add a button to fetch new quotes
 6. Define a function to update the quote and author labels
 7. Show the GUI using root.mainloop()

## Features

- **Fetch Random Quotes**: Retrieves random quotes from the Quotable API.
- **Modern GUI**: Utilizes `ttkbootstrap` to create a visually appealing and responsive interface.
- **Simple and Lightweight**: Designed to be easy to understand and extend.
  

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/T9113/Quote_Generator_Python.git
   cd quote-generator
   ```

2. **Create a Virtual Environment (Optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**

   ```bash
   pip install requests
   pip install ttkbootstrap


   ```

 

## Usage

1. **Run the Application**

   ```bash
   python main.py
   ```

2. **Interact with the GUI**

   - Click the "Get Quote" button to fetch a new random quote.
   - The quote and its author will be displayed in the application window.

## Code Overview

- **`main.py`**: Contains the main application logic and GUI setup.
  - `fetch_quote()`: Fetches a random quote from the Quotable API.
  - `update_quote()`: Updates the displayed quote and author in the GUI.
  - GUI setup: Creates the main window, frames, labels, and button using `ttkbootstrap`.

## Contributing

Feel free to open issues or submit pull requests if you have suggestions or improvements!


## Contact

For any questions or feedback, you can reach me at (tayyabmasood911@gmail.com).

---

