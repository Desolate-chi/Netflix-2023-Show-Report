# NYC TAXI PIPELINE

**Introduction**

In an era of exponential data growth, effective data storage and utilization have become critical for businesses. The ability to transform vast datasets into actionable insights is essential for informed decision-making. This project addresses the challenge faced by companies that possess large datasets but struggle to convert them into valuable insights. The goal is to create a workflow that extracts data from a company's website and integrates it with an open-source GUI to manage the database effectively.

**Data Preparation:**

To achieve this, we first need to understand the necessary steps:
1. **Directory Setup**: A new directory was created to ensure all project files are organized and stored securely. Git Bash was used for this purpose.
2. **Docker File**: A Docker file was created to handle the building of the necessary images.
3. **Python Script**: A Python script was developed to perform the entire ETL (Extract, Transform, Load) process.
4. **PG Network**: A PG network was established to create a connection between the database and the GUI tool.

**Data Processing:**

This project presented several challenges from the outset, but each was met with a prepared and strategic approach. Below is a list of the challenges encountered and how they were overcome:

**Data Cleaning:**

During the data ingestion process, three significant challenges were identified:
1. **File Format Conversion**: The data was initially stored in a Parquet format, but a CSV file was required for our purposes. To address this, the original file was downloaded, and a script was written to convert the Parquet file into a CSV format.
2. **Datetime Metadata**: The datetime column in the metadata was originally in a real data type, which needed to be converted to a datetime data type. This was achieved using the SQLAlchemy library.
3. **Database-GUI Connection**: Establishing a link between the database and a GUI for querying the dataset using SQL was another challenge. This was resolved by using PGNetwork, which facilitated a connection between the database and our database manager, PGAdmin.

**Data Analysis and Investment Insights:**

This project is designed to provide critical insights for investors in the dynamic entertainment sector. It addresses key questions that are essential for strategic decision-making in entertainment investments. The primary inquiries include:
1. **Total Monthly Sales of the Year**:
   - Analyze the financial transactions for each month to identify trends. Determine which month had the highest revenue and explore the reasons behind it.
2. **Highest Transaction Made**:
   - Identify the destination with the highest payout for the year. Examine its relationship to destinations with the highest number of requests and assess its impact on the overall annual transactions.
3. **Most Common Destination**:
   - Determine the destination with the highest number of passenger requests and evaluate its impact on the total transactions for the year.

These critical inquiries form the foundation for informed decision-making in the entertainment sector. Through comprehensive data visualizations derived from thorough dataset analysis, this project provides investors with strategic and lucrative opportunities in the ever-evolving world of entertainment.
