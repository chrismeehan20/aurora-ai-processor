# Aurora AI Processor for Sheets

A powerful Google Sheets add-on that leverages AI to process and analyze spreadsheet data.

Created by Chris Meehan - teacher, edtech leader, and very amateur astronomer.

## Features

- Process spreadsheet data with leading AI models from OpenAI, Anthropic Claude, and Google Gemini
- Create new columns with AI-generated insights
- Save and reuse custom prompts
- Process in batches to handle large spreadsheets efficiently
- Filter rows based on criteria
- Test processing on individual rows before running on entire datasets
- Track processing with detailed logs
- Save and load configurations for different tasks

## Installation

### Option 1: Install from Google Workspace Marketplace
1. Go to Extensions > Add-ons > Get add-ons
2. Search for "Spreadsheet AI Processor"
3. Click Install

### Option 2: Install from Script
1. Open your Google Sheet
2. Go to Extensions > Apps Script
3. Delete any code in the editor and paste the code from Code.gs
4. Create a new HTML file named Sidebar.html and paste the HTML code
5. Save and close the script editor
6. Refresh your Google Sheet
7. Find the add-on under Extensions > Spreadsheet AI Processor > Start AI Processing

## Setup

1. Click on "Start AI Processing" from the Extensions menu
2. In the sidebar that appears, select your preferred AI provider
3. Enter your API key(s) in the Advanced Options section

## How to Use

### Basic Processing

#### Configure AI Provider
- Choose OpenAI, Claude, or Gemini
- Select a model and adjust temperature

#### Select Data
- Choose which columns to process
- Optionally configure row filtering

#### Configure Prompt
- Enter instructions for the AI
- Use column variables with {{Column Name}} syntax
- Save frequently used prompts

#### Set Output
- Create a new column or use an existing one

#### Process Data
- Test on a single row first
- Run the processor on all selected data

### Advanced Features
- **Templates**: Enable variables in prompts to reference column values directly
- **Filtering**: Process only rows that match specific criteria
- **Batch Processing**: Control the number of rows processed at once
- **Saved Configurations**: Save entire setups for different processing tasks

## Example Use Cases

### Content Summarization
- Summarize long text entries in a concise format
- Extract key points from meeting notes or feedback

### Data Analysis
- Generate insights from numerical data
- Create interpretations of trends and patterns

### Content Creation
- Generate titles or headlines based on content
- Create descriptions or alternative phrasings

### Classification
- Categorize text entries
- Analyze sentiment or tone of comments

## Troubleshooting

- If processing stops unexpectedly, check the processing log for errors
- For rate limit errors, try reducing the batch size
- If you encounter token limit errors, try processing fewer columns or use a more concise prompt

## Privacy & Security

- API keys are stored securely in your Google user properties
- Your data never leaves your Google account except when being sent to the AI provider
- No data is stored on our servers

## Support

This is a personal project provided as-is with no official support. Documentation and code examples should help you troubleshoot most issues independently. Users are encouraged to fork the repository if they need custom modifications or to share solutions with the community if discovered.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
