### Web Content Saver
An automated web content saving and summarization system featuring:

- Form-triggered content submission
- AI-powered summarization using Gemini and DeepSeek
- Automated saving to Google Docs
- HTTP request integration for content fetching
- Memory buffer for context management

## Implementation Details

### Web Content Saver Implementation
The web content saver workflow automates the process of summarizing and storing web content:

1. **Content Submission**:
   - Users submit website links via a web form
   - Form validation and bot protection

2. **AI Content Processing**:
   - Reads and analyzes website content
   - Generates clear, structured summaries
   - Preserves key details and facts

3. **Document Management**:
   - Creates or updates Google Docs documents
   - Organizes content with descriptive titles
   - Includes original link references

#### Web Content Saver Workflow
![Web Content Saver Output](./Web%20Content%20Saver.jpg)

![Web Content Saver Workflow](./Web%20Content%20Saver%20n8n%20workflow.jpg)



## Getting Started

To use these workflows:

1. Create a workflow in n8n portal
2. Import the desired JSON workflow file
3. Configure your credentials for:
   - Google Docs (for document creation and updates)
   - Google Gemini API (for AI summarization)
   - DeepSeek API (for additional AI processing)
4. Customize the workflow parameters as needed
