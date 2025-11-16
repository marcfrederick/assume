# assume

A simple interactive tool for assuming AWS profiles and setting up environment variables.

## Prerequisites

- [AWS CLI v2](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- [fzf](https://github.com/junegunn/fzf) - command-line fuzzy finder

## Installation

### From Source

1. Clone this repository:
   ```bash
   git clone https://github.com/marcfrederick/assume.git
   cd assume
   ```

2. Make the script executable:
   ```bash
   chmod +x assume
   ```

3. Add to your PATH (optional):
   ```bash
   sudo cp assume /usr/local/bin/
   ```

### Homebrew (macOS/Linux)

You can install `assume` using Homebrew:
```bash
brew install marcfrederick/homebrew-tap/assume
```

## Usage

```bash
eval $(./assume)
```

## License

This project is licensed under the GNU General Public License v3.0.
See the [LICENSE](LICENSE) file for details.
