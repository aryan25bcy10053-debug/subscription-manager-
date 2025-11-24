# Basic Subscription Manager

## Overview of the Project

This project is a simple, command-line utility designed to help users track their recurring monthly subscription expenses. The core functionality involves collecting subscription names and their corresponding costs, storing them in a list-of-dictionaries data structure, and then calculating and displaying the total monthly expenditure.

The primary educational goal of this assignment is to demonstrate proficiency in:
* Using **basic Python I/O** (Input/Output) for user interaction.
* Implementing **loops** (`while`) for continuous data collection.
* Applying **try-except blocks** for robust **input validation** (specifically for numeric cost input).
* Utilizing **Python data structures**, namely a **list of dictionaries**, to store structured, related data records.
* Performing simple data **aggregation** (calculating the total sum).

## Features

* **Interactive Data Entry:** Users can input subscription names and costs one after another.
* **Sentinel Value Termination:** The data entry process is gracefully ended by typing 'done'.
* **Robust Cost Validation:** Ensures that the entered cost is a valid positive number using a `try-except` block.
* **Structured Storage:** Uses a **list of Python dictionaries** (`{'name': str, 'cost': float}`) to maintain clear, named data fields.
* **Total Cost Calculation:** Automatically sums up all entered costs to provide the total monthly expenditure.
* **Formatted Output:** Displays the list of subscriptions and the final total with clean, dollar-formatted (two decimal places) output.

## Technologies/Tools Used

| Tool/Technology | Description |
| **Python** | The primary programming language used (Tested on Python 3.x). |
| **Command Line Interface (CLI)** | The environment where the script is run and interacts with the user via `input()` and `print()`. |
| **Dictionaries** | Used for storing individual subscription records (e.g., `{'name': 'Netflix', 'cost': 9.99}`). |
| **Lists** | Used to collect and manage the sequence of all subscription records. |

## Steps to Install & Run the Project

Since this is a single-file Python script, installation is straightforward.

### Prerequisites
* You must have **Python 3.x** installed on your system.

### Installation & Setup

1.  **Clone the Repository (or download the file):**
    ```bash
    git clone [Your-GitHub-Repository-URL]
    cd basic-subscription-manager
    ```
    *Alternatively, simply save the code into a file named `subscription_manager.py`.*

2.  **Execute the Script:**
    Open your terminal or command prompt, navigate to the directory where you saved the file, and run:
    ```bash
    python subscription_manager.py
    ```

### Example Execution

Upon running the script, the user will be prompted for input:
