# Ubuntu Environment Setup

This repository provides automated scripts to set up a Ubuntu environment with essential tools, Docker, and remote desktop capabilities via xRDP.

## Features

- **Environment Setup**: Updates the system, installs basic packages (net-tools, git, vim, ssh, ufw, traceroute, wget, curl), and disables screen saver and blank screen.
- **Docker Installation**: Installs Docker Engine, CLI, containerd, and Docker Compose plugin.
- **xRDP Installation**: Sets up xRDP for remote desktop access.

## Prerequisites

- Ubuntu operating system
- Sudo privileges
- Internet connection for downloading packages

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ubuntu-environment-setup.git
   cd ubuntu-environment-setup
   ```

2. Run the environment setup script:
   ```bash
   bash environment-setup
   ```

3. Install Docker:
   ```bash
   bash "Docker installation"
   ```
   **Note**: After Docker installation, you may need to reboot the system and log back in for group changes to take effect.

4. Install xRDP:
   ```bash
   cd xrdp-installation
   bash installation
   ```
   **Note**: Disable auto-login and reboot the server after installation.

## Usage

- After running the scripts, your Ubuntu environment will be configured with the specified tools.
- Use Docker commands as usual (e.g., `docker run hello-world`).
- Connect to the system via remote desktop using xRDP.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
