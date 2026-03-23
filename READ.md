# 📊 Sales ETL Pipeline Project

## 👋 Introduction

This is a beginner-friendly Data Engineering project.

In this project, we build a simple **ETL Pipeline** using Python.

👉 ETL means:

* **Extract** → Get data
* **Transform** → Clean and process data
* **Load** → Store or use the data

---

## 🎯 Project Goal

To understand how data flows from raw format to processed format using Python.

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas 📊
* CSV File 📁

---

## 📂 Project Structure

```
sales-etl-pipeline/
│
├── data/
│   └── sales.csv        # Raw data file
│
├── scripts/
│   ├── extract.py       # Reads data
│   ├── transform.py     # Cleans & processes data
│   └── load.py          # Displays final data
│
├── main.py              # Runs the pipeline
├── requirements.txt     # Libraries used
└── README.md            # Project explanation
```

---

## ⚙️ How It Works

### Step 1: Extract

* Reads data from CSV file

### Step 2: Transform

* Removes missing values
* Adds new column (sales with tax)

### Step 3: Load

* Displays final processed data

---

## ▶️ How to Run This Project

1. Open terminal
2. Go to project folder:

```
cd sales-etl-pipeline
```

3. Install libraries:

```
pip3 install pandas
```

4. Run project:

```
python3 main.py
```

---

## 📊 Example Output

* Raw data is printed
* Transformed data is printed
* Final data is shown

---

## 🚀 Future Improvements

* Connect to PostgreSQL database
* Add Apache Airflow scheduling
* Deploy on AWS cloud

---

## 💡 What I Learned

* Basics of ETL pipeline
* Working with CSV data
* Using Python for data processing

---

## 👨‍💻 Author

* Your Name
