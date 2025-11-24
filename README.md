# Studio Manager

CLI tool for managing Hanzo Studio installations, updates, and custom nodes.

## Features

- Install and update Hanzo Studio
- Manage custom nodes and extensions
- Configure Studio settings
- Backup and restore workflows
- System diagnostics and troubleshooting

## Installation

```bash
npm install -g @hanzo-studio/studio-manager
# or
pip install studio-manager
```

## Usage

```bash
# Install Hanzo Studio
studio-manager install

# Update to latest version  
studio-manager update

# Manage custom nodes
studio-manager nodes list
studio-manager nodes install <node-name>
studio-manager nodes update [node-name]

# Configuration
studio-manager config set <key> <value>
studio-manager config get <key>
```

## Development

Coming soon...

## License

MIT
