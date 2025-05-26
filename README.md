# Chrono-Garden

**Cultivate a digital sanctuary that blossoms with your productivity! Chrono-Garden transforms your computer activity into a vibrant, ever-evolving garden.**

## Features

*   **Track User Activity:** Monitors various user activities (configurable, e.g., lines of code written, files saved, applications used).
*   **Unique Digital Plants:** Different "seeds" grow into unique digital plants based on activity types (e.g., a 'Python Vine' for .py files, a 'Document Daisy' for .md/.txt files).
*   **ASCII Art Garden:** Displays a beautiful ASCII art representation of your garden directly in the terminal.
*   **Dynamic Weather System:** Commit frequency influences the garden's "weather" (e.g., frequent commits bring 'sunshine', long gaps bring 'drought').
*   **Time-Lapse Growth:** Visualize your garden's evolution over a specified period with the "time-lapse" feature.
*   **Focused Work Sessions:** Option to "water" plants with focused work sessions, integrating with concepts like the Pomodoro technique.

## Installation

1.  **Prerequisites:** Ensure you have Python 3.7+ installed on your system.
2.  **Install Chrono-Garden:**
    ```bash
    pip install chrono-garden
    ```

## Usage

*   **Initialize and Start Tracking:**
    ```bash
    chrono-garden start
    ```
    This command initializes and starts tracking activity for the current directory.

*   **View Your Garden:**
    ```bash
    chrono-garden view
    ```
    Displays the current state of your digital garden in the terminal.

*   **Check Status:**
    ```bash
    chrono-garden status
    ```
    Shows statistics about tracked activities and the health of your plants.

*   **Generate Time-Lapse:**
    ```bash
    chrono-garden timelapse <period>
    ```
    Generates a time-lapse of your garden's growth. Examples for `<period>`: `last_week`, `last_month`.

*   **Water a Plant:**
    ```bash
    chrono-garden water <plant_name>
    ```
    Manually "water" a specific plant after a focused work session to boost its growth.

## Dependencies

*   Python 3.7+
*   `termascii` (for ASCII art rendering in the terminal)
*   `activity-monitor-lib` (a cross-platform activity tracking library)

## Contributing

We welcome contributions! Please feel free to fork the repository, create a feature branch, and submit a pull request.

For bugs and feature requests, please open an issue on the GitHub issue tracker for this project.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
