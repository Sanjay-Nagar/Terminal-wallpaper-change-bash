# Update Terminal Background and Theme Script

This repository contains a bash script designed to change the terminal app background for Windows via WSL and set the wallpaper theme for your terminal text.

## Prerequisites

Before you can use this script, ensure you have the following installed:

- **WSL (Windows Subsystem for Linux)**
- **Required Tools:**
  - `pywal`
  - `zsh`

## Installation

Follow these steps to clone the repository, move the script to the appropriate directory, and give it executable permissions.

1. **Clone the repository:**

    ```sh
      git clone https://github.com/Sanjay-Nagar/Terminal-wallpaper-change-bash.git
    ```

2. **Navigate to the repository:**

    ```sh
    cd Terminal-wallpaper-change-bash
    ```

3. **Move the script to `/usr/local/bin`:**

    ```sh
    sudo mv update-cmd-wall /usr/local/bin/
    ```

4. **Give the script executable permissions:**

    ```sh
    sudo chmod +x /usr/local/bin/update-cmd-wall
    ```

## Usage

Once installed, you can update your terminal background and theme by running:

```sh
update-cmd-wall

