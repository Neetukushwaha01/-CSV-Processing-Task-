# -CSV-Processing-Task-
 CSV Processing Task   Blooprint
 Django CSV Upload & Processing Project - Documentation
1. Project Overview
This project is a Django web application that allows users to upload CSV files, process them asynchronously using Celery, and display dynamic results with search functionality. The application also performs various calculations like sum, average, count, total revenue, best-selling product, and most profitable product.

2. Features
CSV File Upload: Users can upload CSV files through a web interface.

Asynchronous Processing: Celery is used to process files in the background.

Dynamic Data Display: Uploaded data is displayed with search and filter options.

Calculations:

Total count of products

Sum and average of prices

Total revenue calculation

Best-selling product identification

Most profitable product determination

GitHub Submission: The final project is submitted via a GitHub repository


Process for CSV Upload & Processing in Django

Upload CSV File

User selects a CSV file and clicks the upload button.

The file is sent to the backend using a Django form.

File Validation

The backend verifies the file format (only .csv files allowed).

If invalid, an error message is displayed.

Saving File

The uploaded CSV file is stored in the media directory.

Processing CSV with Celery

A Celery task is triggered asynchronously to process the file.

Data is read from the CSV file and inserted into the database.

Calculations & Analysis

Sum, average, count, total revenue, best-selling product, and most profitable product are calculated from the uploaded data.

Displaying Processed Data

The processed data is retrieved from the database.

Search functionality allows users to filter results dynamically.

Error Handling & Logging

Any issues during upload or processing are logged for debugging.

Users receive appropriate error messages if something goes wrong.

Final Submission

The project, including code and documentation, is pushed to GitHub.

front page  looking liks this --
http://127.0.0.1:8000/
![image](https://github.com/user-attachments/assets/9198e925-8796-4801-ad22-1edd2107cb5f)

