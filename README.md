# git-branch-dates

## Overview

`git-branch-dates` is a shell script designed to fetch all branches in a Git repository and display their creation and last update dates in a neatly formatted table. This script can be useful for understanding the lifecycle of branches in a project.

## Features

- Lists all local and remote branches.
- Displays creation and last update dates for each branch.
- Provides a clear and formatted output to help with branch management.

## Setup Instructions

### Download and Install

1. **Download the script**: Save the `git-branch-dates` script to your preferred directory.

   For macOS and Linux, you can use the following command to place it in a globally accessible location:
   
   ```bash
   sudo nano /usr/local/bin/git-branch-dates
   ```

2. Make the script executable by running:
   ```bash
   sudo chmod +x /usr/local/bin/git-branch-dates
   ```

3. To use the script globally, run:
   ```bash
   git-branch-dates
   ```
   This command will display the branch dates from any Git repository on your system.
