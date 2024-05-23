# Todo Shell script 

## Overview

The `todo` script is a command-line tool for managing todo tasks. It allows users to create, update, delete, and view tasks stored in a JSON file 🗓️.

## Dependencies

- [jq](https://stedolan.github.io/jq/): A lightweight and flexible command-line JSON processor used for handling JSON data.

## Installation

1. **Git:**
   - If not already installed, install Git using your package manager:
     ```bash
     sudo apt update
     sudo apt install git
     ```

2. **jq:**
   - If not already installed, install `jq` using your package manager:
     ```bash
     sudo apt update
     sudo apt install jq
     ```

## How to Use

1. **Clone Repository:**
   ```bash
   git clone https://github.com/bigam128/todo.git

2. **Run Script:**

   Navigate to the directory:
     ```bash
     cd todo
     ```
   Run the script:
     ```bash
     ./todo
     ```
     This command will display completed and uncompleted tasks for the current day.


3. **Creating a Task:**

    To create a new task, run:

    ```bash
    ./todo -c
    ```
    Make sure you enter the information required.


4. **Updating a Task:**

    To update an existing task, run:

    ```bash
    ./todo -u id
    ```


5. **Deleting a Task:**

    To delete a task, run:

    ```bash
    ./todo -d id
    ```

    
6. **Searching for a Task:**

    To search for a task by title, run:

    ```bash
    ./todo -s "task title"
    ```

7. **Help** 

    To get Help and see the commands, run:

    ```bash
    ./todo -h
    ```


