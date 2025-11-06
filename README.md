# n8n Workflow Collection

This repository is a collection of [n8n](https://n8n.io/) workflows for various automation tasks.

## About n8n

n8n is a free and open workflow automation tool. It allows you to connect different services and automate tasks without writing code.

## Structure

- `workflows/` - Contains all the n8n workflow files (JSON format)

## How to Use

1. Browse the workflows in the `workflows/` directory
2. Download the workflow JSON file you want to use
3. Import it into your n8n instance:
   - Open your n8n instance
   - Click on "Workflows" in the menu
   - Click "Import from File" or "Import from URL"
   - Select the downloaded JSON file

## Contributing

Feel free to contribute your own n8n workflows! Simply add your workflow JSON file to the `workflows/` directory with a descriptive name.

## Workflow Naming Convention

Please name your workflow files descriptively:
- Use lowercase letters
- Separate words with hyphens
- Include the main service or purpose
- Example: `slack-notification-on-error.json`

## License

The workflows in this repository are provided as-is for educational and automation purposes.