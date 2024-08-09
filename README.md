# Disk Temperature Monitor

## Disclaimer

**Disclaimer:** This project is provided "as-is" without any warranties or guarantees. Use it at your own risk. The authors are not responsible for any damages or issues that arise from the use of this software. By using this project, you acknowledge and agree to these terms.


<p align="center">
  <img src="https://socialify.git.ci/SexyWerewolf/Disk_Temperature/image?font=Inter&amp;forks=1&amp;issues=1&amp;language=1&amp;logo=https%3A%2F%2Favatars.githubusercontent.com%2Fu%2F78776000%3Fv%3D4&amp;name=1&amp;owner=1&amp;pattern=Solid&amp;stargazers=1&amp;theme=Dark" alt="project-image">
</p>

<p align="center">Monitor your disk's temperatures with alerts via Telegram notifications.</p>

## Table of Contents

1. [Project Screenshots](#project-screenshots)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contribution Guidelines](#contribution-guidelines)
6. [License](#license)
7. [Creator](#creator)

## Project Screenshots:

<p align="center">
  <img src="https://github.com/SexyWerewolf/Disk_Temperature/blob/main/demo1.jpg?raw=true" alt="project-screenshot" width="400" height="400">
  <img src="https://github.com/SexyWerewolf/Disk_Temperature/blob/main/demo2.jpg?raw=true" alt="project-screenshot" width="400" height="400">
  <img src="https://github.com/SexyWerewolf/Disk_Temperature/blob/main/demo3.jpg?raw=true" alt="project-screenshot" width="400" height="400">
</p>

## Features

Here're some of the project's best features:

*   Add Disk
*   Remove Disk
*   Set Global Critical Temperature
*   Set Critical Temperature Per Disk
*   Change Bot Token & Chat ID

## Installation

1. **Install smartmontools**
    ```bash
    sudo apt update
    sudo apt install smartmontools -y
    ```

2. **Clone the repository:**

    ```bash
    git clone https://github.com/SexyWerewolf/Disk_Temperature.git
    ```

3. **Move and set permissions:**

    ```bash
    sudo mv Disk_Temperature/disktemp /usr/local/bin/
    sudo chmod +x /usr/local/bin/disktemp
    ```

4. **Run the configuration:**

    ```bash
   sudo disktemp -conf
    ```

5. **Start monitoring:**

    ```bash
    disktemp
    ```

## Usage

To keep the monitoring script running in the background, you should use **`tmux`** or **`screen`**.

## Contribution Guidelines

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

For bug reports or feature requests, please open an issue on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Creator

This project was created by **Dachi Wolf**.

For more projects and information, visit [GitHub Profile](https://github.com/SexyWerewolf).
