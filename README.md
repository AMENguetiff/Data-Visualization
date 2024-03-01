# 📚 Project description

<strong>The project seeks to analyze and forecast the math, reading, and writing scores of high school students in the United States</strong>, aiming to uncover the key determinants driving academic achievement in these areas.(https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) (Student's performance in exams) : 

# Interactive Data Visualization

The primary aim of this project is to craft an interactive data visualization dashboard, enabling the analysis of student performance through diverse lenses. This dashboard seeks to uncover insights into the interplay between student achievement and variables such as gender, ethnicity, parental education, lunch provisions, and participation in test preparation courses. By scrutinizing these relationships, users can deepen their understanding of how these factors impact academic progress, empowering them to make informed decisions in shaping educational policies and practices.

## Code Overview

The provided code imports essential libraries, loads the data, and preprocesses it to establish an interactive dashboard. This dashboard incorporates various visualization methods and machine learning models to dissect the data and extract valuable insights. The code structure can be segmented into the following sections:

### Preprocessing

The CSV file is imported, and its data is stored in a Pandas dataframe. This dataset comprises students' scores in math, reading, and writing, alongside their gender, race/ethnicity, parental education level, lunch status, and participation in test preparation courses. Additionally, a new binary feature named 'pass' is generated to signify whether a student has achieved a score of 60 or higher in all three subjects.

### Libraries and Panel Extensions

The code uses Plotly, Matplotlib, Seaborn, HoloViews, and Panel for data visualization and interactive elements. These libraries are imported, and necessary extensions are enabled for smooth rendering and interactivity.

### Dashboard Components

The dashboard is designed using Panel, a high-level app and dashboarding solution for Python. Various widgets like checkboxes, dropdowns, and sliders are created to allow users to interact with the dashboard and customize the visualizations.

### Interactive Components

Interactive components are defined through Panel's bind function, allowing visualizations to update automatically as users interact with the widgets. These interactive elements are generated for each visualization and machine learning model employed in the dashboard.

### Dashboard Layout

The dashboard is structured into three primary sections: Exploration, Modeling, and Analysis. Within each section, there is a sidebar housing widgets for user interaction, alongside a main content area presenting visualizations and results.

### Exploration

This section allows users to explore the dataset using histograms, scatter plots, box plots, and target plots. Users can customize the visualizations by selecting features and adjusting other settings through the sidebar widgets.

### Modeling

Within this segment, machine learning models are integrated for both regression and classification tasks. Users have the option to choose from various models and target variables. The dashboard showcases evaluation metrics, Q-Q plots, scatter plots, and confusion matrices to provide comprehensive insights.

### Analysis

In this section, supplementary statistical analysis is offered.

## Documentation

For more detailed documentation, please visit our [official documentation](https://pypi.org/project/dashboard-dataviz-panel/0.1.3/).
