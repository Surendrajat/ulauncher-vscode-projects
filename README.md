# Ulauncher SublimeMerge

## Requirements

- Ulauncher 5
- Python 3
- Visual Studio Code with [Project Manager](https://github.com/alefragnani/vscode-project-manager) extension installed.
- Sublime merge

## Install

Open ulauncher preferences window -> extensions -> add extension and paste the following url:

```
https://github.com/Surendrajat/ulauncher-vscode-projects-smerge
```

## Usage

- Type `sm` into ulauncher input to see a list your VS Code projects. (only git based projects are supported for now.).
- "Enter" will open the VS Code projects in Sublime merge while "ALT + Enter" will open in the default file manager.

If you save the message saying "No project found" make sure you the the VS Code Extension correctly installed. You might need to refresh your projects list
so the cache file read by this extension will be created. "F1 -> Project Manager: Referesh Projects".

## Development

```
git clone https://github.com/Surendrajat/ulauncher-vscode-projects-smerge
make link
```

The `make link` command will symlink the cloned repo into the appropriate location on the ulauncher extensions folder.

To see your changes, stop Ulauncher and run it from the command line with: `ulauncher -v`.

## Contributing

Contributions, issues and Features requests are welcome.
