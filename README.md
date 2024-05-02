# Google AI Hackathon

## Overview

This Jupyter notebook is developed for the Google AI Hackathon, focusing on advanced data analysis and visualization techniques to uncover insights from complex datasets. It leverages Gemini Pro and Gemini Pro Vision to facilitate the generation of graphs and insights from raw data extracted from Google Sheets.

## Key Features

- **Integration with GeminiPro for Graph Generation**: Seamlessly integrate Gemini Pro into the workflow to automate the generation of visually appealing and insightful graphs from data. Utilizing Gemini Pro's capabilities enhances the quality and efficiency of graph creation, facilitating better data representation. See example graphs generated inside the [google-ai-hackathon.ipynb](https://github.com/win-laeyee/google_AI_hackathon/blob/main/google-ai-hackathon.ipynb) notebook or the [image](https://github.com/win-laeyee/google_AI_hackathon/blob/main/image.png) PNG file.
- **Utilization of Gemini Pro Vision for Insights from Graph Images**: Harness Gemini Pro Vision to extract meaningful insights from graph images. By leveraging advanced image recognition features, the notebook analyzes graph images to derive actionable insights, enriching the data analysis process.
- **PDF Report Generation**: Generate professional-quality PDF reports summarizing the analysis findings and visualizations, providing a clear and concise overview of the dataset insights together with the generated graphs. View an example report generated in the [graph_insights_report.pdf](https://github.com/win-laeyee/google_AI_hackathon/blob/main/graph_insights_report.pdf) PDF file. 
- **Seamless Integration with Google Drive**: Retrieve raw data directly from Google Sheets, while also storing the generated insights PDF for easy access and sharing.

## Usage
1. Clone the repository. `git clone https://github.com/win-laeyee/google_AI_hackathon.git`
2. Open the notebook in a suitable IDE.
3. Ensure you have access to Google Gemini and Google Drive APIs to run the notebook:
- Obtain your Google Gemini API key [here](https://aistudio.google.com/app/apikey). Create a google_gemini_credentials.json file and store the API Key in the following format: {"GOOGLE_API_KEY": "YOUR_API_KEY"}
- To access the Google Drive API, create a Google Cloud project, enable the Google Drive API, and create credentials. Download the credentials in JSON format and rename the file as google_drive_api_credentials.json.
- Store both JSON files in the secrets/ directory.
4. Run the notebook cells sequentially to perform data analysis and visualization tasks.
- Ensure to update the folder_name and spreadsheet_name variables with your folder and spreadsheet names respectively, where the Google Sheet is stored and named.
5. Generate PDF reports by executing the designated cells that invoke the custom PDF generation scripts.
- Make sure to update the folder_name variable to specify the folder where you want to save your PDF.

## Data Source

The data used in this project is sourced from the following Kaggle dataset:

[Vehicle Sales Count by Year (2002-2023)](https://www.kaggle.com/datasets/adityakishor1/vehicle-sales-count-by-year-2002-2023?resource=download)
