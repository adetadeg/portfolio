# Power BI Portfolio

Welcome to my Power BI portfolio! This repository showcases my expertise in data visualization and analytics using Power BI. Each project demonstrates different aspects of my skills, including data modeling, DAX calculations, and dashboard design.

## Projects

1. **[Sales Dashboard](https://github.com/adetadeg/portfolio/blob/main/README.md)**  
   A dashboard showing a comprehensive analysis of total lifetime sales, year-over-year sales percentage growth from 2010 to 2013, and sales trends. It includes an interactive drilldown feature for a salesperson dashboard, displaying cumulative sales by month and year-over-year performance. Additionally, the dashboard highlights top-selling regions, resellers, and products, offering detailed revenue insights through dynamic visualizations.

   - **[Sales_Analysis.pbix](https://github.com/adetadeg/portfolio/tree/main/Sales_Dashboard)**
   - **[Dashboard Screenshot](./Sales_Dashboard/Dashboard_Screenshot.png)**

2. **[Customer Segmentation Analysis](./Customer_Segmentation/README.md)**  
   A project showcasing the segmentation of customers based on purchasing behavior, with insights into marketing opportunities.

## Data Sources

This project uses the **AdventureWorks** dataset, which is provided by Microsoft for sample data analysis. I would like to thank Microsoft for making this dataset available, which helped to enrich this analysis.

To replicate the projects:
1. Download and restore the **AdventureWorks** database from Microsoft or use the provided **[AdventureWorks.bak](https://github.com/adetadeg/portfolio/tree/main/PowerBI_Portfolio/0.%20AdventureWorks_Backup)** file.
2. Follow these steps to restore the **.bak** file in SQL Server:
   - Open SQL Server Management Studio (SSMS).
   - Right-click on "Databases" and choose "Restore Database."
   - Choose the **AdventureWorks.bak** file from the repository or your local folder.
   - Follow the prompts to restore the database.
3. Connect Power BI to the restored **AdventureWorks** database and recreate the data models and visualizations as seen in the Power BI reports.

Feel free to explore each project folder to see the `.pbix` files, screenshots, and additional details.

## File Structure

Here is the file structure of this repository:

```plaintext
PowerBI_Portfolio/
├── README.md                      # This file
├── Sales_Dashboard/               # Sales Dashboard project folder
│   ├── Sales_Analysis.pbix         # Power BI file with sales analysis
│   ├── Dashboard_Screenshot.png    # Screenshot of the dashboard
│   └── README.md                   # Detailed description of the Sales Dashboard project
├── Customer_Segmentation/          # Customer Segmentation project folder
│   ├── Customer_Segmentation.pbix  # Power BI file with customer segmentation analysis
│   ├── Dashboard_Screenshot.png    # Screenshot of the customer segmentation dashboard
│   └── README.md                   # Detailed description of the Customer Segmentation project
└── AdventureWorks_Backup/           # Folder containing the AdventureWorks .bak file
    └── AdventureWorks.bak          # The backup file
