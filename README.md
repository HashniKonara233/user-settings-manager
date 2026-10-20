# User Configuration Manager

## 📌 Project Overview

The **User Configuration Manager** is a simple Python program that allows users to manage their configuration settings. It supports adding, updating, deleting, and viewing settings stored in a Python dictionary.

This project demonstrates fundamental Python concepts such as dictionaries, functions, tuples, conditional statements, loops, and string manipulation.

## 🎯 Objectives

- Add new user settings.
- Update existing settings.
- Delete settings that are no longer needed.
- View all saved settings in a readable format.
- Handle invalid operations with appropriate error messages.
- Convert setting keys and values to lowercase for consistency.

## ⚙️ Features

### 1. Add Settings
The `add_setting()` function adds a new setting if the key does not already exist. It returns a success message when the setting is added or an error message if the key already exists.

### 2. Update Settings
The `update_setting()` function updates the value of an existing setting. If the setting does not exist, it returns an appropriate error message.

### 3. Delete Settings
The `delete_setting()` function removes an existing setting from the dictionary. If the key cannot be found, it returns an error message.

### 4. View Settings
The `view_settings()` function displays all current settings in a formatted list. If the dictionary is empty, it returns `No settings available.`

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Data Structure:** Dictionary
- **Concepts:** Functions, tuples, loops, conditional statements, and string methods

## 🚀 Getting Started

### Prerequisites

Install Python 3 on your computer.

### Running the Program

1. Clone or download this repository.
2. Open the project folder in your preferred code editor or terminal.
3. Save the Python code in a file named `main.py`.
4. Run the following command:

```bash
python3 main.py
```

## 💻 Example Usage

```python
test_settings = {
    'theme': 'light',
    'language': 'english',
    'notifications': 'enabled'
}

print(add_setting(test_settings, ('volume', 'HIGH')))
print(update_setting(test_settings, ('THEME', 'DARK')))
print(delete_setting(test_settings, 'LANGUAGE'))
print(view_settings(test_settings))
```

### Expected Output

```text
Setting 'volume' added with value 'high' successfully!
Setting 'theme' updated to 'dark' successfully!
Setting 'language' deleted successfully!
Current User Settings:
Theme: dark
Notifications: enabled
Volume: high
```

## 🧪 Testing

The program can be tested using different dictionaries and key-value pairs to verify that all functions work correctly.

Test cases should cover:

- Adding a new setting.
- Attempting to add a duplicate setting.
- Updating an existing setting.
- Attempting to update a non-existing setting.
- Deleting an existing setting.
- Attempting to delete a non-existing setting.
- Viewing an empty dictionary.
- Viewing a dictionary containing multiple settings.
- Checking lowercase conversion and output formatting.

## 📂 Project Structure

```text
user-configuration-manager/
├── main.py
└── README.md
```

## 📚 Learning Outcomes

By completing this project, I practiced:

- Creating and using Python functions.
- Working with dictionaries and tuples.
- Adding, updating, and deleting dictionary entries.
- Applying conditional logic and loops.
- Manipulating strings using built-in methods.
- Formatting output and handling edge cases.

## 📄 License

This project was created for educational and learning purposes.
