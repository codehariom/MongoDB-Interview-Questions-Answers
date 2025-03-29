# MongoDB-Interview-Questions-Answers
 A comprehensive list of 50 MongoDB interview questions with detailed answers. This repository covers essential MongoDB concepts, including CRUD operations, indexing, aggregation, schema design, replication, and sharding. Perfect for developers preparing for MongoDB-related roles or anyone looking to strengthen their database knowledge.

### **How to Import a Dataset in MongoDB Compass**  

MongoDB Compass provides a graphical interface to easily import datasets into MongoDB. Follow these steps:  

#### **Step 1: Open MongoDB Compass**  
- Launch **MongoDB Compass** on your system.  
- Connect to your MongoDB server (usually `mongodb://localhost:27017` for local setups).  

#### **Step 2: Select a Database and Collection**  
- Click on the **"Databases"** tab and choose the database where you want to import data.  
- If you don’t have a collection yet, click **"Create Collection"** and give it a name.  

#### **Step 3: Import Data**  
1. Inside your collection, click the **"Import Data"** button.  
2. Choose the file format (`JSON` or `CSV`).  
3. Click **"Browse"** and select your dataset file.  
4. If importing a CSV, check the **"First row is a header"** option to use column names as field names.  
5. Click **"Import"** to upload the dataset.  

#### **Step 4: Verify the Data**  
- After the import is complete, you will see the records displayed in the collection.  
- Click on any document to inspect its details.  

Now, your dataset is successfully imported into MongoDB Compass! 🚀 