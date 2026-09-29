# Customer Welcome Message Automation

My first n8n workflow, built to practice workflow automation, structured data, and dynamic expressions.

## Project Overview

This workflow generates a personalized customer welcome message using sample customer information. It demonstrates how data can move between connected nodes in n8n.

## Workflow

1. **Manual Trigger:** Starts the workflow when executed manually.
2. **Customer Details:** Creates sample customer name, email, and product fields using Edit Fields.
3. **Generate Welcome Message:** Uses an n8n expression to create a personalized message.
4. **Output:** Displays the customer details and generated message for verification.

## Example Input

- Customer name: Mehreen
- Customer email: mehreeen@n8n.com
- Product: AI Automation Course

## Example Output

Hi Mehreen, welcome to AI Automation Course! We're excited to have you with us.

## Requirements

- An n8n Cloud account or a self-hosted n8n instance.
- No external API keys are required.

## How to Import and Run

1. Download `customer-welcome-automation.json` from this repository.
2. Open your n8n workspace.
3. Create a workflow or open the workflow editor.
4. Use the workflow menu to import the downloaded JSON file. Menu labels may vary by version.
5. Inspect the nodes and verify that the expression and field names match this documentation.
6. Click Execute Workflow and inspect the final node's output.

## Concepts Practiced

- Workflow triggers and connected nodes
- Structured data fields
- Dynamic expressions using `$json`
- Workflow execution and output verification

## Current Limitations

This is a beginner practice project. It generates a message but does not send an email, use an AI model, or connect to a customer database.

## Future Improvements

- Read customer records from Google Sheets
- Send welcome emails through an email integration
- Add input validation and error handling
- Explore AI-generated message variations

## Author

Mehreen Fatima

## License

This project is available for learning and educational purposes.
