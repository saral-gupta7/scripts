# Personal Scripts Collection

A collection of utility scripts for various automation tasks and workflows.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/saral-gupta7/scripts
cd ~/scripts
```

### Modify Scripts for Your Usage

These scripts are designed to be easily customizable. Here's how to adapt them:

1. **Review the scripts**: Browse through the files to understand what each script does
2. **Update paths**: Many scripts may contain hardcoded paths specific to my setup. Search for and update:
   - Home directory references
   - Application paths
   - Configuration file locations
3. **Adjust configurations**: Modify variables at the top of scripts to match your environment
4. **Make scripts executable**:
   ```bash
   chmod +x script-name
   ```

### Adding Scripts to Your PATH

To use these scripts from anywhere:

```bash
# Add to your ~/.zshrc or ~/.bashrc
export PATH="$HOME/scripts:$PATH"
```

Then reload your shell:

```bash
source ~/.zshrc  # or ~/.bashrc
```

## Usage Tips

- Read through each script before running it
- Test scripts in a safe environment first
- Back up important data before running system-modifying scripts
- Customize script behavior by editing configuration variables
