
# GitLab Deploy Key Manager

This Python script automates the management of deploy keys across multiple projects on GitLab, providing a streamlined way to enable, check, and manage deploy keys efficiently.

## Features

- **List Deploy Keys**: Retrieve and display all deploy keys available in your GitLab instance.
- **Check Deploy Key Status**: Check whether each deploy key is enabled for specific projects.
- **Enable Deploy Keys**: Enable deploy keys on selected projects or across all projects where they are not currently enabled.

## Prerequisites

Before running this script, ensure you have the following:
- Python 3.x installed on your machine.
- The `requests` library installed, which can be added via pip if not already installed.

## Installation

To set up the GitLab Deploy Key Manager on your local machine, follow these steps:

1. Clone the repository:
   ```plaintext
   git clone https://github.com/morten03nordbye/gitlab-deploy-key-manager.git
   ```
2. Navigate to the cloned directory:
   ```plaintext
   cd gitlab-deploy-key-manager
   ```
3. Ensure Python3 and pip3 are installed:
   ```plaintext
   python3 --version
   pip3 --version
   ```
4. Install the required Python3 packages:
   ```plaintext
   pip3 install requests
   ```

## Usage

To use the script, follow these instructions:

1. Open your terminal.
2. Navigate to the script's directory.
3. Run the script using Python3:
   ```plaintext
   python3 gitlab.py
   ```
4. Follow the on-screen prompts to manage deploy keys.

## Configuration

Configure your GitLab API token and GitLab URL within the script to connect to your GitLab instance:

- Open the `gitlab.py` file.
- Find the lines containing `API_TOKEN` and `GITLAB_URL`.
- Replace `your_api_token` and `https://gitlab.yourdomain.com` with your actual API token and GitLab URL.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes. For more insights into my other projects and professional background, feel free to visit my portfolio at [nordbye.it](https://nordbye.it/).

## License

This project is licensed under the Apache License 2.0. A copy of the license is available in the repository in the LICENSE file. It can also be viewed [here](https://www.apache.org/licenses/LICENSE-2.0).
