# Obsidian config sync

This repository centralizes the Obsidian configuration files across multiple vaults. By symlinking this repository folder into each vault, you ensure that all vaults remain clean and can maintain individual backups. Additionally, any configuration changes made here will automatically sync across all vaults and devices with a simple push/pull.

## Benefits

- **Centralized Configuration:** Keep all Obsidian configuration settings in one location, making it easy to manage.
- **Cross-Vault Consistency:** Ensure all vaults have the same configuration without duplicating files.
- **Easy Sync Across Devices:** Push changes to this repository, and pull it on other devices to keep configuration consistent everywhere.

## Setup Instructions

1. **Clone this repository** to a central location, such as `~/.obsidian`:

  ```sh
  git clone <repository-url> ~/.obsidian
  ```

2. **Symlink the `.obsidian` folder** from this repository to each of your vaults.
  For example, if you have a vault located at `~/Documents/Docs`, create a symlink like this:

  ```sh
  ln -s ~/.obsidian ~/Documents/Docs/.obsidian
  ```

