# randPass-cli

A command-line password manager for securely generating, retrieving, updating, and deleting passwords. This tool uses advanced encryption to ensure your passwords are stored securely on your local system.

## Installation

To install randPass-cli, run the following command in your terminal:

```bash
npm install -g randpass-cli
```

## Usage

To start randPass, simply run:

```bash
randPass
```

You'll be prompted to enter your master password to access your encrypted password vault.

### Main Commands

- **Add a New Password**: Generates a new, secure password for a given username and website, and stores it securely.
- **Retrieve an Existing Password**: Displays a password for the specified website and username.
- **Update a Password**: Generates a new, secure password for an existing entry and updates it.
- **Delete a Password**: Removes a password entry from your vault.

### Navigating the CLI

- Use the arrow keys to navigate up and down through the menu options.
- Press `Enter` to select an option.
- Follow the prompts to add, retrieve, update, or delete passwords.

### Security

Your passwords are encrypted using AES-256 encryption and can only be accessed with your master password. Ensure you remember your master password, as there is no way to recover your encrypted passwords without it.

### Portable Backup

For secure storage on all devices, off the cloud, randPass-cli allows you to create a portable backup of your encrypted password vault. Simply copy the `passwords.enc` file generated by randPass-cli to any external storage device. This file is fully encrypted and can be safely transported or stored offline, providing an additional layer of security and flexibility.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with any improvements or additional features you'd like to suggest.

## License

Distributed under the MIT License. See `LICENSE` for more information.
