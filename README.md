# Data-Analysis-using-LLM-Datahorse
This code demonstrates an AI-driven approach to analyzing and visualizing data using LangChain, Datahorse, and OpenAI's GPT-3.5-turbo. It provides an interactive way to query, preprocess, and visualize data directly in Python, leveraging the power of natural language for data operations.
Key Features:

    AI-Driven Data Interaction:
        Use GPT-3.5-turbo to interact with a Pandas DataFrame for querying data properties like categorical and numeric columns.
        Perform exploratory data analysis (EDA) tasks via conversational queries.

    Datahorse Integration:
        Simplifies data analysis through conversational commands, offering a seamless experience for EDA and preprocessing.
        Supports interactive visualizations like pairplots, barplots, scatter plots, histograms, box plots, and heatmaps.

    End-to-End Workflow:
        Data Loading: Load the StudentPerformanceFactors.csv dataset for analysis.
        EDA and Visualization: Generate insights and visualizations with simple chat commands.
        Data Preprocessing:
            Apply standard scaling to numeric columns.
            Encode categorical columns into numeric formats for machine learning.

The code enables users to:

    Query dataset information such as columns, numeric/categorical types, and more.
    Generate common visualizations like: Pairplots, barplots, scatter plots, histograms, box plots, and heatmaps.
    Preprocess data through standard scaling and encoding.

Libraries Used:

    LangChain: AI model integration for interactive queries.
    Datahorse: An intuitive library for conversational EDA and visualization.
    OpenAI GPT-3.5-turbo: For natural language processing and AI-driven data interaction.
    Pandas: For data manipulation and handling.

Example Workflow:

    Load the dataset using Datahorse.
    Query dataset properties (e.g., column types, summary statistics) via .chat() commands.
    Visualize data with minimal effort through intuitive commands.
    Apply preprocessing techniques like scaling and encoding interactively.

This framework enables streamlined, user-friendly EDA and preprocessing workflows, making it an excellent tool for data scientists, analysts, and ML engineers.
