# PDF to Interactive Dashboard Converter

This project automates the process of converting PDF documents into interactive dashboards using AI-powered code generation and Plotly Dash. With this workflow, you can create data-driven visualizations from PDF content in minutes.

## Features

- Converts PDF data into interactive Plotly Dash dashboards
- Supports multiple AI chatbots for code generation (e.g., ChatGPT 4, Mistral Large 2, Claude Sonnet 3.5, Llama 405b)
- Creates modern, clean visualizations with interactive elements
- Compatible with Replit for easy deployment and sharing

## Workflow

1. **Generate Dashboard Code**
   - Use the provided prompt with an AI chatbot to generate Python code for the dashboard.
   - The prompt instructs the AI to create a script using Plotly Dash with specific features and styling.

2. **Prepare Data**
   - Upload your PDF file (or XLSX, CSV) containing the data you want to visualize.

3. **Deploy Dashboard**
   - Create a new Python Repl on Replit.com.
   - Paste the AI-generated code into the Repl.
   - Run the code to generate your interactive dashboard.

## Usage

1. Copy the following prompt and send it to your preferred AI chatbot along with your PDF data:

   ```
   You're a Python developer with experience in creating data-driven visualizations. Develop a Python script to build a very modern looking (clean fonts, colors), interactive dashboard that:
   - Displays the evolution of the key figures in this PDF document with appropriate type of charts, filters, etc.
   - Create as many charts as necessary, one below the other.
   - Don't hesitate to compare current figures with previous periods.
   - Use Plotly Dash for the dashboard.
   - Ensure the code is compatible with Replit.
   The dashboard should include dynamic features like hover effects, filters by year, and interactive legends.
   Format the script with comments explaining key sections and use a clear, professional tone throughout the code. Think step by step to avoid code errors. Just write the full script.
   ```

2. Upload your PDF file to the AI chatbot before sending the prompt.

3. Copy the generated code and paste it into a new Python Repl on Replit.com.

4. Run the code to view your interactive dashboard.

## Deployment

To share your dashboard, you can use Replit's deployment features to generate a simple link that others can access.

## Contributing

Feel free to fork this project and submit pull requests with improvements or additional features.

## License

