# Bash Crash Course

Welcome to the **Bash Crash Course** repository! This project is based on the YouTube course [Bash Scripting Crash Course](https://www.youtube.com/watch?v=2733cRPudvI&list=PLT98CRl2KxKGj-VKtApD8-zCqSaN2mD4w&index=1), which is an excellent resource for anyone who wants to dive deep into the fundamentals of Bash scripting. This repository provides all the notes, scripts, and exercises to accompany the video lessons in the course.

## Table of Contents

1. [About the Course](#about-the-course)
2. [Repository Structure](#repository-structure)
3. [Installation and Setup](#installation-and-setup)
4. [How to Use](#how-to-use)
5. [Topics Covered](#topics-covered)
6. [Contributing](#contributing)
7. [License](#license)

## About the Course

This course is designed for beginners who are new to Bash scripting and Linux command-line interfaces (CLI). The course explains basic concepts of Bash scripting, shell commands, and automation, providing a solid foundation for further learning and practical use.

### YouTube Playlist:
- [Bash Scripting Crash Course](https://www.youtube.com/watch?v=2733cRPudvI&list=PLT98CRl2KxKGj-VKtApD8-zCqSaN2mD4w&index=1)

## Repository Structure

```bash
├── README.md                   # Course overview and instructions
├── scripts/                    # Bash scripts for each topic covered
└── resources/                  # Additional resources for learning Bash scripting
```

### Folders:
- **`scripts/`**: Contains scripts corresponding to lessons in the YouTube playlist.
- **`resources/`**: Additional reading material, reference guides, and useful links.

## Installation and Setup

### Prerequisites:
- **Bash Shell**: Bash is pre-installed on most Linux and macOS systems. You can check if it's installed by running:
  ```bash
  bash --version
  ```
- **Windows**: Windows users can use Git Bash or install WSL (Windows Subsystem for Linux) to use a Bash shell.

### Clone the Repository:
1. Clone this repository to your local machine:
   ```bash
   https://github.com/brumocas/Bash_Scripting.git
   ```
2. Navigate to the repository folder:
   ```bash
   cd Bash_Scripting
   ```

## How to Use

1. Watch the video lessons from the YouTube playlist [here](https://www.youtube.com/watch?v=2733cRPudvI&list=PLT98CRl2KxKGj-VKtApD8-zCqSaN2mD4w&index=1).
2. Try running the example scripts from the **`scripts/`** folder:
   ```bash
   bash scripts/hello_world.sh
   ```

## Topics Covered

The course covers a range of topics that are fundamental to Bash scripting:

- **Lesson 1: Introduction to Bash**  
  Introduction to the shell, what Bash is, and why it's important for scripting and automation.

- **Lesson 2: Basic Shell Commands**  
  File and directory manipulation commands such as `ls`, `cd`, `cp`, `mv`, `rm`.

- **Lesson 3: Variables in Bash**  
  Working with variables, how to create and use them, and environment variables.

- **Lesson 4: Conditionals and Loops**  
  If statements, `for`, `while`, and `until` loops, and how to control flow in scripts.

- **Lesson 5: Functions**  
  Defining and using functions to modularize code and reuse logic.

- **Lesson 6: Input/Output & Redirection**  
  Handling input/output, redirection with `>`, `>>`, `<`, and piping `|`.

- **Lesson 7: Error Handling**  
  Using exit statuses, `trap`, and other techniques for error management.

- **Lesson 8: Scripting Automation**  
  Automating repetitive tasks using scripts, cron jobs, and scheduling tasks.

- **Lesson 9: Advanced Bash Techniques**  
  Regular expressions, text manipulation with `sed`, `awk`, and process control.

Each folder contains scripts, examples, and notes specific to the lesson being covered.

## Contributing

If you'd like to contribute to this repository, feel free to submit a pull request! Contributions can include:
- Adding new Bash scripts.
- Writing new exercises or improving existing ones.
- Enhancing documentation or notes.
- Reporting issues or bugs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding and enjoy learning Bash scripting!