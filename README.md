#🎧 The Spotify Data Pipeline! 🎶

Project Overview
This project demonstrates how to design and implement a scalable data pipeline for seamlessly moving and processing Spotify data using cloud services.

Key Steps in the Pipeline:
###1️⃣ Extract Data

Fetched Spotify data and uploaded it to an AWS S3 bucket using AWS Lambda.
2️⃣ Transform Data

Processed raw data into a structured format using AWS Lambda.
3️⃣ Load Data

Stored the processed data in S3 and performed analytics with AWS Athena.
Tools and Technologies Used
🛠️ AWS Services:
AWS Lambda: To run Python scripts for data extraction, transformation, and cleanup.
AWS S3: For scalable storage of both raw and processed data.
AWS Glue: For schema inference and automated table creation.
Amazon CloudWatch: To trigger the pipeline daily and monitor performance.
AWS Athena: To execute SQL queries on the processed data for analysis.
