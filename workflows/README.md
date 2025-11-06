# Workflows

This directory contains n8n workflow files in JSON format.

## Available Workflows

### example-workflow.json
A basic template workflow to get started. Contains only a Start node.

## Adding Your Workflow

To add your own workflow:

1. Export your workflow from n8n (Workflow menu → Download)
2. Add the JSON file to this directory
3. Use a descriptive filename (e.g., `github-issue-to-slack.json`)
4. Optionally, document your workflow in this README

## Workflow Documentation Template

When adding a new workflow, please provide a brief description:

### your-workflow-name.json
**Purpose:** Brief description of what this workflow does
**Triggers:** What starts this workflow (webhook, schedule, manual, etc.)
**Services Used:** List of services/nodes used (e.g., Slack, GitHub, HTTP Request)
**Requirements:** Any prerequisites or configuration needed
